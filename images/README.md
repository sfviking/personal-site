# Hero photos

Drop a JPG (or WebP — just update the extension in `css/style.css`) here using the
filename below, and it will replace the Unsplash placeholder for that hero.
If a file is missing, the Unsplash fallback shows automatically — the site never breaks.

| Hero | Filename | Used on |
|---|---|---|
| Home | `home.jpg` | `index.html` |
| Travel hub | `travel.jpg` | `travel/index.html` |
| Pacifica | `pacifica.jpg` | `travel/pacifica.html` |
| San Francisco | `san-francisco.jpg` | `travel/san-francisco.html` |
| Norway | `norway.jpg` | `travel/norway.html` |
| About | `about.jpg` | `about.html` |
| Notes | `notes.jpg` | `notes.html` |

## Recommended export settings

- **Width:** 1600–2000px
- **Format:** JPEG quality ~80, or WebP
- **Target file size:** under 300 KB (the gradient overlay forgives a lot)
- **Composition:** subject in the upper third — title text sits at the bottom of the hero

## Adjusting focal point

Each hero has a `background-position` in `css/style.css` (e.g. `center 40%`).
Tweak the second value if your photo's subject is too high or low.
