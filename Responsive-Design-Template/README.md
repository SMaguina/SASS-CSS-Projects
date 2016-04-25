###Responsive, Mobile First Design Template

This is a template I've created and continuosly added to for mobile first design best practices. It has become more common for responsive designs to start from a phone-default stylesheet first and expand to creating customized breakpoints for tablets and desktops. This approach allows for more simplicity as designing for mobile-first is a constraint in itself. However, it is a form of progressive enhancement that is well-received and considered to be a modern best practice. Feel free to use it for your own responsive projects made from scratch. It includes the following scripts used for their appropriate results:

**Meta Tag to not have mobile devices misinform on browser viewport size**

`<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">` 

**Script to help old IE (Internet Explorer 8 and under) understand HTML and Media Queries**

`[if lt IE 9]>
	<script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
	<script src="http://css3-mediaqueries-js.googlecode.com/svn/trunk/css3-mediaqueries.js"></script>
<![endif]`

**Prevents iPhone from resizing in landscape mode** *(optional)*

`html {-webkit-text-size-adjust: none; }`

**Apply a natural box layout model to all elements to not have padding overflow occur**

`* {box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box;  }`
