# userbottles-photoshop21
Ready to use bottle installation of Photoshop CC 21, allows to run on Linux ( wine 9 )

I assume you have adobe license of course. if you don't, nobody will blame you.

Everything working so far except panels arranging (classic wine bug) and font menu (it works but in a weird way )

Tested on Linux Mint 22, GPU RX580 + Ryzen 3600, esync, svm enabled, no noticeable lag found except following

Known bug list

* When selecting font from the menu, the selection highlight is on wrong line. The actual font selected is one under your cursor.
* Moving panels may cause unstoppable eye-tearing window flicker. DOnt allow panels to undock and make backup (not snapshot!!!) of your installation before moving them.
* Sometimes moving cursor in text window sends the cursor adrift. Use the mouse.
* Login not working due to adobe policy changes
* Process may not close if exit using menu
* If uncheck "Legacy document creation", PS will crash on attempt to make new document

![photo_2024-06-05_00-28-51](https://github.com/juliofawkes/userbottles-photoshop21/assets/37700508/5f89c37f-1400-4ce2-8c78-b2fcb1395e9f)
