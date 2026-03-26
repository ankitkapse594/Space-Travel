# Aetheris Interplanetary

Welcome to the official web application for **Aetheris Interplanetary**, a premier 2026-era space travel agency dedicated to onboarding Martian Pioneers and Lunar Tourists.

## Features

- **Mission Control (Home):**
  - **Live Telemetry Ticker:** Displays real-world context on March 2026 SpaceX and NASA schedules.
  - **Hero Carousel:** A high-fidelity image carousel built using `framer-motion` to seamlessly smoothly pan through destinations.
  - **Launch Window Timer:** A real-time countdown to the late 2026 Mars Transfer Window.
- **Astronaut Onboarding:**
  - A futuristic, responsive 3-step application flow for new recruits.
  - Integration with `react-signature-canvas` for digitally signing the Astra-Lex Code of Conduct.
  - **Session Persistence:** Application data saved to browser Local Storage.
- **Trainee Dashboard:**
  - **G-Force Simulation:** A dynamic progress bar calculating G-Force acclimation.
  - **Flight Surgeon AI:** An interactive simulated terminal chat interface capable of rendering complex Hohmann Transfer trajectory calculations.

## Technology Stack
- **Framework:** Next.js 16 (App Router)
- **Styling:** Tailwind CSS (v4) with custom `void-black` (#020617) & `martian-dust` (#922b21) themes and advanced glassmorphism utility classes.
- **Animations:** Framer Motion
- **Icons:** Lucide-React
- **State Management:** React Hooks & LocalStorage

## Getting Started

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Run the Development Server**
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) with your browser to launch the mission.

## Visual Aesthetics
This project enforces an intense "Interstellar" feel. Custom `--background` and `--foreground` CSS variables alongside `@utility glass` ensure the deepest blacks and highly crisp, frosted glass UI components. Typography is balanced using Next.js Google Fonts (`Inter` and `Orbitron`).
