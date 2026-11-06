# Jun Wang · Personal Homepage

Source of my academic homepage, served by GitHub Pages at **https://jun25336-bit.github.io/**.

I am an M.S. student in Electrical and Computer Engineering at the University of Michigan, working on embodied AI safety, foundation models for robotics, and autonomous driving.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site: one static page with inline CSS. No build step, no dependencies. |
| `teaser.mp4` | 7-second muted loop shown next to the TouchSafeBench paper, cut from the opening of the [paper video](https://jun25336-bit.github.io/TouchSafeBench/). |
| `teaser.jpg` | Still frame of that clip, shown before the video plays and for visitors who prefer reduced motion. |

## Updating the site

Edit `index.html`, then commit and push to `main`. GitHub Pages redeploys in about a minute.

To preview locally:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Common edits:

- **News**: add an `<li>` to the `<ul class="news">` list, newest first.
- **Publication**: copy an existing `<div class="paper-box">` block and change the title, authors, links, badge, and teaser.
- **Profile photo**: add `photo.jpg` to the repo and change `<div class="avatar">JW</div>` to `<div class="avatar"><img src="photo.jpg" alt="Jun Wang"></div>`.

## Related

- TouchSafeBench project page: https://jun25336-bit.github.io/TouchSafeBench/
- TouchSafeBench code: https://github.com/jun25336-bit/TouchSafeBench

## Credits

Layout adapted from [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io).
