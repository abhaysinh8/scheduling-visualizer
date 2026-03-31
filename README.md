# CPU Scheduling Algorithms Visualizer 🚀

An interactive educational simulator for visualizing Operating System CPU scheduling algorithms step-by-step. Built as an OS Internal Assessment project, it helps learners understand scheduling behavior through live Gantt chart animation and computed performance metrics.

## 🌐 Live Demo

https://scheduling-visualizer.vercel.app

## 🌟 Features

- **Live Gantt Chart Animation**: Watch the CPU parse and execute processes in real-time.
- **Dynamic Performance Metrics**: Automatically calculates Turnaround Time (TAT) and Waiting Time (WT) per process, alongside averages.
- **Seven Core Algorithms Supported**:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF) - Non-preemptive
  - Shortest Remaining Time Next (SRTN) - Preemptive SJF
  - Round Robin (RR)
  - Priority Scheduling (Non-preemptive & Preemptive)
  - Highest Response Ratio Next (HRRN)
- **One-Click Export**: Download high-resolution PNG snapshots of your Gantt Charts and Metrics for lab reports and assignments.
- **Zero Config**: Completely self-contained in a single HTML file using vanilla JavaScript and CSS.

## 🛠️ How to Use

1. **No Installation Needed!** Simply download or clone this repository and double click `cpu_scheduling_visualizer.html` to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
2. **Setup your Processes**: Use the input table to define your processes' Arrival Times, Burst Times, and Priorities.
3. **Select an Algorithm**: Pick the scheduling algorithm you wish to visualize. By default, FCFS is selected.
4. **Adjust Speed**: Select your preferred simulation speed (Easy, Medium, Fast).
5. **Run the Simulation**: Click "Run Simulation". You can pause, play, step forward, or skip to the end using the playback controls.
6. **Export**: Once the simulation completes, click the "Export PNG" button to save a picture of your results.

## 💻 Tech Stack

- **HTML5 & CSS3**: Utilizes native CSS grid/flexbox and elegant modern UI elements.
- **Vanilla JavaScript**: All algorithm logic and DOM rendering are handled locally with zero external dependencies (except `html2canvas` for exporting images).

---
*Created for an Operating System Internal Assessment (IA) Assignment.*
