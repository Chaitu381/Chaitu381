# Setup — Chaitu381 GitHub Profile README

This ZIP is designed for your **GitHub profile repository**.

## 1. Create or open the correct repository

The repository must be named exactly:

`Chaitu381`

and it must be **Public** for GitHub to show `README.md` on your profile.

Repository URL:

`https://github.com/Chaitu381/Chaitu381`

## 2. Copy these files into the root

Keep the structure exactly like this:

```text
Chaitu381/
├── README.md
├── assets/
│   ├── hero.png
│   ├── terminal.svg
│   ├── showcase-strip.png
│   └── readme-design-reference.png
└── .github/
    └── workflows/
        └── snake.yml
```

## 3. Push

```bash
git add .
git commit -m "Upgrade GitHub profile README"
git push origin main
```

## 4. Enable the animated contribution snake

Open:

GitHub → `Chaitu381/Chaitu381` → **Actions**

Run **Generate contribution snake** once using **Run workflow**.

The workflow creates an `output` branch. After that, the snake animation in the README will start rendering.

## 5. External services used

The README uses:

- `readme-typing-svg.demolab.com`
- `img.shields.io`
- `skillicons.dev`
- `github-readme-stats.vercel.app`
- `streak-stats.demolab.com`
- `github-readme-activity-graph.vercel.app`
- `komarev.com`

These make the profile dynamic without putting JavaScript into GitHub Markdown.

## 6. Video / showcase

GitHub README does not behave like a normal website and cannot reliably embed a fully interactive custom video player.

The included **Project Showcase** is therefore a clickable visual card that opens:

`https://portfolio.fengari.me`

If you later upload a proper portfolio/demo video to YouTube, replace that link with the YouTube URL.

## Important

The reference image contains illustrative stats such as stars, commits and followers. Those numbers should not be hardcoded because they can become inaccurate. This README uses live GitHub cards/badges instead.

