🏭 Smart Warehouse System
Design and Analysis of Algorithms (DAA) Mini Project
A Smart Warehouse Management System that demonstrates the practical application of Design and Analysis of Algorithms concepts using Fractional Knapsack and Dijkstra’s Algorithm.
This project visually simulates optimal product placement and shortest path navigation inside warehouses.
📌 Project Overview
Modern warehouses need to:
Store products optimally based on capacity
Maximize value under limited space
Quickly locate products using the shortest path
This project solves these problems using core DAA algorithms, presented through an interactive web-based visualization.
🎯 Objectives
Apply Fractional Knapsack Algorithm for optimal space utilization
Apply Dijkstra’s Algorithm for shortest path navigation
Visually demonstrate algorithm execution
Help students understand DAA concepts through real-world simulation
🧠 Algorithms Used
1️⃣ Fractional Knapsack (Greedy Algorithm)
Used to optimally place products into racks
Products are sorted based on Value/Weight ratio
Supports partial placement of products when rack capacity is limited
Time Complexity:
Sorting: O(n log n)
Placement: O(n)
2️⃣ Dijkstra’s Algorithm (Shortest Path)
Used to find the shortest path from warehouse entrance to the rack
Warehouse is modeled as a weighted graph
Time Complexity:
O(V²) (array-based implementation)
🏗️ System Architecture
Warehouses
Alpha Warehouse
Beta Warehouse
Gamma Warehouse
Delta Warehouse
Each warehouse contains:
Multiple racks (Small, Medium, Large capacity)
A graph structure for navigation
Product Attributes
Product Name
Company
Weight
Value
Value/Weight Ratio
Warehouse Assigned
Rack Number
Fraction Placed
⚙️ Features
✅ Random product generation
✅ Live Fractional Knapsack placement animation
✅ Rack capacity visualization
✅ Product search functionality
✅ Shortest path display using Dijkstra’s algorithm
✅ Interactive and responsive UI
✅ Real-time logs for algorithm steps
🖥️ Technologies Used
HTML5
CSS3
JavaScript (Vanilla JS)
Google Fonts (Inter)
No external libraries or frameworks used.
🚀 How to Run the Project
Clone the repository:
git clone https://github.com/your-username/smart-warehouse-system.git
Navigate to the project folder:
cd smart-warehouse-system
Open index.html in any modern web browser:
Chrome / Edge / Firefox
No server or installation required.
🧪 How It Works
Enter the number of products to generate
Products are assigned randomly to warehouses
Fractional Knapsack Algorithm optimally places products into racks
Use the search bar to find a product
Dijkstra’s Algorithm displays the shortest path from entrance to rack
📊 Sample Use Cases
Demonstrating Greedy Algorithms
Demonstrating Graph Algorithms
College mini-project / DAA lab submission
Algorithm visualization for learning
📂 Project Structure
📁 Smart-Warehouse-System
 ├── index.html
 ├── README.md
📚 Academic Relevance
This project aligns with:
Design and Analysis of Algorithms
Greedy Strategy
Graph Algorithms
Algorithm Visualization
✨ Future Enhancements
Add BFS / DFS visualization
Use priority queue for optimized Dijkstra
Add backend with database
Export reports (PDF)
Real-time warehouse analytics dashboard
👤 Author
Hari Charan Bakkamanthala
B.Tech – Computer Science & Engineering
SRM University AP
📧 Email: Pavancharan4833@gmail.com
📍 Location: Amaravati, India
📜 License
This project is for educational purposes.
Feel free to fork, modify, and use with attribution.
