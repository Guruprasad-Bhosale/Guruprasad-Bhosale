# GP-OS // GitHub Profile Configuration Guide

This repository powers the personal profile for `https://github.com/Guruprasad-Bhosale`.

---

## 1. Directory Structure

```text
├── README.md                           # Main GitHub profile interface
├── SETUP.md                            # Configuration & workflows guide
├── assets/
│   ├── header.svg                      # Moonlit hero scene + OS chrome
│   ├── about_terminal.svg              # ABOUT.MD and TERMINAL.EXE dual consoles
│   ├── tech_inventory.svg              # Categorized equipment & runtime slots
│   ├── projects_banner.svg             # Featured projects section header
│   ├── project_kinddoor.svg            # KindDoor illustrated quest card
│   ├── project_payvia.svg              # PayVia illustrated quest card
│   ├── project_fixmyui.svg             # FixMyUI illustrated quest card
│   ├── project_retrace.svg             # RETRACE illustrated quest card
│   ├── project_signova.svg             # SIGNOVA illustrated quest card
│   ├── project_visionctrl.svg          # VISIONCTRL illustrated quest card
│   ├── stats_header.svg                # Telemetry section header
│   └── taskbar.svg                     # Subordinate retro desktop taskbar
└── .github/
    └── workflows/
        ├── snake.yml                   # Automated contribution snake generator
        └── metrics.yml                 # Profile metrics & isometric calendar generator
```

---

## 2. GitHub Actions Permissions

For automated workflows (`snake.yml` and `metrics.yml`) to commit and publish generated SVGs:

1. Navigate to **Settings → Actions → General** in your profile repository (`Guruprasad-Bhosale/Guruprasad-Bhosale`).
2. Scroll down to **Workflow permissions**.
3. Select **Read and write permissions**.
4. Check **Allow GitHub Actions to create and approve pull requests** (if applicable).
5. Click **Save**.

---

## 3. Contribution Snake Setup

The `snake.yml` workflow runs daily at 18:17 UTC (and on every push to `main`):
- It collects your authentic GitHub contribution graph.
- It styles the snake with dusty teal (`#4BA3A3`) and dots matching your palette (`#151B26`, `#1C2635`, `#202C3D`, `#4BA3A3`, `#F29E85`).
- It automatically pushes `github-contribution-grid-snake.svg` to an orphan `output` branch.
- **Manual Trigger**: Go to **Actions → Generate contribution snake → Run workflow**. Once complete, the snake displays live in the README disclosure panel.

---

## 4. Optional: Metrics Card (`METRICS_TOKEN`)

The `metrics.yml` workflow generates isometric calendars and language metrics:
1. Generate a Personal Access Token (classic) with `repo` and `read:user` scopes at **GitHub Settings → Developer settings → Personal access tokens**.
2. Add it to this repository at **Settings → Secrets and variables → Actions → New repository secret**.
3. Set Name to `METRICS_TOKEN`.
4. Run the workflow manually from **Actions → Generate profile metrics → Run workflow**.

---

## 5. Verified Project Links

The project cards link directly to verified public repositories:
- **KindDoor**: [`https://github.com/Guruprasad-Bhosale/KindDoor`](https://github.com/Guruprasad-Bhosale/KindDoor)
- **PayVia**: [`https://github.com/Guruprasad-Bhosale/PayVia`](https://github.com/Guruprasad-Bhosale/PayVia)
- **FixMyUI**: [`https://github.com/Guruprasad-Bhosale/FixMyCode`](https://github.com/Guruprasad-Bhosale/FixMyCode) *(Repository titled Fix My UI)*
- **RETRACE**: [`https://github.com/Guruprasad-Bhosale/RETRACE`](https://github.com/Guruprasad-Bhosale/RETRACE)
- **SIGNOVA**: [`https://github.com/Guruprasad-Bhosale/SIGNOVA`](https://github.com/Guruprasad-Bhosale/SIGNOVA)
- **VISIONCTRL**: [`https://github.com/Guruprasad-Bhosale/VISIONCTRL`](https://github.com/Guruprasad-Bhosale/VISIONCTRL)
