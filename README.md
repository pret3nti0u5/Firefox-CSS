# Firefox-CSS
Custom userChrome.css for making your Firefox Browser look better.  
Heavily based on [datguypiko's Firefox-Mod](https://github.com/datguypiko/Firefox-Mod), with customised colors and functionality to fit personal prefrence.

**AutoHiding NavBar**

![alt text](https://j.gifs.com/r8rpP4.gif)  

There's two options available for AutoHiding NavBar:    
(1) Show NavBar on hover, use userChrome.css  
(2) Show NavBar on pressing hotkey (Ctrl + L / Alt + D), use userChrome-hotkey.css [Recommended Option]
 <br></br>
 
**Blurred URL Bar**

![alt text](https://i.imgur.com/kYf5wYt.png)

For Blur to work need about:config 'layout.css.backdrop-filter.enabled' = true
and it could require the 'gfx.webrender.enabled' to true. But if it works with the 'backdrop-filter' leave this one as is.
<br></br>    
Tested on:
```html
 Windows 10 / 77.0.1 / Default Dark Theme
 Manjaro 77.0.1 / Default Dark Theme
```

Dont forget to enable 'toolkit.legacyUserProfileCustomizations.stylesheets' in about:config for your custom themes to work.  
A good tutorial for the same can be found [here](https://www.reddit.com/r/FirefoxCSS/comments/73dvty/tutorial_how_to_create_and_livedebug_userchromecss/).
<br></br>
More detailed documentation and available customizations can be found in [Firefox-Mod Github Page](https://github.com/datguypiko/Firefox-Mod) or in userChrome.css.
