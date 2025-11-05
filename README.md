1.📚 Library Search System

A simple Java project that demonstrates the use of **Binary Search** to locate a book by its ISBN number in a digital library. This is a practical example of how binary search can be used in backend systems for fast data retrieval.

---

## 🚀 Features

- Efficient search for books using ISBN
- Binary Search implementation with O(log n) time complexity
- Clean and readable Java code
- Console-based output for quick testing

---

## 🧠 How It Works

The system assumes a **sorted array of ISBN numbers**. When a user inputs a target ISBN, the program uses binary search to find the book's index in the array.

```java
2. 📚 Application: Sorting Book Titles Alphabetically with Merge Sort
✨ Features
- ✅ Sorts book titles in alphabetical order
- ✅ Handles both uppercase and lowercase titles correctly
- ✅ Efficient for large lists of titles
- ✅ Preserves the original order of equal titles (stable sort)
- ✅ Easy to integrate into library systems, bookstore apps, or reading list managers

⚙️ How It Works (in short)
- The list of book titles is recursively divided into smaller halves.
- Each half is sorted individually.
- The sorted halves are then merged together in order.
- Comparison is done using compareToIgnoreCase() to ensure case-insensitive sorting.
Merge Sort is ideal here because it guarantees O(n log n) performance and maintains stability, which is important when sorting titles with similar names.
Would you like a visual diagram of how the sorting happens step-by-step?
