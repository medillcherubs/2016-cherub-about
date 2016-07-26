# 2016-cherub-about
About page for the Cherubs 2016 website

https://medillcherubs.github.io/2016-cherub-about/

Paste this into your Wordpress post:

```
<div id="example"></div>
<script> var pymParent = new pym.Parent("example", "//medillcherubs.github.io/2016-cherub-about/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-cherub-about/edit/gh-pages/index.html -->
```

Paste this into the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script> <script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
