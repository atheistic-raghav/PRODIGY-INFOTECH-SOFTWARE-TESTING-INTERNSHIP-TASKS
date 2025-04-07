# sCalc Test Cases

## TC01 – Adding Two Numbers
**Preconditions:**  
- sCalc app is open in the browser (https://dunizb.github.io/sCalc/index.html)  
- Display shows "0"

**Steps:**  
1. Tap `2`  
2. Tap `＋`  
3. Tap `3`  
4. Tap `＝`

**Expected Result:**  
Display shows `5`

---

## TC02 – Subtracting Two Numbers
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `8`  
2. Tap `－`  
3. Tap `5`  
4. Tap `＝`

**Expected Result:**  
Display shows `3`

---

## TC03 – Multiplying Two Numbers
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `4`  
2. Tap `×`  
3. Tap `6`  
4. Tap `＝`

**Expected Result:**  
Display shows `24`

---

## TC04 – Dividing Two Numbers
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `9`  
2. Tap `÷`  
3. Tap `3`  
4. Tap `＝`

**Expected Result:**  
Display shows `3`

---

## TC05 – Immediate Execution (No Operator Precedence)
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `2`  
2. Tap `＋`  
3. Tap `3`  
4. Tap `×`  
5. Tap `4`  
6. Tap `＝`

**Expected Result:**  
Display shows `20`  
*(First 2 + 3 = 5, then 5 × 4)*

---

## TC06 – Chaining Operations Without Equals
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `5`  
2. Tap `＋`  
3. Tap `2`  
4. Tap `×`  
5. Tap `3`  
6. Tap `＝`

**Expected Result:**  
Display shows `21`  
*(5 + 2 = 7, then 7 × 3)*

---

## TC07 – Decimal Addition
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `3`, then `.`, then `2`  
2. Tap `＋`  
3. Tap `0`, then `.`, then `8`  
4. Tap `＝`

**Expected Result:**  
Display shows `4`

---

## TC08 – Leading Decimal Input
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `.`, then `5`  
2. Tap `＋`  
3. Tap `.`, then `2`  
4. Tap `＝`

**Expected Result:**  
Display shows `0.7`

---

## TC09 – Negative Number Addition
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `－`, then `5`  
2. Tap `＋`  
3. Tap `3`  
4. Tap `＝`

**Expected Result:**  
Display shows `-2`

---

## TC10 – Division by Zero
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `5`  
2. Tap `÷`  
3. Tap `0`  
4. Tap `＝`

**Expected Result:**  
Display shows `Infinity` or an appropriate `Error` message

---

## TC11 – Multiple Decimal Input
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `5`, then `.`, then `2`, then `.`, then `3`

**Expected Result:**  
Second `.` is ignored; display shows `5.23`

---

## TC12 – Equals Without Operation
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `7`  
2. Tap `＝`

**Expected Result:**  
Display remains `7`

---

## TC13 – Clear Entry (CE) Functionality
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `2`, then `＋`, then `3`  
2. Tap `CE`  
3. Tap `4`  
4. Tap `＝`

**Expected Result:**  
Display shows `4`

---

## TC14 – Backspace (←) Functionality
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `1`, then `2`, then `3`  
2. Tap `←` → should show `12`  
3. Tap `←` → should show `1`  
4. Tap `←` → should show `0`

---

## TC15 – Modulo (%) Functionality
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap `5`, then `0`  
2. Tap `%`  
3. Tap `3`  
4. Tap `＝`

**Expected Result:**  
Display shows `2`  
*(50 % 3 = 2)*

---

## TC16 – Theme Toggle (Light/Dark Mode)
**Preconditions:**  
- Display shows "0" in light theme

**Steps:**  
1. Tap the **theme toggle icon**

**Expected Result:**  
UI switches to dark theme (navigates to the dark‑theme page; functionality remains intact)

---

## TC17 – Cancel (Close) Icon
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap the **Cancel (✖)** icon

**Expected Result:**  
Calculator window slides down and disappears (app hides)

---

## TC18 – Full-Screen (Maximize) Icon
**Preconditions:**  
- Display shows "0"

**Steps:**  
1. Tap the **Full Screen (口)** icon

**Expected Result:**  
Calculator expands to fill the browser viewport; tapping again restores original size

---

## TC19 – Dark-Theme Functionality
**Preconditions:**  
- Calculator is in dark theme

**Steps:**  
1. Tap `2`  
2. Tap `＋`  
3. Tap `2`  
4. Tap `＝`

**Expected Result:**  
Display shows `4` (operations work normally in dark mode)

---

## TC20 – One-Hand Mode Toggle
**Preconditions:**  
- Display shows "0" in standard layout

**Steps:**  
1. Swipe the calculator panel left  
2. Swipe the calculator panel right

**Expected Result:**  
Layout shifts to left-hand mode, then shifts back to right-hand mode
