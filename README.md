# real-time-video-streaming

## Theory
### RTP

### RTSP

### WebRTC

### USB/IP


## Open Source Tools

### aiortc

- ``aiortc`` is a python package that supports webRTC APIs outside the browser.
- The datachannel-cli, videostream-cli and webcam examples are the examples one may want to go through to understand the how to write your webRTC based own examples.
- Important Classes defined in aiortc: MediaTreamTrack, MediaPlayer, MediaRecorder, RelayStreamTrack ...

**Note:**

- In the original webRTC implementation (javascript code) webcams were accessed via the browser and video streams were displayed on the browser. In ``aiortc`` the av python package is used to convert between webRTC video frames and opencv video frames. Accessing webcam video streams, processing them, displaying them etc. can be done using opencv. The need for browser is eliminated.

### FFMPEG

### Gstreamer

### MediaMTX


# References:

1) AV package - https://pyav.org/docs/develop/api/video.html
2) USB/IP - https://developer.ridgerun.com/wiki/index.php?title=How_to_setup_and_use_USB/IP
