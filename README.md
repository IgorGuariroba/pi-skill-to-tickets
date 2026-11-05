# pi-skill-to-tickets

[![Pi Package](https://img.shields.io/badge/pi--package-skill-blue)](https://github.com/IgorGuariroba/pi-skill-to-tickets)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**to-tickets** skill for the **[Pi coding agent](https://pi.dev)**, adapted from Matt Pocock's Engineering Skills.

> Break a plan, spec, or the current conversation into a set of tracer-bullet tickets, each declaring its blocking edges, published to the configured tracker (edges as text in one file per ticket locally, or native blocking links on a real tracker).

---

## Installation

Install directly into Pi using `pi install`:

```bash
pi install git:github.com/IgorGuariroba/pi-skill-to-tickets
```

Or clone into your local/global skills directory:

```bash
# Global Pi skills directory:
git clone https://github.com/IgorGuariroba/pi-skill-to-tickets.git ~/.pi/agent/skills/to-tickets

# Or Agent Skills standard path:
git clone https://github.com/IgorGuariroba/pi-skill-to-tickets.git ~/.agents/skills/to-tickets
```

---

## Usage

Trigger it explicitly in your session:

```text
/skill:to-tickets
```

Or let Pi automatically route to it based on conversation context and need.

---

## Credits

- **Original concept & methodology**: [Matt Pocock](https://github.com/mattpocock)
- **Adapted for Pi Agent**: [Igor Guariroba](https://github.com/IgorGuariroba)

---

## License

[MIT](LICENSE)
