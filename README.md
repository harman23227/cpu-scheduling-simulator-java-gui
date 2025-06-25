
# 🖥️ CPU Scheduling Simulator (Java GUI)

A Java-based simulator to visualize and compare different CPU scheduling algorithms through a graphical interface. Perfect for learning how operating systems schedule processes under different strategies like FCFS, SJN, Round Robin, and Priority Scheduling.

---

## 📌 Features

- ✅ Simulates popular CPU scheduling algorithms:
  - FCFS (First-Come, First-Served)
  - SJN (Shortest Job Next)
  - Round Robin (RR)
  - Priority Scheduling
- 🖼️ Java-based GUI for easy user interaction
- 📊 Shows execution order, turnaround time, waiting time, CPU idle time
- ✍️ Input your own process list with:
  - Process ID
  - Arrival Time
  - Burst Time
  - Priority (if applicable)
  - Quantum (for RR)

---

## 📁 Project Structure
cpu-scheduling-simulator-java-gui/
├── src/main/ # Java source files
├── target/ # Compiled classes (if applicable)
├── sources/ # Additional source files
├── pom.xml # Maven config (optional)



---

## 🚀 Getting Started

### 🔧 Prerequisites

- Java JDK 8 or higher
- (Optional) Apache Maven
- Java IDE (e.g., IntelliJ IDEA, Eclipse)

### ▶️ How to Run

1. **Clone the repository**

```bash```
git clone https://github.com/harman23227/cpu-scheduling-simulator-java-gui.git
cd cpu-scheduling-simulator-java-gui

2. **Clone the repository**

Using terminal:

javac -d bin src/main/*.java
java -cp bin Main
Or simply run the Main class from your IDE.


