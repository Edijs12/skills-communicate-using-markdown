# Daily Learning

## Morning Planning
- [x] Paest brokastis
- [x] Neaizmigt
- [x] Nenokavet skolu

<img alt="Tired" src="https://media.istockphoto.com/id/1143952151/photo/sleepy-young-woman.jpg?s=612x612&w=0&k=20&c=1DrqLtW9W74ALu9hwuomyOsnsPmtSOTibU__1BdlaBI=" width="300">

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
