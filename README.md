# OxygenSafe

**Oxygen concentrator safety training: an interactive 3D and scenario-based simulation.**

▶ **Live course:** https://sinonabdoulaziz717-a11y.github.io/oxygensafe/

OxygenSafe lets ward staff explore a 3D oxygen concentrator and practise the safety decisions that matter when the device warns them or fails: setting and checking the prescribed flow, spotting unsafe bedside set-ups, reading warning lights, restoring oxygen first and taking a faulty device out of service.

- **Four stages:** Explore (optional) · Practice · Respond · Results
- **Bilingual:** English and French
- **Clinically validated** by three medical doctors and a nurse
- **Accessible:** keyboard support, screen-reader feedback, reduced motion, and a flat-drawing alternative to the 3D model

Designed and developed with AI as a development partner, mainly Claude and ChatGPT. 3D model created with Tripo AI and displayed with Three.js.

## How it's built

OxygenSafe is deliberately a single, self-contained page (`index.html`), so it loads fast, works on any static host and is easy to share; only the 3D model files sit separately in `models/`. Inside the page, the visual design is driven by shared colour and type tokens, and most course content (parts, warnings, scenarios and checklists) is kept in separate English and French data blocks. For a future version or new language, the next step would be to split the design, content and code into their own files.

> Training simulation of a generic device. Always follow the manufacturer's manual, your facility's protocol and the prescription.
