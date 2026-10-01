# Setup — Muhammed Massab GitHub Profile README

This package is made for the GitHub profile repository:

`khanking0316120/khanking0316120`

## Put these files in the repository root

- `README.md`
- `assets/hero.svg`
- `assets/profile-scan.svg`
- `assets/footer-wave.svg`
- `.github/workflows/snake.yml`

## Important

The animated profile scanner tries to load your current GitHub avatar from:

`https://github.com/khanking0316120.png?size=260`

If GitHub ever blocks nested external images inside the SVG, replace the `<image href="...">`
inside `assets/profile-scan.svg` with a local file such as `./profile.png`, then add that image
to the `assets` folder.

## Contribution snake

After you push the files:

1. Open your profile repository on GitHub.
2. Go to **Actions**.
3. Open **Generate contribution snake**.
4. Click **Run workflow** once.
5. The workflow creates an `output` branch.
6. The README will then show the animated snake automatically.

## Push commands

```bash
git add README.md assets .github
git commit -m "Upgrade GitHub profile README"
git push origin main
```
