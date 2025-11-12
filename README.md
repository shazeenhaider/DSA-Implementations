# DSA-Implementations
🏛️ Library Catalogue System – DSA Mini Project
🎯 Objective

To design a simple library catalogue system that stores book records and allows users to:
Add new books
Display all books
Search books (by title or author)
Sort books (by title, author, or ID)
This project demonstrates the use of arrays / structures, searching algorithms (Linear / Binary Search), and sorting algorithms (Bubble / Selection / Insertion / Quick Sort).


---

🧱 Data Structure Used

struct Book {
    int id;
    char title[100];
    char author[100];
    float price;
};

You can store all books in an array of structures, for example:

struct Book library[100];
int count = 0;


---

⚙️ Main Functionalities

1. Add Book
User inputs book details and adds them to the array.


2. Display Books
Displays all the book records in tabular form.


3. Search Book
Linear Search: search by title or author.
Binary Search: when data is sorted by title.


4. Sort Books
Sort by Title / Author / ID using any sorting algorithm (Bubble Sort, Selection Sort, etc.)

5. Exit
End the program.
---

🧠 Algorithmic Concepts Used

Task	Algorithm Used	Complexity

Searching	Linear / Binary Search	O(n) / O(log n)
Sorting	Bubble / Selection / Quick Sort	O(n²) / O(n log n)
Data Storage	Array of Structures	O(n)
