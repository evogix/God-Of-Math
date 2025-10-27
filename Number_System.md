# Number Systems - Complete Guide (Hinglish mein)

Chalo bachho ki tarah step-by-step samajhte hain! 🎓

## 1. DECIMAL NUMBER SYSTEM (Dashamik Paddhati)

**Base/Radix: 10**

Ye wahi system hai jo hum daily life mein use karte hain.

**Digits available:** 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 (total 10 digits)

### Place Value ka concept:

```
     Thousands | Hundreds | Tens | Units
        10³    |   10²    | 10¹  |  10⁰
       1000    |   100    |  10  |   1
```

**Example 1:** 2345 ko samajhte hain
- 2345 = (2 × 10³) + (3 × 10²) + (4 × 10¹) + (5 × 10⁰)
- 2345 = (2 × 1000) + (3 × 100) + (4 × 10) + (5 × 1)
- 2345 = 2000 + 300 + 40 + 5

**Example 2:** 567
- 567 = (5 × 10²) + (6 × 10¹) + (7 × 10⁰)
- 567 = (5 × 100) + (6 × 10) + (7 × 1)
- 567 = 500 + 60 + 7

---

## 2. BINARY NUMBER SYSTEM (Dviaadhaarik Paddhati)

**Base/Radix: 2**

Computer ki language! Sirf 2 digits use hote hain.

**Digits available:** 0, 1 (bas itne hi!)

### Place Value:

```
    2³  |  2²  |  2¹  |  2⁰
    8   |  4   |  2   |  1
```

**Example 1:** Binary 1011 ko decimal mein convert karte hain

```
Position:     3    2    1    0
Binary:       1    0    1    1
Place value:  2³   2²   2¹   2⁰
             (8)  (4)  (2)  (1)

Calculation:
= (1 × 2³) + (0 × 2²) + (1 × 2¹) + (1 × 2⁰)
= (1 × 8) + (0 × 4) + (1 × 2) + (1 × 1)
= 8 + 0 + 2 + 1
= 11 (Decimal)
```

**Example 2:** Binary 11010 ko decimal mein

```
Position:     4    3    2    1    0
Binary:       1    1    0    1    0
Place value: 2⁴   2³   2²   2¹   2⁰
            (16)  (8)  (4)  (2)  (1)

= (1×16) + (1×8) + (0×4) + (1×2) + (0×1)
= 16 + 8 + 0 + 2 + 0
= 26 (Decimal)
```

### Decimal se Binary kaise banaye?

**Method: 2 se divide karte raho**

**Example:** 13 ko binary mein convert karo

```
2 | 13
  |---
2 | 6  --- Remainder: 1  (sabse last digit)
  |---
2 | 3  --- Remainder: 0
  |---
2 | 1  --- Remainder: 1
  |---
  | 0  --- Remainder: 1  (sabse first digit)

Answer: 1101 (neeche se upar padho)
```

**Verification:**
1101 = (1×8) + (1×4) + (0×2) + (1×1) = 8+4+0+1 = 13 ✓

**Example 2:** 25 ko binary mein

```
2 | 25
2 | 12 --- R: 1
2 | 6  --- R: 0
2 | 3  --- R: 0
2 | 1  --- R: 1
  | 0  --- R: 1

Answer: 11001
```

---

## 3. OCTAL NUMBER SYSTEM (Ashtaadhaarik Paddhati)

**Base/Radix: 8**

**Digits available:** 0, 1, 2, 3, 4, 5, 6, 7 (total 8 digits)

### Place Value:

```
   8³  |  8²  |  8¹  |  8⁰
  512  |  64  |  8   |  1
```

**Example 1:** Octal 347 ko decimal mein

```
Position:     2    1    0
Octal:        3    4    7
Place value:  8²   8¹   8⁰
             (64)  (8)  (1)

= (3 × 8²) + (4 × 8¹) + (7 × 8⁰)
= (3 × 64) + (4 × 8) + (7 × 1)
= 192 + 32 + 7
= 231 (Decimal)
```

**Example 2:** Octal 125 ko decimal mein

```
= (1 × 8²) + (2 × 8¹) + (5 × 8⁰)
= (1 × 64) + (2 × 8) + (5 × 1)
= 64 + 16 + 5
= 85 (Decimal)
```

### Decimal se Octal kaise banaye?

**Method: 8 se divide karte raho**

**Example:** 83 ko octal mein

```
8 | 83
  |---
8 | 10 --- R: 3  (last digit)
  |---
8 | 1  --- R: 2
  |---
  | 0  --- R: 1  (first digit)

Answer: 123 (octal)
```

**Verification:**
123₈ = (1×64) + (2×8) + (3×1) = 64+16+3 = 83 ✓

---

## 4. HEXADECIMAL NUMBER SYSTEM (Shodashik Paddhati)

**Base/Radix: 16**

**Digits available:** 0-9 aur A-F (total 16 symbols)

```
Decimal:  0  1  2  3  4  5  6  7  8  9  10  11  12  13  14  15
Hexa:     0  1  2  3  4  5  6  7  8  9  A   B   C   D   E   F
```

### Place Value:

```
   16³  |  16²  |  16¹  |  16⁰
  4096  |  256  |  16   |   1
```

**Example 1:** Hexa 2A3 ko decimal mein

```
Position:     2    1    0
Hexa:         2    A    3
Decimal val:  2   10    3
Place value: 16² 16¹  16⁰
            (256)(16)  (1)

= (2 × 16²) + (10 × 16¹) + (3 × 16⁰)
= (2 × 256) + (10 × 16) + (3 × 1)
= 512 + 160 + 3
= 675 (Decimal)
```

**Example 2:** Hexa 1F ko decimal mein

```
= (1 × 16¹) + (15 × 16⁰)
= (1 × 16) + (15 × 1)
= 16 + 15
= 31 (Decimal)
```

### Decimal se Hexadecimal kaise banaye?

**Method: 16 se divide karte raho**

**Example:** 254 ko hexa mein

```
16 | 254
   |----
16 | 15 --- R: 14 (E)  (last digit)
   |----
   | 0  --- R: 15 (F)  (first digit)

Answer: FE (hexadecimal)
```

**Verification:**
FE₁₆ = (15×16) + (14×1) = 240+14 = 254 ✓

---

## CONVERSION TABLE (Quick Reference)

```
Decimal | Binary  | Octal | Hexa
--------|---------|-------|------
   0    |  0000   |   0   |  0
   1    |  0001   |   1   |  1
   2    |  0010   |   2   |  2
   3    |  0011   |   3   |  3
   4    |  0100   |   4   |  4
   5    |  0101   |   5   |  5
   6    |  0110   |   6   |  6
   7    |  0111   |   7   |  7
   8    |  1000   |  10   |  8
   9    |  1001   |  11   |  9
  10    |  1010   |  12   |  A
  11    |  1011   |  13   |  B
  12    |  1100   |  14   |  C
  13    |  1101   |  15   |  D
  14    |  1110   |  16   |  E
  15    |  1111   |  17   |  F
  16    | 10000   |  20   | 10
```

---

## SPECIAL CONVERSIONS

### Binary se Octal (Shortcut):

**3 binary digits = 1 octal digit**

**Example:** Binary 110101 ko octal mein

```
Step 1: Right se 3-3 digits ka group banao
        110  101

Step 2: Har group ko decimal mein convert karo
        110 = (1×4) + (1×2) + (0×1) = 6
        101 = (1×4) + (0×2) + (1×1) = 5

Answer: 65 (Octal)
```

### Binary se Hexadecimal (Shortcut):

**4 binary digits = 1 hexa digit**

**Example:** Binary 11010110 ko hexa mein

```
Step 1: 4-4 digits ka group banao
        1101  0110

Step 2: Convert each group
        1101 = (8+4+0+1) = 13 = D
        0110 = (0+4+2+0) = 6

Answer: D6 (Hexadecimal)
```

---

## Practice Problems (Khud try karo!)

1. **Decimal to Binary:** 45 = ?
2. **Binary to Decimal:** 10110 = ?
3. **Decimal to Octal:** 100 = ?
4. **Octal to Decimal:** 77 = ?
5. **Decimal to Hexa:** 255 = ?
6. **Hexa to Decimal:** ABC = ?

### Answers:
1. 101101
2. 22
3. 144
4. 63
5. FF
6. 2748

---

## Yaad Rakhne Ki Tricks:

1. **Binary:** "Do friends" - Base 2
2. **Octal:** "Aath friends" - Base 8
3. **Decimal:** "Das friends" - Base 10
4. **Hexa:** "Solah friends" - Base 16

**Conversion ka golden rule:** Jis base se convert karna hai, us number se divide karte jao aur remainders collect karte jao!
