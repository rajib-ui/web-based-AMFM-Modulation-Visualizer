# Web-Based AM/FM Modulation Visualizer (EC401)

An interactive, high-fidelity web dashboard designed for visualizing analog communication schemes. This tool provides real-time time-domain, frequency-domain, and phasor-domain representations of various modulation techniques, built entirely with vanilla HTML5, CSS3, and JavaScript.

👉 **Live Demo:** [https://rajib-ui.github.io/web-based-AMFM-Modulation-Visualizer/](https://rajib-ui.github.io/web-based-AMFM-Modulation-Visualizer/)

---

## ⚡ Key Features

*   **Multi-Scheme Support:** Visualize standard AM (Double Sideband TC), DSB-SC (Suppressed Carrier), SSB-USB (Single Sideband Upper Sideband), FM (Frequency Modulation), and PM (Phase Modulation).
*   **Time-Domain Oscilloscope:** Real-time animated canvas plotting of the message $m(t)$, carrier $c(t)$, and modulated $s(t)$ signals, including dynamic AM envelope boundaries.
*   **Frequency-Domain Spectrum:** A live spectrum analyzer showing carrier and sideband frequencies, complete with hover tooltips for exact frequency and amplitude readouts.
*   **Live Phasor Diagram:** An animated vector display visualizing the carrier, sideband, and net modulated signal phasors rotating in real-time.
*   **Active Formula Rendering:** Displays the textbook governing mathematical equation dynamically matching the selected mode and parameters.
*   **Laboratory Telemetry Dashboard:** Computes real-time transmission metrics:
    *   Carrier Power ($P_c$)
    *   Sideband Power ($P_{sb}$)
    *   Total Power ($P_t$)
    *   Transmission Efficiency ($\eta$)
    *   Carson's Bandwidth ($B$)
*   **Interactive Controls:** Adjust amplitudes, frequencies, modulation index, and channel noise (AWGN) via synchronized sliders and numeric text inputs. Supports mouse wheel scrolling to zoom in/out of the scopes.
*   **Premium Visuals:** Features custom light/dark theme toggles, sleek glassmorphic panel styling, and high-visibility color-coded traces.

---

## 🛠️ Technology Stack

*   **Frontend:** Semantic HTML5, CSS3 (Custom Variables, Flexbox, CSS Grid)
*   **Graphics/Physics Engine:** HTML5 2D Canvas API (High DPI/devicePixelRatio support for crisp rendering)
*   **Fonts:** Google Fonts (Outfit & JetBrains Mono)
*   **Calculations:** Math/Physics solvers implemented in pure client-side JavaScript (including numerical solvers for Bessel approximations).

---

## 🚀 How to Run Locally

Since this project is completely client-side with zero dependencies, you can run it without any local server:

1. Clone the repository:
   ```bash
   git clone https://github.com/rajib-ui/web-based-AMFM-Modulation-Visualizer.git
   ```
2. Navigate to the project folder and open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge):
   ```bash
   cd web-based-AMFM-Modulation-Visualizer
   start index.html
   ```

---

## 📝 Academic Compliance
Designed in compliance with elite laboratory standards for the Course Code **EC401 (Analog Communication Systems)**.
