# CPU Scheduling Visualizer

A web-based tool that simulates and visualizes various CPU scheduling algorithms. This project helps users understand how scheduling algorithms work by providing an interactive visual representation of processes being scheduled.

## Features

- **Algorithms Implemented**:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Round Robin (RR)
  - Priority Non-preemptive (PN)
  - Priority Preemptive (PP)
  
- **Visual Representation**: Displays a Gantt chart of the processes as they are scheduled.
- **Interactive Input**: Users can input custom processes with parameters like burst time, arrival time, and priority.
- **Step-by-Step Simulation**: View the scheduling step by step, allowing for a detailed understanding of each algorithm's behavior.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Algorithms**: Data Structures and Algorithm concepts for CPU scheduling
- **Visualization**: Dynamic Gantt chart generation using JavaScript and CSS

## Requirements

- A modern web browser (e.g., Chrome, Firefox)

## Installation

 Clone the repository:
     git clone https://github.com/Prathamesh-Hajare/CPU-Scheduling-Visualizer.git
    

## Usage

1. **Input Processes**: You can add multiple processes with the following parameters:
   - **Burst Time**: The amount of time the process requires for execution.
   - **Arrival Time**: The time at which the process arrives in the ready queue.
   - **Priority** (for priority-based algorithms).
   
2. **Select Scheduling Algorithm**: Choose one of the scheduling algorithms from the dropdown menu.

3. **Simulate**: Click on the "Start Simulation" button to visualize the scheduling process.

4. **Gantt Chart**: Observe how each algorithm schedules the processes using a Gantt chart that dynamically updates with the simulation.

## Algorithms Overview

- **FCFS (First Come First Serve)**: Processes are executed in the order of their arrival.
- **SJF (Shortest Job First)**: The process with the smallest burst time is executed first.
- **RR (Round Robin)**: Each process gets a fixed time slice for execution, after which it goes to the back of the queue.
- **PN (Priority Non-preemptive)**: Processes are scheduled based on priority, without preemption.
- **PP (Priority Preemptive)**: Higher priority processes can preempt the current running process.

## Future Enhancements

- Add support for additional algorithms (e.g., Multilevel Queue, Multilevel Feedback Queue).
- Improve UI for better user experience.
- Optimize performance for larger datasets.
