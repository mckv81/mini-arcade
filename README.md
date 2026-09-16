# 🕹️ Mind Arcade

An interactive, responsive metacognitive arcade mini-game built entirely mobile-first for web and mobile browsers.

Players step into the cockpit of the Mind Console, learning to intercept runaway emotional and cognitive impulses in real-time through strategic micro-interventions.

---

## 🚀 Play Live

Play directly in your browser:  
👉 **[https://mckv81.github.io/mini-arcade/](https://mckv81.github.io/mini-arcade/)**

---

## 🎮 The Challenge & Mechanics

When high-stress cognitive scenarios strike, the console's **Stability Gauge** begins draining immediately. If it hits zero, the console suffers a cognitive overload.

1. **Observe the Impulse:** Watch the active character's thought loop escalate.
2. **Hit the Brakes:** Tap the emergency brake to pause the cognitive drain and bring in **Echo** to inspect the thought.
3. **Deploy Strategy Orbs:** Choose between raw reactive impulses or calculated counter-tools (Micro-Steps, Cognitive Reframing, Sensory Grounding) to restore console stability and earn points.

---

## 👥 The Characters

* **⚡ Sparks (The Alarmist):** A high-voltage static-ball prone to catastrophic thinking and panic spirals ("If I get this wrong, everything is ruined!"). Countered with structured micro-steps.
* **🌋 Rumble (The Steam-Vent):** A pressurized volcanic bulldog who reacts to frustration and errors with impulsive destruction. Countered with deep breathing and creative reframes.
* **💧 Slump (The Fog-Slug):** An oversized-hoodie creature trapped in cognitive inertia and task paralysis ("I can't start, my brain doesn't work"). Countered with messy "ugly first drafts" and low-friction starters.
* **🦉 Echo (The Observer):** The metacognitive navigator with a glowing monocle lens. When the brakes are engaged, Echo steps into the cockpit to assess thoughts neutrally and evaluate counter-strategies.

---

## 🛠️ How to Run Locally

No installations, build tools, or complex setups required:

1. Clone or download this repository.
2. Ensure the custom character artwork (`sparks.png.PNG`, `rumble.png.PNG`, `slump.png.PNG`, `echo.png.PNG`) resides in the same root folder.
3. Open `index.html` in any modern desktop or mobile browser (Safari, Chrome, Edge, Firefox).

---

## 🧰 Dependencies & Architecture

* **Zero External Dependencies:** Built with pure vanilla HTML5, modern CSS3 animations, and vanilla JavaScript.
* **Zero Audio Files:** Uses the native **Web Audio API** (`OscillatorNode` / `GainNode`) for instant, client-side synthesized 8-bit sound effects.
* **Mobile-Optimized:** Features responsive viewport scaling, touch event handling, and safe-area padding for mobile displays.
