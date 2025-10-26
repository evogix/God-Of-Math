```
# Number Systems - Complete Guide (Hinglish mein)

Chalo bachcho ki tarah step-by-step samajhte hain! 🎯

## 1. DECIMAL SYSTEM (Dashamik Pranali)

### Kya hai ye?
- Ye wo system hai jo hum roz use karte hain
- **Base 10** hai (0 se 9 tak digits)
- 10 digits hain: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9

### Place Value samjho:

```
Number: 5432
       ↓ ↓ ↓ ↓
       5 4 3 2
       | | | |
   10³ 10² 10¹ 10⁰
   1000 100 10  1
```

**Calculation:**
- 5 × 1000 = 5000
- 4 × 100 = 400
- 3 × 10 = 30
- 2 × 1 = 2
- **Total = 5432**

### Example:
Number **729** ko breakdown karo:
- 7 × 10² = 7 × 100 = 700
- 2 × 10¹ = 2 × 10 = 20
- 9 × 10⁰ = 9 × 1 = 9
- **Total = 729**

---

## 2. BINARY SYSTEM (Dviyk Pranali)

### Kya hai ye?
- Computer ki language! 🖥️
- **Base 2** hai (sirf 0 aur 1)
- 2 digits: 0, 1

### Place Value:

```
Binary: 1011
        ↓ ↓ ↓ ↓
        1 0 1 1
        | | | |
       2³ 2² 2¹ 2⁰
       8  4  2  1
```

**Decimal mein convert karo:**
- 1 × 8 = 8
- 0 × 4 = 0
- 1 × 2 = 2
- 1 × 1 = 1
- **Total = 11 (decimal mein)**

### Examples:

**Example 1:** Binary **101** ko decimal mein
- 1 × 2² = 1 × 4 = 4
- 0 × 2¹ = 0 × 2 = 0
- 1 × 2⁰ = 1 × 1 = 1
- **Answer = 5**

**Example 2:** Decimal **13** ko binary mein convert karo

**Method - Divide by 2:**
```
13 ÷ 2 = 6 remainder 1  ←
6 ÷ 2 = 3 remainder 0   ←
3 ÷ 2 = 1 remainder 1   ←
1 ÷ 2 = 0 remainder 1   ←
```
**Neeche se upar padho: 1101**

**Verify:** 1×8 + 1×4 + 0×2 + 1×1 = 8+4+0+1 = 13 ✓

---

## 3. OCTAL SYSTEM (Ashtak Pranali)

### Kya hai ye?
- **Base 8** hai
- 8 digits: 0, 1, 2, 3, 4, 5, 6, 7
- 8 aur 9 nahi hote!

### Place Value:

```
Octal: 725
       ↓ ↓ ↓
       7 2 5
       | | |
      8² 8¹ 8⁰
      64 8  1
```

**Decimal mein:**
- 7 × 64 = 448
- 2 × 8 = 16
- 5 × 1 = 5
- **Total = 469**

### Examples:

**Example 1:** Octal **52** ko decimal mein
- 5 × 8¹ = 5 × 8 = 40
- 2 × 8⁰ = 2 × 1 = 2
- **Answer = 42**

**Example 2:** Decimal **100** ko octal mein

**Method - Divide by 8:**
```
100 ÷ 8 = 12 remainder 4  ←
12 ÷ 8 = 1 remainder 4    ←
1 ÷ 8 = 0 remainder 1     ←
```
**Answer: 144 (octal)**

**Verify:** 1×64 + 4×8 + 4×1 = 64+32+4 = 100 ✓

---

## 4. HEXADECIMAL SYSTEM (Shodash Pranali)

### Kya hai ye?
- **Base 16** hai
- 16 symbols: 0-9 aur A-F
- **A=10, B=11, C=12, D=13, E=14, F=15**

### Place Value:

```
Hex: 2F3
     ↓ ↓ ↓
     2 F 3
     | | |
   16² 16¹ 16⁰
   256 16  1
```

**Decimal mein:**
- 2 × 256 = 512
- F × 16 = 15 × 16 = 240
- 3 × 1 = 3
- **Total = 755**

### Examples:

**Example 1:** Hex **1A** ko decimal mein
- 1 × 16¹ = 1 × 16 = 16
- A × 16⁰ = 10 × 1 = 10
- **Answer = 26**

**Example 2:** Decimal **255** ko hex mein

**Method - Divide by 16:**
```
255 ÷ 16 = 15 remainder 15 (F)  ←
15 ÷ 16 = 0 remainder 15 (F)    ←
```
**Answer: FF**

**Verify:** F×16 + F×1 = 15×16 + 15 = 240+15 = 255 ✓

---

## CONVERSION TABLE (Quick Reference)

| Decimal | Binary | Octal | Hexadecimal |
|---------|--------|-------|-------------|
| 0       | 0      | 0     | 0           |
| 1       | 1      | 1     | 1           |
| 2       | 10     | 2     | 2           |
| 3       | 11     | 3     | 3           |
| 4       | 100    | 4     | 4           |
| 5       | 101    | 5     | 5           |
| 6       | 110    | 6     | 6           |
| 7       | 111    | 7     | 7           |
| 8       | 1000   | 10    | 8           |
| 9       | 1001   | 11    | 9           |
| 10      | 1010   | 12    | A           |
| 11      | 1011   | 13    | B           |
| 12      | 1100   | 14    | C           |
| 13      | 1101   | 15    | D           |
| 14      | 1110   | 16    | E           |
| 15      | 1111   | 17    | F           |
| 16      | 10000  | 20    | 10          |

---

## CONVERSION METHODS (Ek System se Dusre mein)

### Kisi bhi system se Decimal:
**Formula:** Har digit × (Base)^position

### Decimal se Kisi bhi system:
**Method:** Base se divide karo, remainders neeche se upar padho

### Binary se Octal (Shortcut):
3 binary digits = 1 octal digit
```
Binary: 110 101 011
Octal:   6   5   3  = 653
```

### Binary se Hex (Shortcut):
4 binary digits = 1 hex digit
```
Binary: 1101 1010
Hex:     D    A   = DA
```

---

## PRACTICE PROBLEMS

### Level 1 (Easy):
1. Binary **1001** = ? (Decimal)
2. Decimal **25** = ? (Binary)
3. Octal **17** = ? (Decimal)

### Level 2 (Medium):
1. Hex **AB** = ? (Decimal)
2. Decimal **200** = ? (Octal)
3. Binary **11111111** = ? (Hex)

### Answers:
**Level 1:** 
1. 9
2. 11001
3. 15

**Level 2:** 
1. 171
2. 310
3. FF

---

## YAAD RAKHNE KE TIPS:

1. **Base yaad rakho:**
   - Decimal = 10
   - Binary = 2
   - Octal = 8
   - Hex = 16

2. **Powers yaad rakho:**
   - 2⁰=1, 2¹=2, 2²=4, 2³=8, 2⁴=16, 2⁵=32, 2⁶=64, 2⁷=128, 2⁸=256

3. **Hex letters:**
   - A=10, B=11, C=12, D=13, E=14, F=15

4. **Practice karo daily!** 💪

---

## BONUS: Arithmetic Operations

### Binary Addition:
```
Rules:
0 + 0 = 0
0 + 1 = 1
1 + 0 = 1
1 + 1 = 10 (carry 1)

Example: 1011 + 1101
    1011
  + 1101
  ------
   11000
```

### Binary Subtraction:
```
Rules:
0 - 0 = 0
1 - 0 = 1
1 - 1 = 0
0 - 1 = 1 (borrow 1)

Example: 1101 - 1011
    1101
  - 1011
  ------
    0010
```

### Binary Multiplication:
```
Rules:
0 × 0 = 0
0 × 1 = 0
1 × 0 = 0
1 × 1 = 1

Example: 101 × 11
     101
   ×  11
   -----
     101
   101
   -----
   1111
```

---

## Important Formulas

1. **Decimal to Any Base:**
   - Repeatedly divide by base
   - Read remainders from bottom to top

2. **Any Base to Decimal:**
   - Σ(digit × base^position)

3. **Maximum value with n digits:**
   - Decimal: 10^n - 1
   - Binary: 2^n - 1
   - Octal: 8^n - 1
   - Hex: 16^n - 1

4. **Number of digits required:**
   - Digits needed = ⌊log_base(number)⌋ + 1

---

## Real-Life Applications

### Binary:
- Computer memory aur processing
- Digital electronics
- Network protocols

### Octal:
- File permissions in Unix/Linux
- Digital displays

### Hexadecimal:
- Color codes (#FFFFFF)
- Memory addresses
- MAC addresses
- Assembly language

---

Chapter Closed 🔐 😔 
```
