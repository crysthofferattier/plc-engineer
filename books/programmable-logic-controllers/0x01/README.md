### 1. What is a programmable logic controller (PLC)?  
A PLC is a solid-state control device designed to perform logic, sequencing, timing, counting, and control functions for industrial automation processes. It uses programmable memory to store instructions and execute specific control tasks such as monitoring inputs, making decisions, and controlling outputs.

---

### 2. Identify four tasks in addition to relay switching operations that PLCs are capable of performing.  
1. **Timing and counting** operations.  
2. **Mathematical computations** such as addition, subtraction, multiplication, and division.  
3. **Data handling** functions, such as moving, comparing, or manipulating data.  
4. **Process control** through proportional, integral, and derivative (PID) functions.

---

### 3. List six distinct advantages that PLCs offer over conventional relay-based control systems.  
1. **Flexibility**: Easy to reprogram for different control tasks.  
2. **Space-saving**: Eliminates large relay panels.  
3. **Reduced wiring**: Minimal wiring compared to relay-based systems.  
4. **Reliability**: Solid-state electronics offer higher reliability and longer life.  
5. **Troubleshooting ease**: Diagnostic tools simplify problem identification.  
6. **Cost-effectiveness**: Lower maintenance and operational costs over time.

---

### 4. Explain the differences between open and proprietary PLC architecture.  
- **Open Architecture**: Allows integration with hardware and software from multiple manufacturers.  
- **Proprietary Architecture**: Restricts compatibility to hardware and software from a single manufacturer.

---

### 5. State two ways in which I/O is incorporated into the PLC.  
1. **Fixed I/O**: Integrated into the PLC unit, where the number and type of I/O points are predetermined.  
2. **Modular I/O**: Separate, interchangeable modules that can be added or removed to customize the I/O configuration.

---

### 6. Describe how the I/O modules connect to the processor in a modular-type PLC configuration.  
I/O modules connect to the processor via a **backplane** or **bus system**, which provides power and communication pathways between the processor and the I/O modules.

---

### 7. Explain the main function of each of the following major components of a PLC:  
a. **Processor Module (CPU)**: Executes the control program and manages communication between the I/O modules and other devices.  
b. **I/O Modules**: Interface the PLC with external devices, allowing inputs (sensors) and outputs (actuators) to be connected.  
c. **Programming Device**: Used to write, edit, and load the control program into the PLC.  
d. **Power Supply Module**: Supplies the necessary electrical power to the PLC and its components.

---

### 8. What are the two most common types of PLC ­programming devices?  
1. **Personal computers (PCs)** with specialized programming software.  
2. **Hand-held programming terminals.**

---

### 9. Explain the terms program and programming ­language as they apply to a PLC.  
- **Program**: A sequence of instructions designed to control a specific process.  
- **Programming Language**: The method used to write the instructions, such as ladder logic, function block diagram (FBD), or structured text (ST).

---

### 10. What is the standard programming language used with PLCs?  
The standard programming language is **Ladder Logic** (also known as Ladder Diagram), based on graphical symbols.

---

### 11. Answers regarding Figure 1-13 (Relay Ladder Diagram):  
*(Refer to the book for the diagram and these explanations.)*

---

### 12. The programmable controller operates in real time. What does this mean?  
Real-time operation means the PLC processes inputs, executes the program, and updates outputs continuously, ensuring control decisions are made as events occur.

---

### 13. Answers regarding Figure 1-16 (PLC Ladder Logic Diagram):  
*(Refer to the book for the diagram and these explanations.)*

---

### 14. Compare the method by which the process control operation is changed in a relay-based system to the method used for a PLC-based system.  
- **Relay-Based System**: Requires physical rewiring to modify the control logic.  
- **PLC-Based System**: Changes can be made by simply reprogramming the logic.

---

### 15. Compare the PLC and PC with regard to:  
a. **Physical Hardware Differences**: PLCs are rugged and designed for industrial environments, while PCs are general-purpose devices.  
b. **Operating Environment**: PLCs withstand harsh environments (temperature, vibration), whereas PCs are sensitive to such conditions.  
c. **Method of Programming**: PLCs use specialized languages like ladder logic, while PCs are programmed using high-level languages.  
d. **Execution of Program**: PLCs execute programs in a repetitive scan cycle, while PCs follow sequential or event-driven execution.

---

### 16. What two categories of software written and run on PCs are used in conjunction with PLCs?  
1. **Programming software**: For writing and debugging PLC programs.  
2. **HMI/SCADA software**: For monitoring and controlling industrial processes.

---

### 17. What is a programmable automation controller (PAC)?  
A PAC is an advanced automation controller that combines the functionality of a PLC with higher-level features such as multi-tasking, complex data handling, and networking.

---

### 18. List four criteria by which PLCs are categorized.  
1. **Size and complexity**: Nano, micro, and large PLCs.  
2. **Number of I/O points**.  
3. **Memory capacity**.  
4. **Communication capabilities**.

---

### 19. Compare the single-ended, multitask, and control management types of PLC applications.  
- **Single-Ended**: Handles a single process or machine.  
- **Multitask**: Manages multiple processes simultaneously.  
- **Control Management**: Supervises and coordinates other PLCs in a hierarchical system.

---

### 20. What is the memory capacity, expressed in bits, for a PLC that uses 16-bit words and has an 8 K word capacity?  
\[ \text{Memory Capacity} = \text{Number of Words} \times \text{Bits per Word} \]  
\[ 8,192 \, \text{words} \times 16 \, \text{bits/word} = 131,072 \, \text{bits} \]

---

### 21. List five factors affecting the memory size needed for a particular PLC installation.  
1. Number of I/O points.  
2. Size of the control program.  
3. Complexity of the logic.  
4. Data storage requirements.  
5. Communication functions.

---

### 22. What does the instruction set for a particular PLC refer to?  
The **instruction set** refers to the collection of commands and functions available for programming the PLC, such as logic operations, timers, counters, and arithmetic functions.

--- 

Let me know if you need clarification or additional details!