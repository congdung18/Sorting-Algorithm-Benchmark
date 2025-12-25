# Sorting Algorithms Benchmark (C++)

A C++ project that benchmarks **classical and advanced sorting algorithms**, measuring **execution time** and **number of comparisons** across multiple data distributions and input sizes.

---

## ✨ Features
- Implement and benchmark multiple sorting algorithms:
  - Selection Sort
  - Insertion Sort
  - Bubble Sort
  - Shell Sort
  - Heap Sort
  - Merge Sort
  - Quick Sort (median-of-three, Lomuto partition, Hoare partition)
  - Radix Sort
  - Flash Sort
- Compare performance on different data distributions:
  - Random
  - Sorted
  - Reversed
- Measure:
  - Execution time using `std::chrono`
  - Number of comparisons
- Structured result output for easy analysis and reporting

---

## 🛠️ Core Concepts
- Sorting algorithms and complexity analysis
- Empirical performance benchmarking
- Time measurement with `std::chrono`
- Algorithm optimization techniques
- Clean separation of logic and measurement

---

## 📊 Benchmark Configuration
- Input sizes: **1,000 → 30,000 elements**
- Data types:
  - Random
  - Already sorted
  - Reverse sorted
- Metrics:
  - Time (milliseconds)
  - Comparison count

---

## 🚀 How to Use
1. Clone or pull the project to your local machine
2. Compile and run the benchmark program
3. The program will output benchmark results to files / console
4. Each run produces consistent, comparable results across algorithms

Example console output:
```text
Benchmark completed successfully
```

## 📂 File Structure
```text
├── sorting_algorithms.hpp
├── sorting_algorithms.cpp
├── benchmark.cpp
├── data_generator.cpp
├── main.cpp
```

### 📄 File Description
**headers.hpp:** Declarations of all libraries used and functions involved.

**implement.cpp:** 
Implementations of sorting algorithms, including:

- Quick Sort with median-of-three pivot selection

- Lomuto partition scheme

- Radix and Flash Sort implementations

Generates input arrays:

- Random

- Sorted

- Reversed


Handles:

- Timing using std::chrono

- Comparison counting

- Result aggregation and formatting

**main.cpp:**
Entry point of the program.
Runs benchmarks and prints or saves results.