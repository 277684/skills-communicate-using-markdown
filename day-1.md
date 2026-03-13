# Daily Learning
- Item 1
- Item 2
- Item 3
+ Item1.1
+ Item 2.1
* Item 1.3
* Item 2.3
## Morning Planning
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
1. Step 1
1. Step 2
1. Step 3
## Review
- [x] This task is complete
- [ ] This task is not complete
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
