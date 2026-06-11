# AlgoVision - Interactive Algorithm Visualizer

<div align="center">

![AlgoVision](https://img.shields.io/badge/AlgoVision-v1.0-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Master computer science algorithms through interactive, real-time visualizations**

[View Demo](#) • [Report Bug](#) • [Request Feature](#) • [View Algorithms](#algorithms-implemented)

</div>

---

## 📚 Project Overview

AlgoVision is a production-ready, educational web platform that visualizes complex algorithms through engaging, real-time animations. Built with vanilla JavaScript, HTML5, and CSS3, it provides an immersive learning experience for students, developers, and algorithm enthusiasts.

The application features a modern dark theme with glassmorphism design, responsive layouts, and comprehensive educational content for each algorithm.

### ✨ Key Highlights

- 🎯 **11+ Algorithms** covering sorting, searching, graph traversal, and pathfinding
- 🎨 **Real-Time Animations** with customizable speed and step-by-step execution
- 📊 **Performance Metrics** showing comparisons, swaps, and execution time
- 📱 **Fully Responsive** design works seamlessly on all devices
- 🌙 **Dark/Light Mode** toggle for comfortable viewing
- 📚 **Educational Content** with pseudocode and complexity analysis
- ⚡ **Zero Dependencies** pure vanilla JavaScript, HTML, and CSS
- 🔧 **Interactive Controls** pause, resume, and step through algorithms

---

## 🚀 Features

### 1. **Sorting Algorithms** (5 implementations)
- Bubble Sort - Classic O(n²) algorithm
- Selection Sort - Simple selection-based approach
- Insertion Sort - Efficient for small datasets
- Merge Sort - Divide-and-conquer O(n log n)
- Quick Sort - Optimized partitioning algorithm

**Sorting Visualizer Includes:**
- Real-time bar animation with color coding
- Comparison and swap counters
- Adjustable array size (10-200 elements)
- Speed control for animations
- Complexity analysis display
- Algorithm descriptions and pseudocode

### 2. **Search Algorithms** (2 implementations)
- Linear Search - Sequential element search
- Binary Search - Logarithmic search on sorted arrays

**Searching Visualizer Includes:**
- Interactive array generation
- Target value input
- Step-by-step visualization
- Current index tracking
- Time complexity display
- Algorithm explanations

### 3. **Graph Algorithms** (2 implementations)
- Breadth-First Search (BFS)
- Depth-First Search (DFS)

**Graph Visualizer Includes:**
- Interactive graph builder
- Add/remove nodes and edges
- Node dragging and repositioning
- Traversal order display
- Queue/Stack visualization
- Real-time node coloring

### 4. **Pathfinding Algorithms** (2 implementations)
- Dijkstra's Algorithm
- A* Algorithm

**Pathfinding Visualizer Includes:**
- Interactive grid system
- Wall drawing capability
- Start and end node placement
- Visited nodes visualization
- Final path highlighting
- Performance metrics

### 5. **Additional Features**
- Dark/Light Mode Toggle
- Speed Control Slider
- Step-by-Step Execution
- Auto Play Capability
- Pause and Resume Controls
- Educational Explanation Panels
- Comparison Mode (in development)
- Responsive Mobile Design

---

## 📊 Algorithms Implemented

### Complexity Table

| Algorithm | Best Case | Average Case | Worst Case | Space | Stable |
|-----------|-----------|--------------|-----------|-------|--------|
| Bubble Sort | O(n) | O(n²) | O(n²) | O(1) | ✓ |
| Selection Sort | O(n²) | O(n²) | O(n²) | O(1) | ✗ |
| Insertion Sort | O(n) | O(n²) | O(n²) | O(1) | ✓ |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) | ✓ |
| Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) | ✗ |
| Linear Search | O(1) | O(n/2) | O(n) | O(1) | - |
| Binary Search | O(1) | O(log n) | O(log n) | O(1) | - |
| BFS | O(V+E) | O(V+E) | O(V+E) | O(V) | - |
| DFS | O(V+E) | O(V+E) | O(V+E) | O(V) | - |
| Dijkstra | O(E log V) | O(E log V) | O(E log V) | O(V) | - |
| A* | O(E log V) | O(E log V) | O(b^d) | O(V) | - |

---

## 🎨 Design Features

### Modern Aesthetic
- **Glassmorphism** UI with backdrop blur effects
- **Gradient Accents** throughout the interface
- **Dark Theme** with custom CSS variables
- **Smooth Animations** and transitions
- **Professional Typography** with semantic sizing
- **Color-Coded Visualizations** for algorithm states

### Color Scheme
- **Primary**: #00d4ff (Cyan/Blue)
- **Secondary**: #ff006e (Pink/Red)
- **Accent**: #8338ec (Purple)
- **Success**: #3a86ff (Bright Blue)
- **Warning**: #fb5607 (Orange)
- **Danger**: #ff006e (Red)

### Responsive Breakpoints
- Desktop: 1400px max width
- Tablet: Optimized for 768px and below
- Mobile: Full-width responsive layout

---

## 📁 Project Structure

```
AlgoVision/
│
├── index.html                 # Main HTML file
├── style.css                  # Comprehensive styling
├── script.js                  # Main application logic
│
├── algorithms/
│   ├── bubbleSort.js          # Bubble Sort implementation
│   ├── selectionSort.js       # Selection Sort implementation
│   ├── insertionSort.js       # Insertion Sort implementation
│   ├── mergeSort.js           # Merge Sort implementation
│   ├── quickSort.js           # Quick Sort implementation
│   ├── linearSearch.js        # Linear Search implementation
│   ├── binarySearch.js        # Binary Search implementation
│   ├── bfs.js                 # BFS implementation
│   ├── dfs.js                 # DFS implementation
│   ├── dijkstra.js            # Dijkstra's Algorithm implementation
│   └── astar.js               # A* Algorithm implementation
│
└── README.md                  # Project documentation
```

---

## 🔧 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Local Setup

1. **Clone the repository**
```bash
git clone https://github.com/Nandana-28/AlgoVision.git
cd AlgoVision
```

2. **Open in browser**
   - Double-click `index.html` or
   - Right-click → Open with → Browser

3. **Optional: Use a local server**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server)
npx http-server
```

4. **Visit**
   - Open browser and navigate to `http://localhost:8000`

---

## 💻 Usage Guide

### Navigation
- Use the top navigation bar to switch between different algorithm visualizers
- Each section contains controls for the specific algorithm category

### Sorting Visualizer
1. Select an algorithm from the dropdown
2. Adjust array size (10-200 elements)
3. Set animation speed
4. Click "Generate New Array" to create random data
5. Click "Start" to begin visualization
6. Use "Pause"/"Resume" to control playback
7. View metrics: comparisons, swaps, execution time
8. Check complexity analysis panel for Big O notation

### Search Visualizer
1. Choose Linear or Binary Search
2. Generate an array
3. Enter target value to search
4. Click "Search" to start
5. Watch real-time index tracking
6. View total steps and complexity

### Graph Visualizer
1. Click "Add Node" to create nodes
2. Select two nodes (they will highlight)
3. Click "Connect Nodes" to create edges
4. Choose BFS or DFS algorithm
5. Click "Start" to run traversal
6. Observe traversal order and visited count

### Pathfinding Visualizer
1. Select grid size
2. Choose drawing mode: Walls, Start, or End
3. Click on grid to place elements
4. Select Dijkstra or A* algorithm
5. Click "Find Path" to visualize
6. See visited nodes and final path

### Theme Toggle
- Click the moon/sun icon in the top-right to switch between dark and light modes
- Setting persists in browser local storage

---

## 🎓 Educational Content

Each algorithm includes:

### Definition
Clear explanation of what the algorithm does

### How It Works
Step-by-step breakdown of the algorithm logic

### Applications
Real-world use cases and where it's commonly used

### Advantages
Strengths and benefits of the algorithm

### Disadvantages
Limitations and potential drawbacks

### Complexity Analysis
Big O notation for time and space complexity

### Pseudocode
Algorithmic representation for reference

---

## 🔍 Sorting Algorithm Details

### Bubble Sort
- **Use Case**: Educational purposes, nearly sorted data
- **Pros**: Simple to understand and implement
- **Cons**: Poor performance on large datasets
- **Best For**: Beginners learning algorithm concepts

### Selection Sort
- **Use Case**: Minimal memory writes required
- **Pros**: Guaranteed O(n²) comparisons
- **Cons**: Never faster than O(n²)
- **Best For**: Situations with expensive write operations

### Insertion Sort
- **Use Case**: Small arrays, nearly sorted data
- **Pros**: Efficient for small or partially sorted data
- **Cons**: O(n²) for large unsorted data
- **Best For**: Online sorting, small datasets

### Merge Sort
- **Use Case**: Large datasets, stable sort required
- **Pros**: Guaranteed O(n log n), stable
- **Cons**: Requires O(n) extra space
- **Best For**: Large datasets, linked lists

### Quick Sort
- **Use Case**: General-purpose sorting
- **Pros**: Average O(n log n), in-place sorting
- **Cons**: Worst-case O(n²), unstable
- **Best For**: General-purpose sorting

---

## 🔍 Search Algorithm Details

### Linear Search
- **Time**: O(n)
- **Use Case**: Unsorted data, small datasets
- **Advantage**: Works on unsorted data
- **Disadvantage**: Slow for large datasets

### Binary Search
- **Time**: O(log n)
- **Use Case**: Large sorted datasets
- **Advantage**: Very fast on sorted data
- **Disadvantage**: Requires sorted data

---

## 🗺️ Graph Algorithm Details

### BFS (Breadth-First Search)
- **Time**: O(V + E)
- **Space**: O(V)
- **Use**: Shortest path in unweighted graphs
- **Applications**: Level order traversal, shortest path

### DFS (Depth-First Search)
- **Time**: O(V + E)
- **Space**: O(V)
- **Use**: Connected components, topological sorting
- **Applications**: Backtracking, cycle detection

---

## 🗺️ Pathfinding Algorithm Details

### Dijkstra's Algorithm
- **Time**: O((V + E) log V)
- **Space**: O(V)
- **Use**: Shortest path with non-negative weights
- **Greedy**: Always picks minimum distance node

### A* Algorithm
- **Time**: O((V + E) log V)
- **Space**: O(V)
- **Use**: Pathfinding with heuristic guidance
- **Advantage**: Faster than Dijkstra with good heuristic
- **Heuristic**: Manhattan distance for grid

---

## 📈 Performance Metrics Explained

### Comparisons
Number of times elements are compared during algorithm execution

### Swaps
Number of times elements are swapped/moved

### Execution Time
Real elapsed time in milliseconds

### Steps
Number of iterations or operations performed

### Visited Nodes
Count of nodes explored in graph/pathfinding

### Path Length
Number of nodes in the final shortest path

---

## 🎨 Customization

### Modify Colors
Edit CSS custom properties in `style.css`:
```css
:root {
    --primary-color: #00d4ff;
    --secondary-color: #ff006e;
    --accent-color: #8338ec;
    /* ... more colors ... */
}
```

### Adjust Animation Speed
Slider in each visualizer section (10-500ms)

### Change Grid Size
Pathfinding grid size slider (10-50)

### Modify Array Size
Sorting array size slider (10-200)

---

## 🐛 Browser Compatibility

- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile Browsers

---

## 📝 Code Quality

### Standards
- Clean, modular JavaScript
- Semantic HTML5
- Modern CSS3 with custom properties
- Comments and documentation
- Responsive design best practices

### Best Practices
- Separation of concerns
- Async/await for animations
- Event delegation
- CSS Grid and Flexbox layouts
- No external dependencies

---

## 🚀 Future Improvements

- [ ] Comparison mode (side-by-side algorithm comparison)
- [ ] More sorting algorithms (Shell Sort, Heap Sort, Radix Sort)
- [ ] More graph algorithms (Prim's, Kruskal's, Floyd-Warshall)
- [ ] Algorithm complexity calculator
- [ ] Performance benchmarking
- [ ] Export visualization as video
- [ ] Collaborative features
- [ ] Algorithm difficulty levels
- [ ] Code snippets in multiple languages
- [ ] Advanced heuristics for A*

---

## 📊 Statistics

- **Total Algorithms**: 11
- **Lines of Code**: 3000+
- **CSS Classes**: 100+
- **Animation Frames**: Real-time with Canvas
- **Responsive Breakpoints**: 2
- **Browser Support**: 4+ major browsers

---

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Contribution
- Additional algorithms
- UI/UX improvements
- Performance optimizations
- Documentation enhancements
- Mobile responsiveness
- Accessibility features
- Bug fixes

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

---

## 👨‍💻 Author

**Nandana**
- GitHub: [@Nandana-28](https://github.com/Nandana-28)

---

## 🙏 Acknowledgments

- Algorithm visualizations inspired by VisuAlgo
- Design inspiration from modern UI frameworks
- Community feedback and contributions
- Computer Science educators and researchers


---

## 🎯 Learning Resources

### Recommended Reading
- "Introduction to Algorithms" by Cormen, Leiserson, Rivest, Stein
- "Algorithm Design Manual" by Steven S. Skiena
- Online: GeeksforGeeks, LeetCode, HackerRank

### Practice Platforms
- LeetCode (Coding practice)
- HackerRank (Algorithm challenges)
- CodeSignal (Interview preparation)
- GeeksforGeeks (Tutorials)

---





<div align="center">

### Made with ❤️ for Computer Science Learners


</div>
