TensegrityTrajectoryToolkit

A tiny prototype web app to normalize per-module pose time-series and replay them.

Usage:
- Open index.html in a browser.
- Paste CSV or JSON into the input box, or upload a file.
- Click "Parse & Normalize". The app will try common CSV layouts (columns per module or rows per frame with module fields).
- Use Play / Step controls to preview frames.
- Export normalized CSV or compact JSON via Export buttons.

Limitations: This is a front-end prototype with heuristic parsing. Complex or novel formats may need small adaptations.

No external dependencies. All code is in index.html.