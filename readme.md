# FontScout - Find your Font (chrome extension)


<p><img src="./public/icons/FyF.png" alt="FontScout logo" width="100" height="100"></p>

Struggling to choose the right font for your website? I built FontScout to make it easier. With this Chrome extension, you can quickly test different Google fonts directly on your site and pick the one that fits best

![FontScout demo](./docs/demo/Fontscout.gif)

## Download

Download the extension from [Chrome Extension store]

or

You can download the dist folder from releases and load it manually



## Features of FontScout
✅ Test 1000+ google fonts <br>
✅ Move the modal around the webpage. <br>
✅ Upload your local font and test it <br>
✅ Set italics, underline, weights, line height etc. <br>
✅ Set font size and color<br>



---

## Current limitations
* If the FontScout doesn't open even after double click on a website, please file an issue



### Contributing

The `manifest.json` required for extension is located inside the public folder.

To load the extension locally. Go to extension -> Load unpacked -> point to dist folder (the build folder).

For development use
```
npm run build:dev
```
This is because the extension requires to point to the build folder, using this command you
won't have to rebuild on every save.
