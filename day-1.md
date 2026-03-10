# Daily Learning
## Morning Planning
- [ ] check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [Github Pages](https://skills.github.com/#first-dat-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](http://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
