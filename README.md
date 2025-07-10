🧩 Maze Generator
A dynamic maze generation web app using
HTML, CSS, and JavaScript — featuring multiple famous maze generation algorithms like Recursive Backtracking (DFS), Prim’s, Kruskal’s, Eller's, and Aldous-Broder.


🌐 Live Demo
[Maze Generator](https://maze-generator-6sot.vercel.app)


🚀 Features
🧱 Customizable Maze Size and Grid Dimensions
🔄 Realtime Maze Animation for each algorithm
🟩 Highlighted goal cell
🎨 Clean UI with responsive design
📱 Works on both desktop and mobile
🧠 5 Algorithms Implemented


Algorithm	Description
1) Recursive Backtracking	Depth-First Search based maze carving with backtracking.
2) Prim’s Algorithm	Randomized Prim’s for uniform spanning tree generation.
3) Kruskal’s Algorithm	Union-Find based approach to form a minimum spanning tree.
4) Eller's Algorithm	Row-by-row generation, ideal for infinite mazes.
5) Aldous-Broder	Random walk with uniform spanning guarantee.


🛠️ Tech Stack
HTML5
CSS3
Vanilla JavaScript (ES6+)
Canvas API
Vercel for deployment


📦 Setup & Run Locally
git clone https://github.com/sayamgrover1310/maze-generator.git
cd maze-generator
Then open index.html directly in a browser or launch with Live Server in VS Code.


🧑‍💻 How to Use
Choose your maze size and number of rows/columns
Click on an algorithm (e.g., "Recursive Backtracking")
Watch it generate in real-time 
Use arrow keys to navigate the maze to the green goal cell


📁 Project Structure
maze-generator/
├── index.html      # Main HTML structure
├── style.css       # Styling & layout
├── maze.js         # All algorithm logic and rendering
└── settings.js     # UI logic and event handling


📌 Todo / Future Enhancements
Add BFS/DFS pathfinding after maze generation
Include timer to track solving time
Mobile touch controls
Maze solver animation
