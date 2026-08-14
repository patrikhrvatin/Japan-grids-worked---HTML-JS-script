Evo kratkog i jasnog uputstva za `README.md` datoteku vašeg projekta:

---

## Japan WAJA & Grid Progress Map

Interactive web application for amateur radio operators to track their **WAJA (Worked All Japan Prefectures)** and grid field progress directly in the browser using an ADIF log and a local GeoJSON map file.

### Features

* **100% Client-Side:** All log and map data are processed securely locally in your browser. No data is uploaded to external servers.
* **Dual View Modes:**
* **WAJA (Prefectures) View:** Tracks progress across all 47 Japanese prefectures.
* **Grid Fields View:** Visualizes worked Maidenhead grid squares over Japan.


* **Band Filtering:** Filter progress and statistics instantly by individual bands (`160m` to `6m`) or view the `TOTAL` summary.
* **Detailed Tooltips:** Hover over any prefecture or grid square to see detailed QSO statistics, worked callsigns, and counts.

### Usage

1. Open the HTML file in any modern web browser.
2. Select your ADIF log file (e.g., `lotwreport.adi` or your station log).
3. Select your local GeoJSON file containing Japanese prefectures boundaries (`japan.geojson`).
4. Explore your progress using the interactive map and band buttons, or toggle between Prefecture and Grid views.
