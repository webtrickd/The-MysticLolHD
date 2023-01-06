# Console Rickroll

You can paste this code into a website's console to open the rickroll:

```
window.open(window.atob(window.atob("YUhSMGNITTZMeTkzWldKMGNtbGphMlF1WjJsMGFIVmlMbWx2TDFSb1pTMU5lWE4wYVdOTWIyeElSQT09")), "go nuts");
```

Some other websites might support adding the player without redirecting:

```
var body = document.querySelector("body");
var iframe = document.createElement("iframe");
iframe.src = "https://www.youtube.com/embed/dQw4w9WgXcQ";
iframe.style.position = "absolute";
iframe.style.top = "0";
iframe.style.left = "0";
iframe.style.width = "100%";
iframe.style.height = "100%";
body.appendChild(iframe);

```


### WebTrickd
