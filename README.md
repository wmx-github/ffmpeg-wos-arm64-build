# ffmpeg-wos-arm64-build

Weekly build for ffmpeg windows arm64

Based off :
- https://github.com/BtbN/FFmpeg-Builds/issues/95
- https://trac.ffmpeg.org/wiki/CompilationGuide/Ubuntu

Make build of :

- ffmpeg.exe
- ffprobe.exe
- ffplay.exe

from:
- https://github.com/FFmpeg/FFmpeg 
- https://github.com/libsdl-org/SDL
- https://code.videolan.org/videolan/x264

### auto build ffmpeg:latest
build-ffmpeg-main.yml 
release at releases/tag/main

### auto build ffmpeg:release/6.1
build-ffmpeg-release6.1.yaml
release at releases/tag/v6.1

### use
- 1 Manually trigger the workflow
- 2 Trigger when push 
- 3 All workflow is triggered every Monday at midnight (00:00)
