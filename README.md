# 🚀 Logisim Projects

## 📖 Introduction
This repository contains multiple **digital logic circuits** implemented using **Logisim Evolution**. These circuits demonstrate fundamental concepts of digital electronics, such as counters, arithmetic operations, encoding/decoding, and memory organization. Each project focuses on a specific functionality and showcases how digital components interact to perform various logical operations.

## 🛠 Included Circuits

### 1️⃣ **3-Bit Down Counter**
A synchronous **3-bit down counter** that counts in descending order (7 → 6 → 5 → ... → 0 → 7). It utilizes **flip-flops, clock signals,** and **reset logic** to decrement the count at every clock pulse.

**Key Features:**
- Uses **D or T flip-flops** to store binary count values.
- Decrements the count on every clock pulse.
- Implements **asynchronous/synchronous reset** for proper initialization.
- Can be extended to larger bit-widths as needed.

### 2️⃣ **BCD to Excess-3 Converter**
This circuit converts a **Binary-Coded Decimal (BCD)** number to its equivalent **Excess-3 (XS-3)** representation. Excess-3 encoding is commonly used in digital systems and arithmetic circuits.

**Key Features:**
- Implements **binary addition logic** to add '3' to the BCD input.
- Uses combinational logic gates for efficient conversion.
- Avoids invalid BCD states, ensuring correct representation.

### 3️⃣ **BCD to Hex 7-Segment Display Decoder**
A digital circuit that converts a **4-bit BCD input** into a **7-segment display format**, allowing numerical values (0-9) and hexadecimal values (A-F) to be displayed correctly.

**Key Features:**
- Uses combinational logic to generate **7-segment display outputs**.
- Implements **truth tables** for proper character mapping.
- Supports **both numerical (0-9) and hexadecimal (A-F) digits**.

### 4️⃣ **4-Bit Comparator**
A **4-bit magnitude comparator** that compares two **4-bit binary numbers (A and B)** and determines their relationship: greater than, less than, or equal.

**Key Features:**
- Outputs **A > B, A < B, and A = B** conditions.
- Uses combinational logic circuits like **AND, OR, NOT, XOR gates**.
- Can be extended to compare larger bit-widths by cascading multiple units.

### 5️⃣ **Cache Memory Simulation (2107086_Cache.circ)**
A **basic cache memory simulation** that demonstrates how cache storage works in a digital system. This project showcases **cache hits, misses, and data retrieval processes**.

**Key Features:**
- Implements **direct-mapped or associative cache logic**.
- Simulates memory access patterns to observe **cache performance**.
- Uses **RAM/ROM components** to store frequently accessed data.

## 📂 File Structure
```plaintext
/Logisim_Projects
│── 3 bit downcounter.circ  # Synchronous 3-bit down counter
│── BCD to Excess 3 circuit 2107086.circ  # BCD to Excess-3 converter
│── BCD to Hex 7 segment circuit 2107086.circ  # BCD to 7-segment decoder
│── 4 bit comparator 2107086.circ  # 4-bit binary comparator
│── 2107086_Cache.circ  # Cache memory simulation
│── README.md  # Documentation file
```

## 🚀 How to Run the Circuits

### 🔹 Steps to Open in Logisim Evolution
1. **Download and Install** Logisim Evolution → [Logisim Evolution](https://logisim-evolution.org)
2. **Open Logisim Evolution** and load the desired circuit file.
3. **Start the Simulation** by clicking **Simulate → Tick Once** or enabling continuous ticking.
4. **Modify Inputs and Observe Outputs** using switches and LEDs.

## 🔍 Debugging & Common Issues

### 🔹 Floating Inputs (Red Wires)
- Ensure all inputs have defined values (**use constants or input switches**).
- Verify correct connections in combinational circuits.

### 🔹 Incorrect Outputs
- Check **flip-flop connections** in sequential circuits.
- Verify **truth tables** for combinational logic correctness.
- Ensure proper clock signals are applied.

## 🛠 Future Improvements
- ✅ Extend counter circuits to **higher bit-widths**.
- ✅ Implement **priority encoders and decoders**.
- ✅ Improve **cache replacement strategies** for better performance.

## 📜 License
This project is **open-source**. Feel free to use, modify, and contribute!

## 💡 Conclusion
This repository serves as a practical guide to **digital logic design** using **Logisim Evolution**. Each project highlights core **digital electronics concepts**, making it useful for students and hobbyists exploring **computer architecture and circuit design**.
