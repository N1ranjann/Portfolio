# Niranjan — Portfolio 2026

A modern, highly polished developer-designer portfolio showcasing production-grade software engineering, security research, and visual craft. 

Live at: [https://portfolio-n1ranjann.vercel.app/](https://portfolio-n1ranjann.vercel.app/) *(or your custom Vercel domain)*

---

## ─── Selected Work

The portfolio contains five deep-dive project case studies, each styled with unique visual identities tailored to their operational domains:

1. **[Feesible](feesible.html)**
   * *Platform & Core Tech:* Flutter, Firebase, Cloud Firestore.
   * *Overview:* A production-ready, secure mobile application built for independent tutors, teachers, and coaches to manage student rosters, track attendance, and monitor outstanding lessons/revenue with precision.

2. **[Mosaic](mosaic.html)**
   * *Platform & Core Tech:* Electron, Flask, Python, Ultra-Wideband (UWB) Telemetry.
   * *Overview:* A privacy-first spatial intelligence and retail analytics engine. Triangulates shopper presence to centimeter-level precision using anonymous active tags, completely bypassing video/facial capture.

3. **[BlackBox](blackbox.html)**
   * *Platform & Core Tech:* Docker, Tailscale, Linux, Immich, CasaOS, AdGuard Home.
   * *Overview:* A high-availability self-hosted homelab server node engineered on legacy hardware, utilizing Tailscale tunnels, container isolation, and DNS-level network ad-blocking.

4. **[Odyn](odyn.html)**
   * *Platform & Core Tech:* CLI Tooling, Rust, Markdown Compilers.
   * *Overview:* An editorial-grade README analyzer and builder designed to automate checklist scoring for open-source repositories, checking for structural readiness, license compliance, and clear documentation.

5. **[Logix](logix.html)**
   * *Platform & Core Tech:* Real-Time Python, Flask, SQLite, Docker, SIGMA rules.
   * *Overview:* A high-density, real-time Security Information and Event Management (SIEM) behavioral detection engine. Correlates event flows to flags alerts and triggers active threat mitigation.

---

## ─── Core Interaction Features

* **Global Lenis Smooth Scroll:** Integrated with fluid scroll velocity and custom momentum animation on all subpages and anchor elements.
* **Horizontal Drag Grid:** The Design Library section translates vertical wheel scrolls and mouse-drag gestures into smooth horizontal sliding.
* **Fluid custom cursor:** Custom vector cursor tracking with scale transformations on interactable anchors and CTA triggers.

---

## ─── Local Development

The project is pure static HTML, CSS, and vanilla JS, making it extremely lightweight and portable.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/N1ranjann/Portfolio.git
   cd Portfolio
   ```

2. **Run a Local Web Server:**
   * **Python 3:**
     ```bash
     python -m http.server 8000
     ```
   * **Node.js (`serve`):**
     ```bash
     npx serve
     ```

3. Open your browser and navigate to `http://localhost:8000/`.

---

## ─── Vercel Deployment

This project includes a `vercel.json` file configured for optimal static site hosting:

```json
{
  "cleanUrls": true
}
```

This ensures that pages resolve with clean URLs (e.g., navigating to `/feesible` correctly loads `feesible.html` without visible file extensions).

### Deploy in Seconds:
1. Push the repository to GitHub.
2. Link your GitHub account to [Vercel](https://vercel.com).
3. Import the project and click **Deploy**. Vercel detects the static files and deploys them instantly with zero extra build commands required.
