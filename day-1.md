# Daily Learning

## Morning Planning
- [x] Paest brokastis
- [x] Neaizmigt
- [x] Nenokavet skolu

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
