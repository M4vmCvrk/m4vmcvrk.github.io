---
layout: default
---

* * *

*   # M4vmCvrk
## Welcome to my videogame archive !

* * *

<input type="text" id="SearchTxt" /><input type="button" id="SearchBtn" value="Search" onclick="doSearch(document.getElementById('SearchTxt').value)" />
    <script>
        function doSearch(text) {
            if (window.find(text)) {
                console.log(window.find(text));
            }
        }
    </script>

* * *

## Games

## COMMING SOON

*   ### [](./games/.html)

```
:)
```

* * *

<script type="text/javascript" src="https://code.jquery.com/jquery-1.12.3.min.js"></script>

<script type="text/javascript">
    //<![CDATA[
        $(window).on('load', function() { // makes sure the whole site is loaded 
            $('#status').fadeOut(); // will first fade out the loading animation 
            $('#preloader').delay(350).fadeOut('slow'); // will fade out the white DIV that covers the website. 
            $('body').delay(350).css({'overflow':'visible'});
          })
    //]]>
</script>