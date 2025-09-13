# CPU Scheduling Algorithms – Group Project

This repository demonstrates CPU Scheduling Algorithms using multiple approaches: **Python** and **Web (HTML + JavaScript)**.

---

## 📌 About Scheduling Algorithms
- **FCFS (First Come First Serve)** → Non-preemptive, runs processes in arrival order.  
- **SJF (Shortest Job First)** → Selects the process with the smallest burst time.  
- **Round Robin** → Preemptive scheduling with fixed time quantum.  

**General formulas (for all):**  
- **Start Time** = max(Current Time, Arrival Time)  
- **Completion Time** = Start Time + Burst Time  
- **Waiting Time** = Start Time – Arrival Time  
- **Turnaround Time** = Completion Time – Arrival Time  

---

## 📂 Repository Structure
- `roundrobin.py` → Aloshy Antony’s Round Robin (Python) implementation  
- `fcfs.html` → Anto Boban’s FCFS (HTML + JavaScript) implementation  
- `sjf.html` → Vinek Vinod’s SJF (HTML + JavaScript) implementation  
- `README.md` → Documentation  

**Screenshots / Outputs:**  
- `aloshygit.jpg` → Aloshy’s Round Robin output  
- `antogit.jpg` → Anto’s FCFS output  
- `vinekgit.jpg` → Vinek’s SJF output  

---

## 👨‍💻 Contributors & Work

### Aloshy Antony – `roundrobin.py`
- Implemented in Python.  
- Supports **time quantum** for preemptive scheduling.  
- Calculates waiting & turnaround times.  
- Prints Gantt chart representation of process execution.  

### Anto Boban – `fcfs.html`
- Implemented in HTML + JavaScript.  
- Web-based FCFS scheduling simulation.  
- Displays process results in a browser table.  

### Vinek Vinod – `sjf.html`
- Implemented in HTML + JavaScript.  
- Web-based **Shortest Job First** scheduling.  
- Provides tabular output and scheduling order.  

---

## ▶️ Run Instructions

### Aloshy’s Round Robin (Python)
```bash
python roundrobin.py
