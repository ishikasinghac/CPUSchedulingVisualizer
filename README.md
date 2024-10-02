# 🖥️ CPUSchedulingVisualizer

![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

**CPUSchedulingVisualizer** is an interactive web-based platform designed to visualize various CPU scheduling algorithms. This tool helps students, developers, and educators to better understand CPU scheduling by providing dynamic, visual simulations.

## ✨ Features

- **Visualize CPU Scheduling Algorithms**: Supports the following CPU scheduling algorithms:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Round Robin (RR)
  - Shortest Remaining Time First (SRTF)
  - Priority Scheduling
- **Gantt Chart Representation**: Shows process scheduling over time.
- **Interactive User Interface**: Enter process details such as arrival time, burst time, priority, and quantum time for round-robin scheduling.
- **Real-Time Simulation**: Dynamic updates of the scheduling process with visual feedback.
- **Algorithm Comparison**: Displays key metrics such as average waiting time, turnaround time, and CPU utilization to compare different algorithms.

## 🛠️ Technologies Used

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript
- **Visualization**:
  - D3.js (for visual representation of Gantt charts)

## 🚀 Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ishikasinghac/CPUSchedulingVisualizer.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd CPUSchedulingVisualizer
   ```

3. **Open the `index.html` file** in your preferred web browser:
   - You can either open the file directly or serve it via a simple local server:
     ```bash
     python3 -m http.server 8000
     ```
   - Then navigate to `http://localhost:8000` in your browser.

No additional dependencies or installations are required to run the project.


## 🧭 How to Use

1. **Input the Parameters**:
   - Navigate to the input form where you can enter:
     - Number of processes
     - Arrival time
     - Burst time
     - Priority (for Priority Scheduling)
     - Time Quantum (for Round Robin)
   
2. **Select Scheduling Algorithm**:
   - Choose from the list of available scheduling algorithms:
     - FCFS, SJF, RR, SRTF, Priority

3. **Run the Simulation**:
   - Click the "Run Simulation" button to visualize the scheduling process. The platform will generate a Gantt chart displaying the process execution timeline.

4. **View Results**:
   - Check key performance metrics such as:
     - Average Waiting Time
     - Turnaround Time
     - CPU Utilization
   
   You can also compare different algorithms to see which performs best under the given scenario.

## 🏗️ Project Structure

```
CPUSchedulingVisualizer/
├── css/
│   └── styles.css           # CSS for styling the webpage
├── js/
│   └── main.js              # JavaScript logic for scheduling algorithms
├── index.html               # Main HTML page
└── README.md                # This readme file
```

