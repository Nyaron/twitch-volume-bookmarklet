# Twitch Volume Bookmarklet
A bookmarklet to toggle the volume of the Twitch player without muting it
## How to install
Make a new bookmark in your browser (right-click on the bookmarks bar and select `Add page...`)
- Choose the name you want, I named mine "Twitch Lurk"
- Copy the code block below and paste it into the "URL" of the new bookmark
```javascript
javascript:(function(){const t=document.body.querySelector(".video-player video");t.volume = t.volume<1?1:0.01;})();
```
## How to Use
When watching your favourite streamer, just click on the bookmarklet and it will set the volume to 1% unless it's already at 1%, then it will set it back to 100%.

## Why
While Twitch stated that they can detect organic views even when you mute a stream ([Source](https://twitter.com/TwitchSupport/status/1184540919447601153)), I was actually concerned about it not supporting the streamers I watch.

## Licence
Licensed under the [MIT License](http://choosealicense.com/licenses/mit/)
