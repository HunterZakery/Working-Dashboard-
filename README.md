# COVID-19 Finals Dashboard - Analytics Visualization

An interactive, responsive single-page web dashboard built for the Part 3 Midterm requirement. This application provides analytics visualization of COVID-19 case records using client-side JavaScript processing. It features fully synchronized Key Performance Indicators (KPIs) and multiple responsive chart types that reflect real-time filter selections.

##  Features

The application satisfies all midterm development requirements completely client-side:

* **3 Distinct Chart Types:**
    * **Bar Chart:** Displays localized distribution across administrative regions.
    * **Line Chart:** Provides timeline tracking showing active progression rates over months.
    * **Pie Chart:** Illustrates aggregate categorical outcomes (`Recovered`, `Active`, `Deaths`).
* **Interactive Control Panel:**
    * **Category Dropdown Filter:** Instant narrowing of analytical queries based on geographical region selection.
    * **Search Input Field:** Dynamic lookups targeting specific patient identifiers (`Patient ID`).
* **Summary Section (3 KPI Cards):**
    * **Total Cases:** Total quantity count matching the active filter constraint.
    * **Average Age:** Live statistical mean age calculation formatted to a single decimal place.
    * **Most Affected Region:** Algorithmic calculation evaluating which location possesses the highest case frequency within the filtered subset.
* **Fully Responsive Layout:** Utilizes a mobile-first Bootstrap grid layout ensuring optimal legibility across varying viewports (mobile, tablet, desktop resolutions).

##  Built With

* **HTML5 & CSS3** - Modern semantic markup structure.
* **Bootstrap v5.3.0** - Responsive layouts and UI card decoration via CDN.
* **Chart.js** - Dynamic Canvas-based rendering engine for data visualization charts via CDN.
* **Vanilla JavaScript (ES6+)** - Pure client-side reactivity, data processing array manipulation, and DOM population without third-party frameworks.

## 📁 File Structure

```text
├── index.html          # Contains the structural layout, CSS styling context, and functional script engine
└── README.md           # Documentation file explaining the implementation details
