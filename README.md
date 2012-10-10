jquery-ajaxmask
===============

ajaxMask is a super lean (under ~30 lines) jQuery plugin that masks Form content to prevent user interactions and display loading.


Usage
* Inlcude jQuery version required: 1.2 or later.
* Include ajaxmask JS
* Include the ajaxmask CSS


``` html 

  <script type="text/javascript" src="jquery.js"></script>  
  <script type="text/javascript" src="ajaxmask.js"></script>
  <link href="ajaxmask.css" rel="stylesheet" type="text/css"/>

```



``` javascript 

/**
 * start ajax mask
 **/

$(element).ajaxMask();
 

/**
 * stop ajax mask
 **/

$(element).ajaxMask({ stop: true });

```



``` css 

/**
 * example 1 on demo page
 **/

.ajax-mask {
  background: none;
}

.ajax-mask .loading {
  width: 50px;
  height: 50px;
  background: #333 url('../img/loading_mask.gif') center center no-repeat;
  border-radius: 3px;
  -moz-border-radius: 3px;
  -webkit-border-radius: 3px;
  position: relative;
  left:50%;
  margin-left:-25px;
  top:50%;
  margin-top: -25px;
  opacity: 0.9;
  -moz-opacity: 0.9;
}

```
