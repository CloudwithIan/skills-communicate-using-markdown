# Daily Learning

## Morning Planning
- [ ] Check out the [github blob](https://github.blob/) for topic ideas.
- [ ] Learn about [Github Pages](https://skills.github.com/#first-day-on-github)
- [ ] Convert my first blog post into an actual webage.

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=constrast=1.2:saturation=1.1" output.mp4
```
