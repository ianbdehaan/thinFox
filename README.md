# thinFox

## Keyboard centered thin layout firefox css

For people that, like me, prefer the workspace without a lot of visual polution from menus.
I personally navigate mostly with vimium extension and a few normal keyboard shortcuts from firefox,
but you only need to know that ctrl+L focus on the address bar.

Based on https://github.com/lr-tech/OnelineProton/

## How to Install:

If you've done this before just copy the userChrome.css file to your chrome directory, no extra bullshit.

For people that never did this before:

1. In you firefox searchbar, type about:config, accept the risk.
2. Search for **'toolkit.legacyUserProfileCustomizations.stylesheets'** and change it to **True**.
3. Go to your Firefox profile:
   - In the searchbar, type `about:support` and press `Enter`.
   - Search for **`Profile Directory`** and click on **`Open Directory`** button.
4. Create a folder and name it **`chrome`** (with lowercase).
5. Paste userChrome.css file into the folder.
6. Restart Firefox
7. Enjoy your new Firefox!

## Customization:
Unfortunately in the way I implemented most of the customization breaks the layout unless you know what you are doing,
if I realize there is interest around customizing this layout I might put some time into making this more accessible.

## Known bugs:
1. Dragging tabs around leads to them being cut in half while this is being done.
2. Opening a new tab makes the search bar half focused, it's neither completely open nor invisible.

If someone knows how to fix one of these please let me know.

## Extra remarks:
1. There are no borders or curved edged in the firefox layout, they belong to my hyperland configuration.
2. The layout is not purple, I use **Firefox Color** for the colors to match my system
3. This was not a big project, and I used a lot of code from other people, but if you like the design an would like to donate anyways: https://buymeacoffee.com/ianbdehaan
