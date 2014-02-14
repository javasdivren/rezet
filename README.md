rezet
===

A basic CSS reset plus table helper and formatting class

<br>
There are __very good__ css reset like _normalize.css_ or _eric meyer css reset_ , etc

<br>
> But, this is for fun. As css reset, we have very simple table helper and formatting class

<br>
API
----
### reset :
* Just use your elements, we already reset them

<br>
### display class :
* `.none`

* `.block`

* `.inline`

* `.inline-block`

* `.table-cell`

* `.hidden` (this is not `display: hidden`) this is just to hide the element without broke your layout

<br>
### positioning :
* `.absolute`

* `.relative`

* `.fixed`

* `.static`

* `.left`

* `.right`

* `.center` (centering elements, not text)

* `.clear` (it contains `float: none; clear: both;`)

<br>
### formatting :
* `.bold`

* `.italic`

* `.bold-italic`

<br>
### color :
* `.black`

* `.white`

* `.red`

* `.blue`

<br>
### transition :
* `.transition-all`

* `.transition-color`

* `.transition-bg`

* `.transition-opacity`

example of use:
```sh
in html:
<div class="box transition-opacity"></div>

in css:
.box {width: 200px; height: 100px; background: #f00;}
.box:hover {opacity: 0.2}
```

<br>
### columns group :
* `.colsgroup`<br>&nbsp;&nbsp;&nbsp;&nbsp;`.column`

example of use:
```sh
<div class="colsgroup">
    <div class="column">
        column 1
    </div>
    <div class="column">
        column 2
    </div>
</div>
```
<br><br>
### table :
* `.table`<br>&nbsp;&nbsp;&nbsp;&nbsp;`.row`<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`.column`

example of use:
```sh
<div class="table">

    <div class="row">
        <div class="column">
            column 1
        </div>
        <div class="column">
            column 2
        </div>
    </div>
    
    <div class="row">
        <div class="column">
            column 1
        </div>
        <div class="column">
            column 2
        </div>
    </div>
    
</div>
```

<br>
Tips
-----------

__rezet__ is standalone, no-dependency. It's for fun & productivity! Of course, it is still need to be improved. So, let me know what's your idea :)

<br>
Contact
--
https://twitter.com/javasdivren<br>
https://www.facebook.com/bagusjavas90
