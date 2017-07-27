# Google Analytics Fullscreen Javascript Bookmarklet
A small javascript bookmarklet that shows Google Analytics in fullscreen in your browser, without the header and side menu bars. It's a quick way to showcase analytics on a big screen.

## How to install and run the bookmarklet ##
This is example was tested on Google Chrome Version 59.0 but is supposed to work on other browsers as the way to add a bookmarklet is quite consistent accross browser vendors.

Simply copy & paste the below javascript code and create a new bookmark in your browser.

```javascript
javascript:var div=document.getElementById("ID-headerBar");if(div)div=div.style;if(div)void(div.display=div.display=="none"?"block":"none");var div=document.getElementById("ID-gafe4Nav");if(div)div=div.style;if(div)void(div.display=div.display=="none"?"block":"none");
```

In Google Chrome you can start by bookmarking this page:
1. Click on the star in the address bar to bookmark this page.
2. Copy & paste the javascript bookmarklet above.
3. Click on the menu item *Bookmarks* and select *Bookmark Manager*.
4. Hover over the bookmark that you have just created and click the triangle on the right.
5. Choose *Edit...* from the menu and change the title of the bookmark.
6. Next paste the bookmarklet with `CTRL+V` (Windows) or `CMD+V` (OSX) in the field next to title.
7. Hit enter and that's it!

Now fire up Google Analytics and choose the bookmark that you have edited to run the javascript code.

## Credits and Contributors ##
* Original code from the wiki at: [WebviewScreenSaver](https://github.com/liquidx/webviewscreensaver/wiki/Using-WebviewScreenSaver-to-show-full-screen-Google-Analytics)
* Code maintained by: [Francis Laclé](http://visualacuity.nl), blog [visualacuity.nl](http://visualacuity.nl)
