# Test Cases for Simple Calculator Application

## **Test Case 1: Addition of Two Positive Numbers**
**Test Case ID:** TC_001  
**Test Description:** Verify that the calculator correctly adds two positive numbers.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `5` in the first input field.  
2. Enter `3` in the second input field.  
3. Click the `+` (addition) button.  
4. Click the `=` button.  
**Expected Result:** The result should be `8`.

---

## **Test Case 2: Subtraction of a Larger Number from a Smaller Number**
**Test Case ID:** TC_002  
**Test Description:** Verify that the calculator correctly handles subtraction when a smaller number is subtracted from a larger number.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `3` in the first input field.  
2. Enter `5` in the second input field.  
3. Click the `-` (subtraction) button.  
4. Click the `=` button.  
**Expected Result:** The result should be `-2`.

---

## **Test Case 3: Multiplication of a Positive and a Negative Number**
**Test Case ID:** TC_003  
**Test Description:** Verify that the calculator correctly multiplies a positive and a negative number.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `6` in the first input field.  
2. Enter `-2` in the second input field.  
3. Click the `*` (multiplication) button.  
4. Click the `=` button.  
**Expected Result:** The result should be `-12`.

---

## **Test Case 4: Division by Zero**
**Test Case ID:** TC_004  
**Test Description:** Verify that the calculator handles division by zero appropriately.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `10` in the first input field.  
2. Enter `0` in the second input field.  
3. Click the `/` (division) button.  
4. Click the `=` button.  
**Expected Result:** The calculator should display an error message or `Infinity`.

---

## **Test Case 5: Handling of Decimal Numbers**
**Test Case ID:** TC_005  
**Test Description:** Verify that the calculator correctly handles decimal numbers.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `2.5` in the first input field.  
2. Enter `1.5` in the second input field.  
3. Click on the `+` (addition) button.  
4. Click the `=` button.  
**Expected Result:** The result should be `4.0`.

---

## **Test Case 6: Handling Negative Numbers**
**Test Case ID:** TC_006  
**Test Description:** Verify that the calculator correctly handles negative numbers as inputs.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `-4` in the first input field.  
2. Enter `2` in the second input field.  
3. Click the `+` (addition) button.  
4. Click the `=` button.  
**Expected Result:** The result should be `-2`.

---

## **Test Case 7: Verification of BODMAS Rule**
**Test Case ID:** TC_007  
**Test Description:** Verify that the calculator correctly follows the BODMAS rule.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter the expression: `2 + 3 * 4` in the input field.  
2. Click the `=` button.  
**Expected Result:** The result should be `14` (since multiplication is performed before addition).  

---

## **Test Case 8: Brackets in Expressions (BODMAS Rule)**
**Test Case ID:** TC_008  
**Test Description:** Verify that the calculator correctly evaluates expressions with brackets.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `(2 + 3) * 4` in the input field.  
2. Click the `=` button.  
**Expected Result:** The result should be `20` (since the bracketed sum is evaluated first, resulting in `5 * 4 = 20`).

---

## **Test Case 9: Order of Operations with Exponents (BODMAS Rule)**
**Test Case ID:** TC_009  
**Test Description:** Verify that the calculator correctly handles exponentiation in expressions.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `2 + 3^2 * 4` in the input field.  
2. Click the `=` button.  
**Expected Result:** The result should be `38` (since exponentiation is performed first, resulting in `2 + 9 * 4 = 38`).

---

## **Test Case 10: Non-Numeric Input Handling**
**Test Case ID:** TC_010  
**Test Description:** Verify that the calculator does not accept non-numeric characters.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `A` in the first input field.  
2. Enter `5` in the second input field.  
3. Click on any operation button (`+`, `-`, `*`, `/`).  
4. Click the `=` button.  
**Expected Result:** The calculator should display an error message or prevent non-numeric input.

---

## **Test Case 11: Multiple Decimal Points in Input**
**Test Case ID:** TC_011  
**Test Description:** Verify that the calculator does not allow multiple decimal points in a number.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `5.4.2` in the first input field.  
2. Click on any operation button (`+`, `-`, `*`, `/`).  
3. Enter another number in the second input field.  
4. Click the `=` button.  
**Expected Result:** The calculator should display an error message or ignore extra decimal points.

---

## **Test Case 12: Large Number Input Handling**
**Test Case ID:** TC_012  
**Test Description:** Verify that the calculator can handle large number inputs without crashing.  
**Preconditions:** The calculator should be open.  
**Test Steps:**  
1. Enter `9999999999999` in the first input field.  
2. Enter `9999999999999` in the second input field.  
3. Click the `+` (addition) button.  
4. Click the `=` button.  
**Expected Result:** The calculator should return the correct result or an appropriate error message if it exceeds the limit.

 

 
