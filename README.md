<!-- DECISION.ALGO -->

### Example

- Input: `age = 8`
  - Output: `10`
- Input: `age = 16`
  - Output: `15`
- Input: `age = 25`
  - Output: `20`

## 2. Clothing Advice

### Description

This algorithm provides clothing advice based on the temperature and whether it is raining. It gives recommendations for appropriate clothing and whether to take an umbrella.

### Algorithm

1. **Read** the current temperature and whether it is raining.
2. **Determine** the clothing and umbrella advice based on the weather conditions:
   - If it is raining:
     - Temperature less than 10°C: Wear a warm coat and take an umbrella.
     - Temperature between 10°C and 20°C: Wear a jacket and take an umbrella.
     - Temperature 20°C or above: Wear light clothing and take an umbrella.
   - If it is not raining:
     - Temperature less than 10°C: Wear a warm coat.
     - Temperature between 10°C and 20°C: Wear a jacket.
     - Temperature 20°C or above: Wear light clothing.
3. **Output** the clothing advice.

### Pseudocode

recursion.algo

# Fibonacci and Power Functions

## 1. Fibonacci Function

### Description

This function computes the nth Fibonacci number using recursion. The Fibonacci sequence is defined as:

- F(0) = 0
- F(1) = 1
- F(n) = F(n-1) + F(n-2) for n > 1

### Algorithm

1. **Check** if `n` is 0 or 1. If so, return the corresponding Fibonacci number (0 or 1).
2. **Recursively** calculate `fibonacci(n - 1)` and `fibonacci(n - 2)` and return their sum.

### Pseudocod
