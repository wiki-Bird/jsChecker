# jsChecker

Add the following code to the `<head>` of your HTML site to verify a browser is properly configured to run JavaScript. No bloat, tracking, or ads.

```html
<noscript><meta http-equiv="Refresh" content="3;URL=https://js.ramiels.me"></noscript>
```

Users without JavaScript enabled will be redirected to instructions on how to do so, and returned to their original page upon completion. Users with JavaScript enabled will not be affected.

<br>

_Using a refresh interval of less than 3 seconds is [not recommended](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#attributes)._
