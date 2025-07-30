# C-plus-plus-Decision-Making-Statements-Loops
# 🔁 Experiment 6 
## 🎯 Objective

To understand, analyze, and implement **looping mechanisms** in C++ programming. This includes using:
- `for` loops
- `while` loops
- `do-while` loops

The goal is to gain clarity on their syntactic structure, logical flow, and suitable use-cases in programming problems involving **repetition and iteration**.

---

## 📚 Background Theory

### 🔄 What is a Loop?

A **loop** in programming is a control structure that allows repeated execution of a block of code based on a defined condition. Loops are a fundamental concept in structured programming, enabling concise and efficient code by reducing redundancy.

Loops are categorized as **entry-controlled** (e.g., `for`, `while`) and **exit-controlled** (e.g., `do-while`) based on when the loop condition is checked.

---

## 🧱 Types of Loops in C++

### 1️⃣ `for` Loop

#### ➤ Description:
- Best used when the number of iterations is **known in advance**.
- Typically used in **count-controlled loops**.
- It groups **initialization**, **condition**, and **update** into a single line for compact syntax.

#### ➤ Flow:
1. Initialize loop control variable.
2. Check the loop condition.
3. If `true`, execute the loop body.
4. Perform increment/decrement.
5. Repeat from step 2.

#### ➤ Characteristics:
- Compact syntax.
- Ideal for fixed-length tasks like traversing arrays or generating patterns.

---

### 2️⃣ `while` Loop

#### ➤ Description:
- Used when the number of iterations is **not predetermined**.
- Condition is evaluated **before** executing the loop body.

#### ➤ Flow:
1. Evaluate the loop condition.
2. If `true`, execute the loop body.
3. Return to step 1.
4. If `false`, exit the loop.

#### ➤ Characteristics:
- Entry-controlled loop.
- Suitable for **condition-based** iteration like input validation or real-time events.

---

### 3️⃣ `do-while` Loop

#### ➤ Description:
- Similar to `while` loop, but the **condition is checked after** the body is executed.
- Guarantees that the loop body executes **at least once**, regardless of the condition.

#### ➤ Flow:
1. Execute the loop body.
2. Evaluate the loop condition.
3. If `true`, repeat from step 1.

#### ➤ Characteristics:
- Exit-controlled loop.
- Suitable for **menu-driven programs**, **post-processing**, or where one-time execution is required before checking the condition.

---

## 🔍 Comparative Summary

| Feature              | `for` Loop                | `while` Loop              | `do-while` Loop              |
|----------------------|---------------------------|---------------------------|------------------------------|
| Control Type         | Entry-controlled          | Entry-controlled          | Exit-controlled              |
| Condition Check Time | Before loop body          | Before loop body          | After loop body              |
| Guaranteed Execution | No                        | No                        | Yes                          |
| Ideal Use Case       | Fixed iterations          | Unknown iterations        | One-time or menu loops       |

---

## 🧪 Educational Value

This experiment serves as the foundation for:
- Designing **efficient control flows** in programs.
- Applying **decision-making and repetition** constructs together.
- Understanding **iteration** in real-world tasks such as:
  - Pattern generation
  - Repeated user inputs
  - Mathematical computations (e.g., factorials, summations)
  - Search and traversal in data structures

---

## ✅ Learning Outcomes

Upon completion, students will:
- Understand different loop types and their execution behavior.
- Be able to select the appropriate loop for a given scenario.
- Implement nested and conditional loops to solve real-world problems.
- Develop a strong base for handling arrays, functions, and algorithm design.
