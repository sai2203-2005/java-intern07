# Java Internship - Prime Numbers Program

A Java application developed as part of the Java Internship program. This program checks if a given integer is prime and generates all prime numbers within a specified range.

## 🚀 Features

- **Prime Check**: Determines whether a single integer is a prime number using an optimized $O(\sqrt{n})$ trial division algorithm.
- **Range Generation**: Generates and displays all prime numbers between a user-defined start and end range.
- **Interactive CLI**: Easy-to-use console user input via `java.util.Scanner`.

## 📋 Prerequisites

- **Java Development Kit (JDK)**: Version 8 or higher
- **Git** (optional, for cloning)

## 🛠️ How to Build and Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sai2203-2005/java-intern07.git
   cd java-intern07
   ```

2. **Compile the Java file**:
   ```bash
   javac PrimeNumbers.java
   ```

3. **Run the application**:
   ```bash
   java PrimeNumbers
   ```

## 💻 Sample Output

```text
Enter a number to check: 7
7 is a Prime number.

Enter starting range: 1
Enter ending range: 20

Prime numbers between 1 and 20:
2 3 5 7 11 13 17 19 
```

## 📁 Repository Structure

- [`PrimeNumbers.java`](PrimeNumbers.java): Main Java source code containing `isPrime()` logic and `main()` driver execution.
- [`.gitignore`](.gitignore): Configured to ignore compiled `.class` files.
- [`README.md`](README.md): Documentation file.
