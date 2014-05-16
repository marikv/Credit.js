Credit.js
=========

A simple jQuery plugin for creating awesome credit card inputs.

How to use?

```
<!-- Include credit css file -->
<link rel="stylesheet" type="text/css" href="credit.css" />
<!-- Credit card input -->
<input type="text" name="credit_card_number" class="credit" />
// Include jquery
<script type="text/javascript" src="jquery.min.js"></script>
// Include credit.js
<script type="text/javascript" src="credit.js"></script>
<script type="text/javascript">
	jQuery(function ( $ ){
		// Do it!
		$(".credit").credit();
	});
</script>
```

Credit automatically focus on the credit card input, if you don't want this to happen simply set the `auto_select` to false.

```
$(".credit").credit({ auto_select: false });
```


![alt tag](http://s22.postimg.org/8ivlrnopd/credit_js.png)
