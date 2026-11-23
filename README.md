# 🕹️ Web Arcade

A collection of playable, zero-install HTML5 browser games built by **Volcan Studio**, featuring a unified arcade launcher hub (`index.html`), 3D WebGL first-person combat, and ultra-optimized 60 FPS 2D top-down arena action.

---

## 🎮 Included Titles

| Game | Version | Engine / Tech | Genre | Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Cyber Strike 3D](./Cyber%20Strike%203D/index.html)** | `v1.1.0` | Three.js (`r128`), Tailwind CSS, Web Audio | 3D Sci-Fi Arena FPS | 30+ sci-fi weapons, optics & attachments, 3-slot Equipped Armory, 2x headshot crits, Commander Upgrades, and browser-tab LAN rooms. |
| **[Cyber Arena 2D](./Cyber%20Arena%202D/index.html)** | `v1.0.0` | Native HTML5 Canvas (Zero external dependencies) | 2D Circular Bot Battle Royale | 60 FPS auto-lock combat, 4 pre-match starting perks, Boss Waves, Risk Zones, 500-credit bounties, Daily Missions, and permanent Armory upgrades. |

---

## ✨ Key Highlights

* **Unified Arcade Hub (`index.html`):** Launch either title directly from a responsive dark-mode portal page, ideal for GitHub Pages hosting.
* **Self-Contained Architecture:** Each game is packaged as a single standalone HTML file with embedded styles, procedural synth audio, and `localStorage` progression saves.
* **Cross-Platform Controls:** Full support for desktop keyboard/mouse setups as well as mobile touch controls and landscape orientation prompts.

---

## 🎯 Game Breakdown & Controls

### 1. Cyber Strike 3D (`v1.1.0`)
* **Arsenal & Customization:** Choose from 30+ weapons (including *Pulse Assault Rifle*, *Rail Sniper*, *Plasma SMG*, *Blast Launcher*, *Hellfire Minigun*, *Cryo Frost Rifle*, and *Gauss Coilgun*), equip optics (*Iron Sights*, *Red Dot 1.5x*, *Holo 2x*, *ACOG 4x*), and customize weapon/grenade skins.
* **Progression & Modes:** Survive endless waves of rogue synth-bots, earn credits via **2x headshot criticals**, install permanent **Commander Upgrades**, or host/join local browser-tab rooms using shareable room codes (e.g., `CYBER-01`).
* **Key Controls:** `WASD` Move · `Mouse` Aim/Fire · `R` Reload · `G` Grenade · `1–3` Weapon Slots.

### 2. Cyber Arena 2D (`v1.0.0`)
* **Tactical Loadouts & Events:** Select a spawn perk (**+HP**, **Shield**, **Rapid Fire**, or **3X Spread Shot**) before dropping into a circular arena featuring **Boss Waves**, **Risk Zones**, **500-Credit Bounties**, and a live **Top Fighters** leaderboard.
* **Upgrades & Missions:** Complete auto-refreshing **Daily Missions** (*Hunter Shift*, *Boss Breaker*, *Kill Chain*, *Cache Runner*) and spend credits on permanent upgrades (*Titan Armor*, *Flux Reactor*, *Overclock Core*, *Nano Repair*, *Credit Magnet*).
* **Key Controls:**
  * **Desktop:** `WASD` Move · `Shift` Sprint (+65% speed) · `P` / `Esc` Pause · `M` / `N` Toggle Audio/Music · `G` Fullscreen (Auto-lock targeting).
  * **Mobile:** Touch & drag to steer · Hold `SPRINT` button to boost.

---

## 📂 Repository Structure

```text
Web-Arcade/
├── index.html                  # Main Web Arcade hub launcher
├── README.md                   # Repository documentation
├── LICENSE                     # MIT License
├── .gitignore                  # Standard OS/editor ignore rules
├── Cyber Arena 2D/
│   ├── index.html              # Complete 2D bot battle royale game
│   └── CHANGELOG.md            # Patch notes (v1.0.0)
└── Cyber Strike 3D/
    ├── index.html              # Complete 3D sci-fi FPS game
    └── CHANGELOG.md            # Patch notes (v1.1.0)
```

---

## 🚀 Getting Started

### Option 1: GitHub Pages (Recommended for Sharing)
1. Push this repository to GitHub.
2. Go to **Settings → Pages** in your repository.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, select `main` and `/ (root)`, and click **Save**.
4. Your arcade hub will be live at `https://<username>.github.io/Web-Arcade/`.

### Option 2: Run Locally with a Development Server
Running over a local HTTP server ensures smooth asset loading and browser-tab local storage features:

```bash
git clone https://github.com/livemaster4802/Web-Arcade.git
cd Web-Arcade
python -m http.server 8000
```
Open `http://localhost:8000` in your browser to access the Web Arcade hub.

### Option 3: Direct File Launch
Double-click `index.html` in the root folder (or inside `Cyber Arena 2D/` or `Cyber Strike 3D/`) to open it directly in any modern browser. *(Note: Cyber Strike 3D loads Three.js and Tailwind CSS via CDN, so an active internet connection is required for 3D mode.)*

---

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-arcade-game`).
3. Add your new HTML5 game in its own dedicated directory and link it in the root `index.html` launcher.
4. Commit your changes (`git commit -m "Add new HTML5 game"`).
5. Push to your branch and open a Pull Request.

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for details.
