# Microprocessors and Microsystems

This repository contains various **embedded systems projects** developed using **MikroC PRO for PIC**.  
It includes exercises on **digital logic gates**, **conditional programming**, and more complex projects like **sensor-based monitoring systems**.  
These projects are ideal for students or hobbyists learning about **microcontrollers, ADCs, and LCD interfacing**.

---

## 📂 Repository Structure

| File / Folder | Description |
|---------------|-------------|
| `and.mcppi` | Implements the **AND logic gate** using PIC I/O pins. |
| `or.mcppi` | Implements the **OR logic gate**. |
| `xor.mcppi` | Implements the **XOR logic gate**. |
| `If.mcppi` | Demonstrates **conditional logic** using `if` statements. |
| `project2.mcppi`, `project3.mcppi`, `project4.mcppi` | Intermediate-level projects exploring **microcontroller features** such as port manipulation, timers, or simple sensor interfacing. |
| `final project.mcppi` | **Gas leak detection system**: reads analog sensor input, displays gas concentration on an LCD, and triggers alarms. |
| `docs/` (optional) | Notes, diagrams, or additional explanations for the projects. |

---

## 🛠 Tools and Technology

- **MikroC PRO for PIC** – to write, compile, and manage `.c` / `.mcppi` project files.  
- **Proteus 8.13+** – to simulate PIC circuits and LCD outputs.  
- **PIC Microcontrollers** – PIC16F877A, PIC16F84A (common across projects).  
- Understanding of **digital logic gates**, **ADC**, **GPIO**, and **LCD interfacing**.  

---

## 📖 Projects Overview

### 1. **Logic Gate Projects**
- `and.mcppi`, `or.mcppi`, `xor.mcppi`  
- Teach the basics of digital logic using microcontroller inputs and outputs.  
- Example: input switches on PORTB, LED output on PORTA.  

### 2. **Conditional Logic Project**
- `If.mcppi`  
- Demonstrates **decision-making** in embedded C using `if` statements.  
- Can be used to trigger outputs based on sensor or input values.  

### 3. **Intermediate Projects**
- `project2.mcppi`, `project3.mcppi`, `project4.mcppi`  
- Builds on simple logic, introducing **timers, counters, or analog inputs**.  
- Good practice for real microcontroller applications.  

### 4. **Final Project – Gas Leak Detection**
- Reads **analog gas sensor input** from AN0.  
- Displays **gas concentration in ppm** on a 16x2 LCD.  
- Triggers **alarms (LED/buzzer)** on PORTC depending on gas level:  
  - 0–20 ppm → mild gas  
  - 21–40 ppm → gas leak  
  - >40 ppm → toxic gas  
- Teaches **ADC usage, LCD interfacing, and real-time monitoring**.  

---

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/Fzsm/microprocessors-and-microsystems.git
cd microprocessors-and-microsystems
