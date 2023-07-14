# jsChecker

Add the following code to the `<head>` of your HTML site to verify a browser is properly configured to run JavaScript.

```html
<noscript><meta http-equiv="Refresh" content="3;URL=https://js.ramiels.me"></noscript>
```

Users without JavaScript enabled will be redirected to instructions on how to do so, and will be sent back to the original page once this is completed.
