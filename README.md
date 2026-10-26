[README.md](https://github.com/user-attachments/files/33956472/README.md)
# English Hub – 1st Batxillerat

A simple website where English students can find all the extra resources for their course, organised by unit. It is one self-contained HTML file: no installation, no build step and no server needed.

## What it includes

- **10 pages in one file:** a Home page and one page for each of the 9 units.
- **Six resource sections per unit:** Vocabulary, Grammar, Listening, Speaking, Reading and Writing.
- **Links and images:** each section can hold links to external activities and infographics that are shown on the page (click an image to enlarge it).
- **Built-in editor for the teacher:** change names, links and images without touching any code.
- **Works on computers, tablets and phones.** It also adapts to light and dark mode.

### Units

| # | Unit |
|---|------|
| 0 | Here & Now |
| 1 | Destinations |
| 2 | Future Solutions |
| 3 | Consumerism |
| 4 | Health & Fitness |
| 5 | Art & Communication |
| 6 | Media & Entertainment |
| 7 | Crime & Punishment |
| 8 | Getting there |

## Repository contents

| File | Purpose |
|------|---------|
| `index.html` | The whole website (page, styles, content and editor). |
| `README.md` | This file. |

## Using the website

**On your computer:** download `index.html` and double-click it. It opens in your browser.

**Online with GitHub Pages:**

1. Upload `index.html` to the root of this repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select your main branch and the `/ (root)` folder, then save.
4. After a minute or two, GitHub shows the public address of the site. Share it with your students.

Each page has its own address, so you can send students straight to a unit by adding `#unit1`, `#unit2`, etc. to the link (and `#home` for the Home page).

## Editing the content (teacher mode)

1. Open the website and click **Teacher mode** (a small, faint link at the bottom of the page).
2. Click **✏️ Edit page**.
3. Edit names, taglines, resource titles and links. Use **+ Add resource** for a new link and **📷 Add image** for an image. Delete anything with the red ✕.
4. Click **💾 Save changes**. Your browser downloads an updated `index.html`.
5. Replace `index.html` in this repository with the downloaded file and commit it. The online site updates after a short wait.

Nothing is saved on the website itself, and students who open Teacher mode only change their own screen.

## Notes

- Images are stored inside `index.html`, so they keep working wherever the file is hosted. Large images are reduced automatically, but many big images will make the file heavier.
- The site loads three fonts from Google Fonts. If they can't load, it falls back to the device's default fonts.
- Links point to resources on other websites (for example test-english.com). Those materials belong to their respective owners and may change or move over time.

## Author

Created by an English teacher for 1st Batxillerat students.
