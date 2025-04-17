# Memoization_intuition_backpropagation
Memoization is a key concept in deep learning, especially in backpropagation, for optimizing computations. This repository illustrates this through a Fibonacci recursion example, comparing a naive approach (no memoization) with an efficient memoized version

- `fib_no_memo.py`: A classic recursive version without memoization. Time complexity: O(2^n).
- `fib_with_memo.py`: An optimized recursive version with memoization using a dictionary. Time complexity: O(n).

Both include timing with `time` module to compare performance.

## Usage
Run each file with Python:
```bash
python fib_no_memo.py
python fib_with_memo.py

