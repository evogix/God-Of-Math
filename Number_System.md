# 🔢 Number System – Complete Guide (Hybrid Style)

Understanding number systems is the base of **Mathematics** and **Computer Science**.  
Let’s break it down — in Hindi + English for easy understanding.  

---

## 🧠 What Is a Number System?

**Definition (English):**  
A Number System is a way to represent numbers using symbols or digits.  

**Hindi Explanation:**  
Number System ek aisa system hota hai jisme hum numbers ko likhne ke liye ek fixed set of symbols (digits) ka use karte hain.  

**Example:**  
Decimal system uses digits → `0–9`  
Binary system uses digits → `0` and `1`  

---

## 🧮 Types of Number Systems

| Type | Base | Digits Used | Example | Common Usage |
|------|------|--------------|----------|---------------|
| **Binary** | 2 | 0, 1 | 1011₂ | Used in Computers |
| **Octal** | 8 | 0–7 | 745₈ | Old computer systems |
| **Decimal** | 10 | 0–9 | 345₁₀ | Everyday counting |
| **Hexadecimal** | 16 | 0–9, A–F | 2F₁₆ | Computer memory, color codes |

---

## 💡 Concept of “Base” or “Radix”

**Base** means — kitne unique digits us system mein use hote hain.

**Example:**  
Binary → Base 2 → Digits = 2 (0,1)  
Decimal → Base 10 → Digits = 10 (0–9)  
Hexadecimal → Base 16 → Digits = 16 (0–9, A–F)

> **Rule:**  
> Base ke niche likha hua number (₁₀, ₂, ₈, ₁₆) system batata hai.  
> Example: 101ₐ → “a” batata hai kaunsa base use hua hai.

---

## 🔁 Conversion Between Number Systems

### 1️⃣ Binary ↔ Decimal
**Binary to Decimal Formula:**  
Multiply each digit by 2^position and add all.  

**Example:**  
```
(1011)₂ = 1×2³ + 0×2² + 1×2¹ + 1×2⁰ = 8 + 0 + 2 + 1 = (11)₁₀
```

**Decimal to Binary:**  
Divide by 2 repeatedly, take remainders backward.  

**Example:**  
```
(13)₁₀ → divide by 2 → 1101₂
```

---

### 2️⃣ Decimal ↔ Octal

**Decimal to Octal:** Divide by 8 repeatedly.  
**Example:** 65₁₀ → 101₈  

**Octal to Decimal:** Multiply digits by powers of 8.  
**Example:** 125₈ = 1×8² + 2×8¹ + 5×8⁰ = 64 + 16 + 5 = 85₁₀  

---

### 3️⃣ Decimal ↔ Hexadecimal

**Decimal to Hex:** Divide by 16, use A–F for 10–15.  
**Example:** 254₁₀ → FE₁₆  

**Hex to Decimal:** Multiply by powers of 16.  
**Example:** 2F₁₆ = (2×16¹) + (15×16⁰) = 32 + 15 = 47₁₀  

---

## 💻 Real-Life Applications

| Area | Use of Number System |
|------|----------------------|
| **Computers** | All data (text, image, sound) stored in binary form |
| **Networking** | IP addresses use binary/hexadecimal |
| **Colors in Web Design** | Hex codes (#FF5733 etc.) |
| **Digital Electronics** | Circuits use binary logic (0 = OFF, 1 = ON) |

---

## 🧩 Important Relationships

| Conversion | Shortcut |
|-------------|-----------|
| Binary ↔ Octal | Group 3 bits = 1 octal digit |
| Binary ↔ Hex | Group 4 bits = 1 hex digit |
| Decimal ↔ Others | Repeated division or multiplication method |

---

## 🧠 Quick Summary

| Type | Base | Digits | Example |
|------|------|---------|----------|
| Binary | 2 | 0,1 | 1011 |
| Octal | 8 | 0–7 | 745 |
| Decimal | 10 | 0–9 | 345 |
| Hexadecimal | 16 | 0–9, A–F | 2F |

---

## ⚙️ Bonus Concept: Positional Value

In every system, **position (place)** matters.  
For example, 345 in decimal =  
`3×10² + 4×10¹ + 5×10⁰ = 300 + 40 + 5`

Same logic works for binary, octal, hexadecimal — but power changes according to base.

---

## 🧩 Fun Fact

> Computers don’t understand numbers — they understand **ON/OFF (1 and 0)**.  
> But using combinations of binary digits, they represent **everything** — from photos to videos!

---

## ✍️ Practice Questions

1. Convert (1101)₂ → ?₁₀  
2. Convert (45)₁₀ → ?₂  
3. Convert (A5)₁₆ → ?₁₀  
4. Convert (175)₈ → ?₁₀  
5. What is the base of hexadecimal system?

---

## 🧭 Conclusion

Number systems form the **foundation** of digital technology.  
If you master this, understanding **computers, coding, networking, and electronics** becomes 10× easier.

---

📘 *Created for conceptual clarity — Hindi + English hybrid explanation for students.*  
**Author:** Faizal  
**File:** `Number_System.md`  
**Last Updated:** October 2025  
