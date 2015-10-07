##jAppbusy
========

This plugin will Show a loading image if application is busy
You can use your image also


```<script src="js/jAppbusy.js"></script>```

###Usage to show
```
var options=
		{
			status:'show',
			top:0,
			left:0,
			image:'',//image path.leave blank for default image
			width:'130px',
			height:'20px',
			zindex:9999
		}
	$(element).jAppbusy(options);	
				
```				
###To hide
```
	$(element).jAppbusy({status:'hide'});	
				
	```			
