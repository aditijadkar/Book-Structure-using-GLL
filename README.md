Book Structure Management Using Generalized Linked List
-------------------------------------------------------------
This C++ program manages a hierarchical structure of a book using a Generalized Linked List (GLL). 

The hierarchical structure consists of books, chapters, sections, and subsections. 

The program provides functionalities to insert and display these elements within the hierarchical structure.

Features:
------------------
Insert Book: Adds a new book to the system. If a book already exists, it informs the user.

Insert Chapter: Adds chapters to an existing book. If no book exists, it prompts the user accordingly.

Insert Section: Adds sections to a specified chapter within a book.

Insert Subsection: Adds subsections to a specified section within a chapter.

Display Book: Displays the hierarchical structure of the book, including chapters, sections, and subsections.

How It Works:
------------------------
Data Structure:
----------------------
The program uses a node struct to represent each element (book, chapter, section, subsection). Each node contains:

name: The name of the element.

next: Pointer to the next node at the same level (e.g., next chapter).

down: Pointer to the next level of nodes (e.g., sections under a chapter).

flag: Indicates if there are any child nodes (e.g., chapters in a book).

Functions:
-------------------
create(): Creates a new node with user-provided data.

insertb(): Inserts a book into the system.

insertc(): Inserts chapters into a book.

inserts(): Inserts sections into a chapter.

insertss(): Inserts subsections into a section.

displayb(): Displays the entire hierarchical structure of the book.

Example:
--------------
Insert a book by selecting option 1.

Add chapters to the book using option 2.

Add sections to chapters using option 3.

Add subsections to sections using option 4.

Display the entire book structure with option 5.

