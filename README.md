# 🥚 YolkFan Real-Time Analyzer

An open-source, client-side HTML5/JavaScript application designed for real-time egg yolk color classification (DSM YolkFan™ levels 1–16) and RGB colorimetry analysis using standard webcam or mobile camera feeds.

## ✨ Key Features

* **Real-Time Colorimetry:** Calculates average RGB values from a central focal region in real-time.
* **YolkFan™ Mapping (1–16):** Maps the sampled RGB metrics directly to the nearest official DSM YolkFan™ scale level via Euclidean color distance algorithms.
* **Geometric Focal Shapes:** Custom ROI (Region of Interest) overlays including Circle, Square, Triangle, Pentagon, and Hexagon with dynamic SVG borders.
* **Responsive & Mobile-Ready:** Fully optimized for mobile browsers (iOS Safari / Android Chrome) with camera switching support.
* **Zero Dependencies / No Backend:** Runs entirely in the browser using pure HTML, JavaScript (Canvas API), and Tailwind CSS via CDN.
