

# bookmarklets
Useful Bookmarklets

Add them as a new Bookmark in your Browser, just like an URL. For Example:

Darker/Redder:

javascript: (function () {     var FilterOnTopDiv = document.createElement('div');     FilterOnTopDiv.setAttribute('style','width: 100%;                      height:100%;                      z-index:99999;                      position:fixed;                      left:0px;                      top:0px;                      background-color:#620; opacity: 0.25; pointer-events:none;'); document.body.appendChild(FilterOnTopDiv);}());

Works just like entering javascript in the Console Drawer of the Browser:

```
var darker = () => {
  var FilterOnTopDiv = document.createElement('div');
  FilterOnTopDiv.setAttribute('style','width: 100%; height:100%; z-index:99999; position:fixed; left:0px; top:0px; background-color:#620; opacity: 0.25; pointer-events:none;');
  document.body.appendChild(FilterOnTopDiv);
};
```
