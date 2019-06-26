---
layout: post
title: jQuery Cookie Consent Bar Plugin - cookieMessage.js
subtitle: The cookieMessage.js JQuery plugin lets you create a sticky Cookie Consent Bar on the bottom of the webpage to make your web app comply with the GDPR and European cookie law.
bigimg: https://www.jqueryscript.net/images/cookie-consent-bar-message.jpg
tags: [JavaScript, jQuery]
---

The cookieMessage.js JQuery plugin lets you create a sticky Cookie Consent Bar on the bottom of the webpage to make your web app comply with the European cookie law.
## How to use it:
1. Include the minified version of the cookieMessage.js plugin after loading jQuery JavaScript library.

```html
<script src="https://code.jquery.com/jquery-1.12.4.min.js" 
        integrity="sha384-nvAa0+6Qg9clwYCGGPpDQLVpLNn0fRaROjHqs13t4Ggj3Ez50XnGQqc/r8MhnRDZ" 
        crossorigin="anonymous">
</script>
<script src="dist/jquery.cookieMessage.min.js"></script>
```
2. Initialize the plugin and define the message to inform your users that your site has cookies. That's it.
```Javascript
$.cookieMessage({
  'mainMessage': 'This website uses cookies. By using this website you consent to our use of these cookies. For more information visit our <a href="https://www.exa.com/privacy/">Privacy Policy</a>. '
});
```
## Customize the Accept button.
```html
$.cookieMessage({
  'mainMessage': 'This website uses cookies. By using this website you consent to our use of these cookies. For more information visit our <a href="https://www.googel.com/privacy/">Privacy Policy</a>. ',
  'acceptButton': 'Got It!'
});
```
## Customize the appearance of the Cookie Consent Bar.
```html
$.cookieMessage({
  backgroundColor: '#666',
  fontSize: '14px',
  fontColor: 'white',
  btnBackgroundColor: '#f2a920',
  btnFontSize: '11px',
  btnFontColor: 'white',
  linkFontColor: '#ffff00'
});
```
## Set the cookie name and the time the cookie expires.

```Javascript
$.cookieMessage({
  expirationDays: 20,
  cookieName: 'cookieMessage'
});
```
This awesome jQuery plugin is developed by desarrolladorninja. For more Advanced Usages, please check the demo page or visit the official website.
