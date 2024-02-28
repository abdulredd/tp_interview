# TP Tech Interview

## Lucky Numbers

Given an `m x n matrix` of distinct numbers, create a method that will intake 2-dimension array (matrix) and returns all lucky numbers in the matrix in any order.

> A lucky number is an element of the matrix such that it is the minimum element in its row and maximum in its column.

**Example 1:**

- Input: matrix = [[3,7,8],[9,11,13],[15,16,17]]
- Output: [15]
  - (15 is the only lucky number since it is the minimum in its row and the maximum in its column.)

**Example 2:**

- Input: matrix = [[1,10,4,2],[9,3,8,7],[15,16,17,12]]
- Output: [12]
  - (12 is the only lucky number since it is the minimum in its row and the maximum in its column.)

**Example 3:**

- Input: matrix = [[7,8],[1,2]]
- Output: [7]
  - (7 is the only lucky number since it is the minimum in its row and the maximum in its column.)

<br>

---

---

## Valid Parentheses

Given a string `s` containing just the characters `"("`, `")"`, `"{"`, `"}"`, `"["` and `"]"`, create a method that will intake a set of brackets as a string and determine if the brackets are well-formed (match). Note: Brackets can be nested.

> Open brackets must be closed by the same type of brackets.

> Open brackets must be closed in the correct order.

> Every close bracket has a corresponding open bracket of the same type.

**Example 1:**

- Input: s = "()"
- Output: true

**Example 2:**

- Input: s = "()[]{}"
- Output: true

**Example 3:**

- Input: s = "({[]}{[]})"
- Output: true

**Example 4:**

- Input: s = "(]"
- Output: false

**Example 5:**

- Input: s = "{[)][]}"
- Output: false

**Example 6:**

- Input: s = "]"
- Output: false

**Example 7:**

- Input: s = "["
- Output: false

<br>

---

---

## Pyramid Array

Given a 1-dimensional array, create a method that takes in an array of numbers representing the base of a pyramid. The function should return a 2-dimensional array (matrix) representing the completed pyramid. To generate an element of the next level of the pyramid, we sum the elements below and to the left and below and to the right.

**Example 1:**

- Input: array = [2, 3, 7, 5, 9]
- Output: [
           [ 85 ],
           [ 37, 48 ],
           [ 15, 22, 26 ],
           [ 5, 10, 12, 14 ],
           [ 2, 3, 7, 5, 9 ]
          ]

**Example 2:**

- Input: array = [2, 2, 2, 2]
- Output: [
           [ 16 ],
           [ 8, 8 ],
           [ 4, 4, 4 ],
           [ 2, 2, 2, 2 ]
          ]

<br>

---

---

## Spiral Matrix

Given an `m x n matrix`, return all elements of the `matrix` in spiral order, create a method that will intake a 2-dimensional array (matrix) and return a 1-dimensional array containing all elements of the `matrix` in spiral order.

**Example 1:**

![alt text](image.png)

- Input: matrix = [[1,2,3],[4,5,6],[7,8,9]]
- Output: [1,2,3,6,9,8,7,4,5]

**Example 2:**

![alt text](image-1.png)

- Input: matrix = [[1,2,3,4],[5,6,7,8],[9,10,11,12]]
- Output: [1,2,3,4,8,12,11,10,9,5,6,7]
