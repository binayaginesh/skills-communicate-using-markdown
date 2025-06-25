# Daily Learning

## Morning Planning
- Review yesterday’s notes
- Check schedule
- Set priorities

## Review
1. What did I learn?
2. What went well?
3. What can I improve?

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4

