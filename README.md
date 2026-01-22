# Stack Data Structure (DSA)

A **Stack** is a linear data structure that follows the principle  
**LIFO – Last In, First Out**.

This means:
- The element inserted last will be removed first.

---

## Stack Operations

### 1️⃣ Push
**Push** is the operation of **adding an element** to the top of the stack.

**Steps:**
1. Check if the stack is full (Overflow condition)
2. Increase the `top` value
3. Insert the element at `stack[top]`

**Example:**
# Stack Data Structure (DSA)

A **Stack** is a linear data structure that follows the principle  
**LIFO – Last In, First Out**.

This means:
- The element inserted last will be removed first.

---

## Stack Operations

### 1️⃣ Push
**Push** is the operation of **adding an element** to the top of the stack.

**Steps:**
1. Check if the stack is full (Overflow condition)
2. Increase the `top` value
3. Insert the element at `stack[top]`

**Example:**
---

### 2️⃣ Pop
**Pop** is the operation of **removing the top element** from the stack.

**Steps:**
1. Check if the stack is empty (Underflow condition)
2. Access the element at `stack[top]`
3. Decrease the `top` value

**Example:**
---

### 3️⃣ Peek
**Peek** is used to **view the top element** of the stack **without removing it**.

**Steps:**
1. Check if the stack is empty
2. Return `stack[top]`

**Example:**
---

### 4️⃣ Top
**Top** refers to the **index or position of the topmost element** in the stack.

- It is usually stored in a variable called `top`
- Initial value of `top` is `-1` (stack is empty)

**Example:**
---

## Stack Conditions

### Overflow
Occurs when trying to **push** an element into a **full stack**.

### Underflow
Occurs when trying to **pop or peek** from an **empty stack**.

---

## Applications of Stack
- Function calls (Call Stack)
- Expression evaluation (Prefix, Infix, Postfix)
- Undo / Redo operations
- Backtracking algorithms

---

## Language Used
- C Programming

---

## Author
**P Senthil Kumaar**

