# CogniDiff UI/UX Frontend

Frontend interface for CogniDiff — privacy-preserving cognitive monitoring and early screening platform.

## Features
- Interactive 3D Three.js neural brain animation and dynamic starfield background.
- Responsive dashboard with longitudinal cognitive trend charts and latency metrics.
- Cognitive task assessments (reaction time, keystroke dynamics, pattern memory).
- Doctor & clinician report review portal.
- Authentication pages (patient & doctor roles).

## Project Structure
- `index.html`: Landing page featuring 3D neural brain HUD.
- `assets/`: Styling (`neural.css`, `app.css`, `landing.css`) and client scripts (`neural-brain.js`, `starfield.js`, `charts.js`, `api.js`).
- `pages/`:
  - `login.html`: Patient & doctor portal authentication.
  - `dashboard.html`: Longitudinal score charts, session telemetry, and privacy audit logs.
  - `tasks.html`: Interactive cognitive micro-assessments.
  - `doctor.html`: Clinical longitudinal review and diagnostic notes.
- `vendor/`: Local dependencies (Three.js, GSAP, ScrollTrigger, Chart.js) and typography fonts.

## Running Locally
Run with any static file server:
```bash
python -m http.server 3000
```
Then navigate to:
```
http://localhost:3000
```
