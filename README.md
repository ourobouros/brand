# Glovo brand

![Glovo](https://github.com/Glovo/brand/blob/master/images/glovo.png)

Glovo brand resources for developers


## Your Glovo Address
First and most important thing is to know your **GLOVO_ADDRESS**.  
Just browse our website ([https://glovoapp.com](https://glovoapp.com)) and find your store. What you see in your browser
address bar is your glovo address.

> exmaple of glovo address:
> https://glovoapp.com/web/bcn/wok-to-walk

### Customer location
We support extra query params in the url. The params supported are
- _delivery_address_lat, delivery_address_lng_: Latitude & longitude of the delivery address
- _delivery_address_details_ : Details of the address such as "Door, Floor, ..."

So you can create an url like
> https://glovoapp.com/web/bcn/wok-to-walk?delivery_address_lat=41.395572&delivery_address_lng=2.189737&delivery_address_details=planta1


## Widget

![Glovo Widget](https://github.com/Glovo/brand/blob/master/images/widget.png)

If you want to add a widget of your glovo shop in your website
you just need to add this simple widget:

```
<div id="glovoLink" style="margin:10px auto;width:100%">
	<a href="YOUR_GLOVO_ADDRES?focus=true" target="_blank" >
    <img src="https://glovoapp.com/assets-cdn/images/logo_togo.svg" style="width:100%" alt="Buy with Glovo"/>
	</a>
</div>
```


View a [demo](http://codepen.io/glovo/pen/rjzBbJ) or check the examples folder

**[Remember]** you can add parameters to the address. See the _**Customer Section**_ just above.

## iFrame

Adding an iframe with your shop is also very easy:

```
<iframe id="glovo"
	name="glovo"
	title="glovo"
	width="100%"
	height="600px"
	frameborder="0"
	marginheight="0"
	marginwidth="0"
	src="YOUR_GLOVO_ADDRESS">
</iframe>
```

View a [demo](http://codepen.io/glovo/pen/pRrzMw) or check the examples folder
