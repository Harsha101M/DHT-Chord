# DHT-Chord
Interactive visualization of the Chord algorithm for distributed hash tables (DHT). Built with React, it demonstrates how nodes organize and communicate in a P2P network through ring topology and finger tables.

## Features

- Interactive visualization of the Chord ring structure
- Dynamic node addition and removal
- Real-time finger table updates
- Path visualization for key lookups
- Configurable address space size (m-bit identifier)
- Support for multiple active nodes

## Technologies Used

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3

## Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/chord-algorithm-simulation.git
```

2. Navigate to the project directory
```bash
cd chord-algorithm-simulation
```

3. Install dependencies
```bash
npm install
```

4. Start the development server
```bash
npm start
```

The application will open in your default browser at `http://localhost:3000`.

## Usage

1. Enter the number of bits (m) for the address space
2. Input the number of active nodes you want in the network
3. The visualization will show:
   - Active nodes in red
   - Finger tables for each active node
   - Node positions in the Chord ring
4. You can:
   - Search for keys from any active node
   - Add new nodes to the network
   - Remove existing nodes
   - View the path taken to find a key
