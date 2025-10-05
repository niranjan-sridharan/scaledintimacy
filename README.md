# scaledintimacy
scaledintimacymock
# 🌐 Scaled Intimacy Simulation

An agent-based model exploring how social networks maintain intimacy at scale through presence capacity, reciprocity, vulnerability, and memory dynamics.

## Overview

This simulation models how agents form and maintain meaningful connections within overlapping social pods, navigating the tensions between:
- **Presence capacity** limits (how many connections we can actively maintain)
- **Reciprocity** expectations (interaction loops that need closing)
- **Vulnerability** thresholds (trust-based disclosure)
- **Memory decay** (how relationships fade without reinforcement)

## Features

### Interactive Web Visualization
- Real-time network visualization with force-directed physics
- Adjustable parameters (agent count, pod size, pulse cycles)
- Live metrics tracking (SII, presence density, reciprocity index, memory retention)
- Quiet/loud phase alternation showing interaction rhythm effects

### Python Implementation (Mesa Framework)
- Full agent-based model using Mesa, NetworkX, and NumPy
- Overlapping pod structure (simulating friend groups, communities)
- Exponential memory trace decay
- Reciprocity loop tracking
- Trust cascades and breach events
- Systemic Intimacy Index (SII) composite metric

## Quick Start

### Web Version
1. Clone this repo
2. Open `index.html` in a browser
3. Adjust parameters and click "Start Simulation"

### Python Version
```bash
# Install dependencies
pip install mesa networkx numpy matplotlib

# Run simulation
python scaled_intimacy_simulation.py
```

## Key Metrics

- **SII (Systemic Intimacy Index)**: Overall system health composite
- **PD (Presence Density)**: Average meaningful ties per agent
- **RI (Reciprocity Index)**: Fraction of completed interaction loops
- **VH (Variability Homeostasis)**: Novelty vs. destabilization balance
- **VS (Vulnerability Safety)**: Safe disclosure rate
- **MR (Memory Retention)**: Average trace strength
- **RB (Rhythm Balance)**: Quiet-to-loud phase ratio quality

## Model Parameters

| Parameter | Default | Description |
|-----------|---------|-------------|
| N | 100 | Number of agents |
| PC | 7 | Presence capacity (max active ties) |
| RR | 4 | Reciprocity radius |
| VT | 0.5 | Vulnerability threshold |
| MD | 20 | Memory decay constant |
| Q | 10 | Quiet phase duration (cycles) |
| L | 4 | Loud phase duration (cycles) |

## Use Cases

- Exploring optimal social network architecture
- Understanding why communities fragment at certain scales
- Modeling attention economy effects on relationships
- Testing interventions for maintaining social cohesion
- Studying pulse/rhythm effects in social dynamics

## Embedding in Substack/Blog

The web visualization is designed to embed cleanly in blogs:
1. Host `index.html` on GitHub Pages, Netlify, or similar
2. Embed the URL using an iframe or embed block
3. Fully responsive and mobile-friendly

## Theory Background

This model implements concepts from:
- Dunbar's number and cognitive load limits
- Social exchange theory (reciprocity)
- Trust dynamics and vulnerability
- Attention economy
- Temporal patterns in social interaction

## License

MIT License - feel free to adapt and extend!

## Contributing

Contributions welcome! Areas for exploration:
- Alternative pod formation algorithms
- Different memory decay functions
- Network topology experiments
- Additional intervention strategies
- Performance optimizations for larger scales

## Citation

If you use this simulation in research or writing, please link back to this repository.

---

*Built with Mesa (Python) and vanilla JavaScript (Web version)*
