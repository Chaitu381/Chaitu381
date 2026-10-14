# GitHub Profile README — fixed alignment version

This version fixes the issues you showed:

- CTA buttons are aligned using tables instead of floating inline layouts
- About section chips are split into two rows so nothing overflows
- Featured projects SVG is rebuilt with valid XML and safer text layout
- Contribution section no longer shows a broken image before the workflow runs
- The snake workflow is still included and can be enabled later in Actions

## Folder structure

```text
README.md
assets/
  hero.svg
  about.svg
  projects.svg
  process.svg
  snake-info.svg
  footer.svg
  cta-portfolio.svg
  cta-github.svg
  cta-repositories.svg
  cta-linkedin.svg
  cta-email.svg
.github/
  workflows/
    snake.yml
```

## Install

Replace the files in your `D:\Chaitu381` folder with these files, then run:

```powershell
cd D:\Chaitu381
git add .
git commit -m "Fix GitHub profile alignment and image rendering"
git push origin main
```

## Optional live contribution snake

After pushing, you can enable the live snake later:

GitHub → Chaitu381/Chaitu381 → Actions → Generate contribution snake → Run workflow
