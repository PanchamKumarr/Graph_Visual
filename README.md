# Graph Visualizer

A pathfinding visualizer that demonstrates various graph traversal and pathfinding algorithms. [Live Demo](https://graphvisual-green.vercel.app/)

## Features

- **Pathfinding Algorithms**

  - Dijkstra's Algorithm (weighted)
  - A\* Search (weighted)
  - Greedy Best First Search (weighted)
  - Swarm Optimization (weighted)
  - Breadth First Search (unweighted)
  - Depth First Search (unweighted)

- **Maze Generation**

  - Random Maze
  - Vertical Skew
  - Horizontal Skew
  - Weighted Maze
  - Stair Pattern

- **Interactive Features**
  - Add/Remove Walls
  - Add Weights
  - Add Bombs
  - Adjust Visualization Speed
  - Clear Board/Walls/Path

## Local Development Setup

1. Clone the repository:

```bash
git clone https://github.com/PanchamKumarr/Graph_Visual.git
cd Graph_Visual
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

4. Open your browser and visit:

```
http://localhost:3000
```

## Development

For development with auto-reload:

```bash
npm run dev
```

## Project Structure

- `public/` - Contains all static assets and JavaScript files
  - `browser/` - Main application JavaScript files
  - `styling/` - CSS and image assets
- `server.js` - Express server configuration
- `index.html` - Main application entry point
- `vercel.json` - Vercel deployment configuration

## Deployment

The project is deployed on Vercel and can be accessed at:
https://graphvisual-green.vercel.app/

## Technologies Used

- Frontend:

  - HTML5
  - CSS3
  - JavaScript
  - Bootstrap 3.3.7
  - jQuery 3.1.1

- Backend:
  - Node.js
  - Express.js

## License

ISC
