# Dose Defenders — Dose Defender

> Tower defense where radiation particles advance on a patient. Place shielding towers to deflect dose. Each wave represents a treatment fraction — balance protection with therapeutic delivery.

**Demo:** [https://georgezero.github.io/vibe-hackathon-alpha-team-05-dose-defender](https://georgezero.github.io/vibe-hackathon-alpha-team-05-dose-defender)
**Hackathon:** Vibe Hackathon 2025 · Team 05
**License:** MIT

## Team

- **Jamie Wilson** — Solo Developer

## Installation

```bash
npm install
```

## Run

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

Or open `index.html` directly — no build step required for the base game.

## Build for Production

```bash
npm run build
```

Output goes to `dist/`.

## How to Play

Click to place shields — stop radiation particles from reaching the patient.

## Architecture

See [docs/architecture.md](docs/architecture.md) for full design notes.

## Agent Development Notes

See [AGENTS.md](AGENTS.md) for instructions on working with this repo using AI coding agents.

See [docs/prompts.md](docs/prompts.md) for the key prompts used during development.

## Known Limitations

Only 5 wave types implemented. Pathfinding is fixed-route, not dynamic.

## Sample Data

See [sample-data/](sample-data/) for example game states and test fixtures.
