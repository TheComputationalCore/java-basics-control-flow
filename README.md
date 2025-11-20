# Java Basics: Control Flow

![Java Build](https://github.com/TheComputationalCore/java-basics-control-flow/actions/workflows/java-ci.yml/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

This repository contains a set of beginner-friendly Java programs demonstrating **control flow**, including looping, branching, number processing, pattern printing, and basic input/output logic.

It includes **7 standalone programs**, each focusing on a fundamental Java concept.

---

## 📁 Project Structure

```
java-basics-control-flow/
├── src/
│   ├── PrintNumberRange.java
│   ├── CheckNumberSign.java
│   ├── ReverseNumber.java
│   ├── FindSmallestOfThree.java
│   ├── DiscountCalculator.java
│   ├── NumberPatternGenerator.java
│   ├── NumberPatternGeneratorAlt.java
├── screenshots/
│   ├── printnumrange.png
│   ├── numcheck.png
│   ├── reversenum.png
│   ├── smallnum.png
│   ├── discountcal.png
│   ├── pattern.png
├── LICENSE
└── README.md
```

---

## 📝 Program Overviews

### **1️⃣ PrintNumberRange.java**  
Prints numbers from **10 to 50** using a loop.

📸 Screenshot:  
![Print Number Range](screenshots/printnumrange.png)

---

### **2️⃣ CheckNumberSign.java**  
Checks whether a number is **positive** or **negative**.

📸 Screenshot:  
![Number Sign Check](screenshots/numcheck.png)

---

### **3️⃣ ReverseNumber.java**  
Reverses digits in a number  
Example: `876 → 678`

📸 Screenshot:  
![Reverse Number](screenshots/reversenum.png)

---

### **4️⃣ FindSmallestOfThree.java**  
Inputs three numbers and prints the **smallest**.

📸 Screenshot:  
![Smallest of Three](screenshots/smallnum.png)

---

### **5️⃣ DiscountCalculator.java**  
Applies a discount based on purchase amount:

| Amount Range | Discount |
|--------------|----------|
| < 500        | 0%       |
| 500–1000     | 10%      |
| > 1000       | 20%      |

📸 Screenshot:  
![Discount Calculator](screenshots/discountcal.png)

---

### **6️⃣ NumberPatternGenerator.java**  
Prints a number-based pattern using loops.

📸 Screenshot:  
![Pattern](screenshots/pattern.png)

---

### **7️⃣ NumberPatternGeneratorAlt.java**  
Alternative implementation of the number pattern.

---

## ▶️ Running the Programs

### Clone Repository
```bash
git clone https://github.com/TheComputationalCore/java-basics-control-flow.git
cd java-basics-control-flow/src
```

### Compile All Programs
```bash
javac *.java
```

### Run a Specific Program
```bash
java PrintNumberRange
java CheckNumberSign
java ReverseNumber
java FindSmallestOfThree
java DiscountCalculator
java NumberPatternGenerator
```

---

## 🛠 Requirements
- Java **JDK 8 or higher**
- Any Java IDE or terminal

---

## 📄 License
This project is licensed under the **MIT License**.

