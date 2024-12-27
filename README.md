# Insertion Sort Implementation

This repository contains the implementation of the **Insertion Sort** algorithm, a simple and intuitive sorting technique suitable for small datasets or partially sorted arrays.

## Overview
Insertion Sort is an efficient sorting algorithm with the following key characteristics:

- **Time Complexity:**
  - Best Case: O(n)
  - Average Case: O(n^2)
  - Worst Case: O(n^2)
- **Space Complexity:** O(1) (in-place sorting)
- **Algorithm Type:** Comparison-based, stable

## Features
- Implemented in **C++**.
- Supports sorting arrays/lists of integers, floats, or other comparable data types.

## File Structure
- `InsertionSort.cpp`: Contains the implementation of Insertion Sort.
- `README.md`: Documentation for the repository.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/insertion-sort.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd insertion-sort
   ```
3. Compile the code:
   ```bash
   g++ -o insertion_sort InsertionSort.cpp
   ```
4. Run the executable:
   ```bash
   ./insertion_sort
   ```

## Algorithm Steps
1. Start with the second element as the current element.
2. Compare the current element with the elements before it.
3. Shift larger elements one position to the right.
4. Insert the current element into its correct position.
5. Repeat steps 2-4 for all elements in the array.

## Example Input and Output
### Input
```plaintext
Array: [4, 10, 3, 5, 1]
```
### Output
```plaintext
Sorted Array: [1, 3, 4, 5, 10]
```

## Contributing
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## About Me
I am Abdallah Naser, a backend developer, frontend developer using React.js, and a skilled WordPress Designer/Developer with extensive experience in creating and customizing websites using WordPress, Elementor, and WooCommerce.

---

For any questions or feedback, please feel free to contact me!
