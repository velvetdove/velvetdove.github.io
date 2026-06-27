# velvetdove.github.io

The developer website for **LuckyFlop** — a one-person studio making small, honest
mobile apps for Arabic, Persian, and Turkish speakers. Maker of **Receipt Lens**.

Once deployed it is live at **https://velvetdove.github.io** — use that URL as the
**Developer website** in Google Play Console.

## Deploy (GitHub Pages)

1. Create a **public** repo named exactly **`velvetdove.github.io`**.
2. Upload these files to the repo root: `index.html`, `style.css`, `clover.png`, `banner.jpg`.
3. Repo **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save**.
4. Wait ~1 minute, then open **https://velvetdove.github.io** to confirm.
5. In **Google Play Console → your app → Store settings** (Store listing contact details),
   paste `https://velvetdove.github.io` into **Website**.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The page |
| `style.css`  | Styles — brand palette indigo `#4F46E5` → emerald `#10B981`, four-leaf-clover motif |
| `clover.png` | Logo + favicon (512×512) |
| `banner.jpg` | Social / profile banner (4096×2304) |

## Editing

- **Studio name:** search `LuckyFlop` in `index.html` to rename.
- **Apps:** duplicate the `<article class="app">` block to add another app.
- **Contact:** the email `luckyflopbtt@gmail.com` and `github.com/velvetdove` appear in the
  Contact section and footer.

No build step, no dependencies — plain HTML/CSS with two fonts from Google Fonts.
