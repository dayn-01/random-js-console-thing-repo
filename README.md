# Repo for js things i do

## google_play_total_used/g_play_total_used_by_game.js
- Getting google playstore total moolah used

### Usage
 
- go to https://play.google.com/store/account/orderhistory
- make sure all orders are loaded.
- make sure to check the comments and update them.
- run the script on the dev console

### Usage for g_play_total_used_by_game.js
same with the first one but:

on the code, you can see the target__
ex:

```
let target__ = 'https://play-lh.googleusercontent.com/x8aGPOteVSHRBaRKJnfJI4sq95rL9Xo8yj37Q0mMROdQUPPvz9Y63QiEXehhbfFS6T3y=s50';
```
it needs to be 
```
let target__ = '<game img src link here>';
```
and you get the `img src` by doing ctrl + shift + c, clicking the image, and then copy pasting the `img src link`

img: picking the img

![image](https://github.com/dayn-01/random-js-console-thing-repo/assets/34685779/cd19101d-2f84-4dd5-9596-aa98b10784d0)

img: location of the img src link

![image](https://github.com/dayn-01/random-js-console-thing-repo/assets/34685779/6ad705c5-cac1-4270-8a15-6351778d1dc0)


## save_bookmarks/unread_bookmarks (outdated)

### Usage

- go to https://manganelo.com/bookmark or https://mangakakalot.com/bookmark
- run the script on the console
---
- It will create a text file of your bookmark list and the same list will be shown on the console
- a modified version of [this](https://greasyfork.org/en/scripts/390432-mananelo-mangakakalot-bookmarks-export/code) script 
