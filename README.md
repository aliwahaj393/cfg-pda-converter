# CFG / PDA Simulator

A professional, interactive web-based simulator for Context-Free Grammars (CFG) and Pushdown Automata (PDA).

## Features

- **CFG to PDA Conversion**: Visually design your Context-Free Grammars and see them transformed into Pushdown Automata.
- **Interactive Simulation**: Step through the simulation or run it automatically with visual feedback for state transitions, stack operations, and input processing.
- **Neo4j Integration**: Connect to a local or remote Neo4j database to save, load, and manage your PDA states securely.
- **Import / Export**: Easily export your grammars as `.cfg` files and import them later.
- **Modern UI/UX**: Built with a responsive, modern interface featuring a dark and light mode toggle.
- **No Build Required**: Everything is contained in a single HTML file using vanilla JavaScript and CSS.

## Getting Started

Since this project is contained within a single HTML file, getting started is incredibly simple.

1. **Clone the repository:**
   ```bash
   git clone <your-github-repo-url>
   ```
2. **Open the application:**
   Simply open `cfg-pda-tool.html` in your favorite web browser.

## Neo4j Setup (Optional)

If you wish to save your PDAs to a database:
1. Make sure you have a running Neo4j instance (e.g., Neo4j Desktop).
2. Open the "Neo4j Database" panel in the simulator.
3. Enter your connection URI, Username, and Password, then click **Connect**.

## Technologies Used

- HTML5
- CSS3 (Vanilla)
- JavaScript (Vanilla)
- Neo4j JavaScript Driver
