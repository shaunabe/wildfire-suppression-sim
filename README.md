# Wildfire Suppression Simulator

Interactive comparison of four wildfire suppression strategies — Firedome, drone swarms, air tankers, and ground crews — across different site profiles, weather conditions, and seasonal leasing arrangements.

**Live demo:** https://shaunabe.github.io/wildfire-suppression-sim/

## What it models

- **Four asset types** with realistic physical parameters (payload, cycle time, wind ceilings, range)
- **Three site profiles**: residential community, wine farm, ski resort — same structure count, very different geometry
- **Wind ceilings**: aircraft and drones are grounded above 30 mph; Firedome and ground crews keep working
- **Seasonal leasing** with 2–3 positioning options per asset (on-site / regional / truck-mounted)
- **Cost stack**: per-season lease + per-deployment sortie + incident damages

## Built with

React 18, Recharts 2, Babel standalone (in-browser JSX). Single-file HTML, no build step. Hosted on GitHub Pages.

## License

Proprietary — Third Sphere
