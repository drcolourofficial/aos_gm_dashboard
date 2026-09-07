# GM Campaign & Skirmish Manager

A standalone desktop application built for Game Masters to track continental milestones, fortify critical locations, manage asymmetrical war campaigns, and fight modular skirmishes.

## Features
- **Interactive Skirmish Board:** Drag-and-drop checkpoints, custom map fortifications, and tactical point deployment.
- **Continental & Military Milestones:** Complete progress and advancement tech trees that scale national power points.
- **War Room & Casus Belli Engine:** Automated tug-of-war tracking with dynamic victory thresholds based on war goals.
- **Auto-Update System:** Automatically checks for remote repository updates on launch.

---

## Installation & Setup 

1. Download the latest `.msi` or setup installer from the [Releases Page]
2. Run the installer to place the app on your desktop.
3. **Connecting to the World Data:** 
   - Open the app and navigate to the **⚙ Settings** tab.
   - Paste your official GM Repository path (e.g., `drcolourofficial/aos_gm_dashboard`).
   - Click **⬇ Pull from Server** on the Dashboard to sync the latest global milestones and map changes.

---

## For Game Masters (Pushing Updates)
1. Go to the **⚙ Settings** tab in the app.
2. Configure your repository path, target file (`master_data.json`), and paste your GitHub **Personal Access Token (PAT)** with `repo` scopes (you need to get this from Colour).
3. Click **⬆ Push to Repo** on the Dashboard to save your campaign's global state online.
