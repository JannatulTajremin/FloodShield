# 🌊 FloodShield
### Flood-Aware Emergency Rescue Route and Resource Planning System

FloodShield is a C++ graph algorithms project that simulates emergency rescue route planning during flood situations.

The system represents locations as vertices and roads as weighted edges. It uses graph algorithms to explore reachable locations, find alternative routes, and build a minimum spanning network.

**Note:** This is an educational simulation. It does not use live flood data, GPS, or real-time maps.

## 🚀 Features

- Interactive representation of 7 locations and 9 roads.
- BFS for finding routes with the minimum number of road segments.
- DFS for exploring reachable locations.
- Dijkstra for finding shortest-distance routes.
- Kruskal for building a Minimum Spanning Tree (MST).
- Manual road status control (OPEN/BLOCKED).
- Detection of unreachable destinations.

## 🧠 Algorithms Used

| Algorithm | Purpose |
|---|---|
| BFS | Minimum number of road segments |
| DFS | Explore reachable locations |
| Dijkstra | Shortest-distance route |
| Kruskal | Minimum Spanning Tree |

## 🛠️ Technologies Used

- C++
- Standard Template Library (STL)
- HTML, CSS and JavaScript (GUI prototype)
- Code::Blocks

## 📊 Sample Results

- Dijkstra shortest distance (Rescue Center to Hospital): **10**
- BFS route: **2 road segments**
- Kruskal MST total weight: **15**
- Disconnected destination: **No available route!**

All distances are sample values for educational demonstration.

## 📁 Project Structure

```text
FloodShield/
├── README.md
├── .gitignore
├── src/
│   └── floodshield.cpp
├── gui/
│   └── floodshield-gui.html
├── docs/
│   ├── Project_Report.pdf
│   └── Presentation.pdf
├── diagrams/
└── screenshots/
```

## ▶️ How to Run

### C++ Console Application

1. Open `src/floodshield.cpp` in Code::Blocks or another C++ IDE.
2. Compile the source code.
3. Run the program.
4. Select an algorithm from the menu.

### Interactive GUI Prototype

1. Open `gui/floodshield-gui.html` in a web browser.
2. Select a start and destination.
3. Run the desired algorithm.
4. Toggle road statuses to test different scenarios.

**Note:** The HTML/JavaScript GUI is a separate prototype and is not connected to the C++ console application.

## ⚠️ Limitations

- Uses predefined locations and sample road distances.
- Road conditions are updated manually.
- No live flood information or GPS integration.
- Not intended for real-world emergency navigation.

## 🔮 Future Improvements

- Integration of real-time flood and road information.
- Interactive geographical maps.
- Connection between the GUI and C++ backend.
- Rescue resource prioritization.

## 👩‍💻 Author

**Jannatul Tajremin**  
Department of Computer Science and Engineering  
University of Asia Pacific (UAP)

## 📌 Disclaimer

This project was developed for academic and educational purposes to demonstrate graph algorithms.
