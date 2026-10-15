# FairTwitter

Judge posts by what they say, not who said it or how popular they are.

On every post and reply on x.com, FairTwitter:

- **Hides** like, reply, repost, quote, bookmark and view counts. The buttons still work.
- **Hides** the "Who to follow" box, so you pick who to follow from their posts.
- **Blurs** the name, @handle, badge, profile picture and post time.

It is a single CSS file with no JavaScript and no data collection.

## Install

1. Download this folder (or `git clone` it).
2. Load it in your browser:

**Chrome, Brave, Edge, Opera, Vivaldi**
1. Open `chrome://extensions` (Brave: `brave://extensions`, Edge: `edge://extensions`).
2. Turn on **Developer mode**.
3. Click **Load unpacked** and pick this folder.

**Firefox (121+)**
1. Open `about:debugging#/runtime/this-firefox`.
2. Click **Load Temporary Add-on** and pick `manifest.json`.

Firefox removes temporary add-ons when it restarts. To keep it installed, the add-on has to be signed on [addons.mozilla.org](https://addons.mozilla.org/developers/).

**Safari**
Run `xcrun safari-web-extension-converter .` on a Mac and build the Xcode project it creates.

3. Reload x.com.

## Turn it off

Disable it on your browser's extensions page.

## Something still shows?

X sometimes renames its page code. Find the element in your browser's dev tools and fix its selector in `fair.css`.
