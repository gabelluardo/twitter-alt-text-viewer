# Twitter Alt-Text Viewer

A set of custom CSS rules to make alt-text visible on Twitter's desktop web interface.

## Features

### Clear indicators for whether an image has alt-text or not:
![Screenshot showing a tweet with two images. One has a blue border and a blue icon in the corner saying "✓ ALT", the other has a red border and a red icon in the corner saying "✕ ALT".](docs/screenshot-icons.png)

### Visible alt-text on mouse-over:
![Screenshot showing a tweet with one image. The mouse cursor is hovering over the image, and the alt-text for the image is displayed in an overlay.](docs/screenshot-overlay.png)

## Installation

### Step 1: Install a browser extension to inject custom CSS

There are several available, but I'm personally partial to [Stylus](https://github.com/openstyles/stylus) (Chrome/Firefox/Opera) and [UserScripts](https://apps.apple.com/us/app/userscripts/id1463298887) (Safari).

There's also the popular **Stylish**, but there are [compelling reasons against using it](https://robertheaton.com/2018/08/16/stylish-is-back-and-you-still-shouldnt-use-it/) — Stylus was created as a safer alternative after that fiasco.

### Step 2: Install the custom CSS

#### Using Stylus

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/lunasorcery/twitter-alt-text-viewer/main/twitter-alt-text-viewer.user.css)

With Stylus installed, click the above button, and the extension will open a new tab prompting you to add the style.

![](docs/stylus-add.png)

Then, click the "Install style" button on the left, and you're all set!

#### Using UserScripts (Safari)

![](docs/userscripts-safari-open.png)

Click the UserScripts icon in the window bar, and press "Open" to launch its settings panel.

![](docs/userscripts-safari-add.png)

Click the "+" button, then "New Remote". When prompted for a URL, paste in the following:

```
https://raw.githubusercontent.com/lunasorcery/twitter-alt-text-viewer/main/twitter-alt-text-viewer.user.css
```

The extension will import the style, but _make sure to hit the "Save" button in the bottom-right of the screen_.