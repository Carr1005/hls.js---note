https://github.com/Carr1005/hls.js---note/blob/6f706bdea6e55987c134c1f3650d6ac055b2fe6f/src/controller/subtitle-track-controller.ts#L344C1-L347C69
```
// setting this.subtitleTrack will trigger internal logic
// if media has not been attached yet, it will fail
// we keep a reference to the default track id
// and we'll set subtitleTrack when onMediaAttached is triggered
```
