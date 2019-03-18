# Browser
  Hurry!, Super easy to find your browser and add your logics based on it.
  
## Installation 
  Since it is a jQuery plugin, you need to add **jQuery**. Your code must be followed in below given order.
  
**1. Add jQuery**
```
<script src="..dist/jquery.min.js"></script>
```
**2. Call Back Events**
Call back browser events, which will triggered based on the browser.

```
This is an example for the chrome browser test, version which returns your browser Version
$(document).on("Chrome", function(event, version){
    //Your Script here.
});
```
**3. Browser Detection Plugin**
Add the plugin script at the end of the closing `</body>` tag
```
<script src="..dist/browser-detection.min.js"></script>
```

# Example
| Browser | Code |
| --- | --- |
| Chrome | **Chrome**|;
| OmniWeb | **OmniWeb** |;
| Safari | **Safari**|;
| Opera | **Opera**|;
| iCab | **iCab**|;
| Konqueror | **Konqueror**|;
| Firefox | **Firefox**|;
| Camino | **Camino**|;
| Netscape | **Netscape**|;
| Explorer | **Explorer**|;
