What is headerMessage:
=========
Pure CSS3, without javascript.
headerMessage is a lightweight CSS library for generating a sliding header panel to show important messages about your website on toggle.

Demo:
=========

http://fpmweb.github.io/headerMessage

![Alt text](/demo/headerMessage.gif?raw=true "headerMessage in action")


How to use it:
=========

Include the headerMessage.css into the head section of your html page.
```html
<link rel="stylesheet" href="css/headerMessage.css">
```

Add your own messages to the header panel.
```html
<div class="headerMessage">
  <h1> hello world!</h1>
  <h2>I'm a hidden message.</h2>
</div>
```
Create a checkbox based button to toggle the header message panel.
```html
<input type="checkbox" name="toggle" id="toggle">
<label for="toggle"></label>
```

Bower installation:
=========

To add a new Bower package to your project you use the install command. This should be passed the name of the package you wish to install.

```js
bower install headerMessage
```

Author:
=========

| [![twitter/fpmweb](https://ca.gravatar.com/gravatars/edit-rating/469cb496a69dd2fad754acea476a53c4)](https://twitter.com/fpmweb "Follow @fpmweb on Twitter") |
|---|


