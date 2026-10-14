# GHOST//PROTOCOL — install guide

This folder is a ready-to-upload starter for `https://github.com/Guruprasad-Bhosale/Guruprasad-Bhosale`.

## 1. Upload the files

In the profile repository, replace `README.md` and add these paths:

- `assets/night-banner.png`
- `.github/workflows/snake.yml`
- `.github/workflows/metrics.yml`

Keep the paths and filename capitalization exactly as shown.

## 2. Enable Actions permissions

Open **Settings → Actions → General** in the profile repository. Under workflow permissions, allow the `GITHUB_TOKEN` to have read and write permissions. Save the setting.

## 3. Generate the animated contribution snake

Open **Actions → Generate contribution snake → Run workflow**. After it succeeds, the workflow publishes an `output` branch. The snake image in README should then resolve from that branch; scheduled refreshes run daily.

## 4. Generate the Metrics card (optional but recommended)

Create a GitHub personal access token for reading your profile data. Follow the current `lowlighter/metrics` documentation and use the least privileges needed for the plugins you keep. Add it to your profile repository under **Settings → Secrets and variables → Actions → New repository secret** with the exact name `METRICS_TOKEN`.

Then open **Actions → Generate profile metrics → Run workflow**. The workflow commits `metrics.svg` to `main`, which the README displays. The Metrics workflow will fail until `METRICS_TOKEN` is configured.

## 5. Check the project links

The links are set to the public repositories currently associated with this profile: `RETRACE`, `FixMyCode` (the repository README calls the project Fix My UI), `SIGNOVA`, `KindDoor`, `PayVia`, and `VISIONCTRL`.

## Notes

- GitHub README Markdown does not allow arbitrary CSS, so the palette is expressed through the custom banner, custom-colored widgets, badges, and generated SVGs rather than styling the whole GitHub page.
- GitHub stats, typing SVG, Skill Icons, and the generated graphics depend on external services or GitHub Actions. They may take a little time to appear after the first push.
- No metrics are hard-coded; the cards are generated from your actual public GitHub activity and repositories.
