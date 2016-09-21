EmailTS by VersatilityWerks
=====================
###Email Typo and Suggestion jQuery Plugin

Makes entering your email address faster, and prevents typos!

EmailTS will try to suggest the correct domain while you're typing. You can either click enter or click on the tooltip. If you misspell a common domain like blah@gmail.com as blah@gamil.com, when you leave the field, it'll say "Did you mean blah@gmail.com?". If you click on the suggestion, it'll change the value for you. This is a MUST HAVE to illiminate customer frustration, and to speed up your own typing.

#Demo: <a href='http://flwebsites.biz/emailTS'>flwebsites.biz/emailTS</a>

To Use:
=====
```html
<html>
  <head>
    <link rel="stylesheet" href="dist/emailTS.css"/>
  </head>
  <body>
    <input type='email'>
    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
    <script src='dist/emailTS.min.js'></script>
    <script type="text/javascript">
      $('input[type="email"]').emailTS();
    </script>
  </body>
</html>
```

Options (Defaults):
====
```javascript
	$('input[type="email"]').emailTS({
		tooltip: true,
		typo: true,
		domains: ['yahoo.com', 'ymail.com', 'live.com', 'mail.com', 'comcast.com', 'comcast.net', 'yahoo.co.uk', 'hotmail.co.uk', 'verizon.net', 'sbcglobal.net', 'att.net', 'embarqmail.com', 'aim.com', 'me.com', 'msn.com', 'hotmail.com', 'gmail.com', 'aol.com'],
		addDomains: ['verswerks.com', 'farfromboring.com', 'nomoreagent.com']
	});
	```
