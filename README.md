* Add to bookmark browser

```js
javascript:(function () { 
    var script =  document.createElement('script');
    script.src="//raw.githubusercontent.com/bombkiml/inspect-mobile/main/inspect-mobile.js"; 
    document.body.appendChild(script);
    script.onload = function () { 
        eruda.init() 
    } 
})();
```
