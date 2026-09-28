### ⚡ Neon Clash 3.0

A feature-rich, high-performance 2D fighting game and sandbox platform built entirely for the web. **Neon Clash 3.0** combines responsive fighter mechanics with a modular web-based ecosystem, featuring peer-to-peer networking, visual creators, a progression economy, and procedural elements. 

👉 **[PLAY NEON CLASH 3.0 LIVE HERE!](/goto?url=CAESYwHrOzAVFPs7JfsCil5-tBePYLL0da_y4aEfLJ8urYgRWY1l-qb96ukEK1U_AIFotSIUWyjfTcBEJEhMx9STIPetebx36vUrTvOmtgnDKB64SNMMUJ--xrBuiAl1SZRfOPp3QA)** 

### 🕹️ Controls & Battle Core

* **Movement:** A / D (Move), W / Space (Jump), S (Drop down platforms)
* **Combat:** J (Attack), K (Special Move), L (Dash), E (Parry/Guard), U (Ultimate)
* **Strategy:** Q (Tag Team Partner Swap), I (Accessory), O (Companion)
* **Developer Tools:** H toggles live **Hitbox/Hurtbox rendering visualization** in real-time.
* **Photo Mode:** P opens high-fidelity screen rendering filters (Neon Noir, Cyberpunk, Sepia, etc.).

### 🚀 Advanced Architecture & Technical Features

### 🌐 1. Real-Time Online Multiplayer (MQTT Networking)

* Powered by lightweight, low-latency messaging over neon-clash/public-lobbies.
* Broadcasts public rooms dynamically allowing up to 8 players to browse, join, or host live lobbies.
* Supports active slot handling, combining human players and scaling AI bot difficulties concurrently.

### 🗺️ 2. In-Browser Creative Sandboxes

* **Interactive Map Editor:** Full visual grid coordinate designer supporting drag-and-drop platform creation, dynamic snapping (20px), canvas sky gradient mapping, and interactive hazard triggers (e.g., lava fields). Includes string-based layout sharing via map code translation.
* **Procedural Skin Editor:** Complete dynamic look customizer utilizing canvas composite coloring. Includes body style overrides (Chibi, Ooze, Spectre, Mecha) and sprite sheet rendering logic.

### ⚖️ 3. Web Storage Game Economy & Progression

* **The Command Center Hub:** Organizes system state, historical data logging (Last 20 matches tracking), global settings configuration, and state persistence with local file import/export hooks.
* **Simulated Marketplace Ecosystem:** Fully integrated local data model tracking dual-currency values (Coins vs. Premium Tokens), functional Auction House listing structures (escrow engine with reserve values), and a Skinner Fusion engine.
* **Roguelike Run Mechanics ("The Neon Ascent"):** Stage progression state tracking that stacks floor rewards, character perks, and dynamic character upgrading loops.

### 🛠️ Tech Stack

* **Engine Core:** Vanilla JavaScript (ES6+ Architecture) / HTML5 Canvas API
* **Networking Layer:** MQTT Broker client messaging protocols
* **Data Management:** LocalStorage API web persistence layers
* **Styles & Filters:** Dynamic CSS Variables, CSS Canvas-Filter matrices, and responsive structural layouts

### ⚙️ Running Locally

1. Clone this repository: 

bash

git clone https://github.com/maximum131114/neon-clash.git



2. Navigate into the folder and launch a local web server (such as VS Code's *Live Server* or python's http.server): 

bash

python3 -m http.server 8080



3. Open http://localhost:8080 in your web browser.
