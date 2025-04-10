# Integrated Documentary (iDoc)
### Intended for public use

An opensouce project to implement an integrated documentary format into a single library for public use

Inspired by Apollo in Real Time by Ben Feist, It's time to open up for more 

![til](./apollo1.gif)

![img](https://apolloinrealtime.org/11/img/help_callouts.jpg)

[Apollo 13 Github Repo](https://github.com/bfeist/Apollo_13.git)

---

Youtube API

```
function onYouTubeIframeAPIReady() {
    trace("INIT: onYouTubeIframeAPIReady():creating player object");
    player = new YT.Player('player', {
        videoId: 'KfRygQcR5uk',
        width: '100%',
        height: '100%',
        playerVars: {
            frameborder: 0,
            iv_load_policy: 3,
            modestbranding: 1,
            autohide: 1,
            rel: 0,
            'controls': 0,
            fs: 0,
            playsinline: 1
        },
        events: {
            'onReady': onPlayerReady,
            'onStateChange': onPlayerStateChange
        }
    });
    // player.setPlaybackQuality('hd1080');
}
```
