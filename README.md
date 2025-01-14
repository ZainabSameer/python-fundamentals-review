*Personal Library Manager Lab*
Objective:

Develop a straightforward personal library management application that operates entirely within the terminal. This application will enable users to catalog their books and write brief reviews directly from the command line. Data can be managed using a .csv file for persistent storage or a local object/dictionary for in-memory management. Through this project, you’ll practice using Python, handling user input, and managing data.

Requirements:

Your personal library manager should allow users to:

Main Menu:

When the application starts, display a menu with the following options:

Add a New Book: Users can add a new book to their library.

View All Books: Display a list of all books in the library.

Write a Review: Add a review for a specific book.

Add a New Book:

Collect the following information from the user:

Title: The title of the book.

Author: The author of the book.

Example:

Copy
Title: The Alchemist
Author: Paulo Coelho
View All Books:

Print a list of all books in the library, including the title and author.

Example:

Copy
1. The Alchemist by Paulo Coelho
2. The Little Prince by Antoine de Saint-Exupéry
Write a Review:

Users can write a short review for a book in their library.

Display the review alongside the book details when viewing all books.

Example:

Copy
Title: The Alchemist
Review: "A magical story about following your dreams."
Technical Requirements:

Store all book details in a .csv file.

Store all reviews in a separate .csv file.

Load existing data from the .csv files when the application starts.

Stretch Goals:

Basic Search: Allow users to search for books by title or author.
