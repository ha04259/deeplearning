Programming Assignment: Working with a Virtual Library 💻
Welcome to your first graded assignment! In this assignment, you'll be working with a virtual library system. Don't worry, you won't be actually coding the library. Instead, you'll be using your Python skills to interact with some pre-defined library information.

Before you begin 🚦
If you need a fresh copy of the assignment (reset), follow the provided instructions.

INSTRUCTIONS FOR ATTEMPTING THE ASSIGNMENT:
Before starting each exercise, read the instructions carefully. Look for the part called Your Task, it tells you exactly what you need to code and gives you all the details you need.
In each exercise cell, look for comments ### START CODE HERE ### and ### END CODE HERE ###. These show you where to write your code. Do not add or change any code that is outside these comments, or add any extra code cells in the notebook.
After you finish coding an exercise, there will be a test section that checks your work using a function called test_your_code. If everything is correct, you'll see a message saying "All tests passed!" and you can move on. If there's a mistake, you'll see a red message explaining what went wrong, so you can fix it.
Before submitting your notebook for grading, ensure ALL exercises are complete (gotten All tests passed! for all of them). Save your work by clicking the 💾 icon at the top left, then click the Submit assignment button at the top right.
ASKING FOR HELP IN THE COMMUNITY FORUM:
Sign up for our Community Forum if you haven't already. Once signed up, post your questions in the AP4B category with detailed information, such as the item's name, exercise number, or code cell. This helps others understand your issue better. Share screenshots if you can, but don't post solution code publicly; instead, share the error message you receive.
With that out of the way, let's begin!

Table of Exercises
Exercise 1: Book Information ℹ️
Exercise 1-A: Defining Variables
Exercise 1-B: Print Statements
Exercise 2: Checking Out a Book 📖
Exercise 3: Book Request 📚
Assignment Starts From Here
Before starting the assignment, run the cell below. It will bring in some helpful code to check if your solutions are correct and provide feedback if you need to make changes. You'll learn more about how this works as you progress through the course.

IMPORTANT NOTE: Always run this cell when starting or resuming your assignment. DO NOT include it in any other notebook cells.

import test_your_code

Exercise 1: Book Information ℹ️
Let's assume the library has the following books and their information:

Book Title	Author	Year Published	Available Copies
The Lord of the Rings	J.R.R. Tolkien	1954	2
Brave New World	Aldous Huxley	1932	4
The Hitchhiker's Guide to the Galaxy	Douglas Adams	1979	5
Pride and Prejudice	Jane Austen	1813	1
To Kill a Mockingbird	Harper Lee	1960	0

Exercise 1-A: Defining Variables
One of the books available in your virtual library is:

Book Title	Author	Year Published	Available Copies
Brave New World	Aldous Huxley	1932	4
Your Task:

Store the information of this book into Python variables book_title, author, year_published and available_copies

### START CODE HERE ###
​
# Store the title of the book `Brave New World` as a string
book_title = # Add your code here
​
# Store the author `Aldous Huxley` of the book as a string
# Add your code here
​
# Store the year `1932` the book was published as an integer
# Add your code here
​
# Store the number of available copies `4` of the book as an integer
# Add your code here
​
### END CODE HERE ###
Run the next cell to check if your code is correct. In case you receive an error please make sure you defined the required variables with the correct names.

# Test your code!
test_your_code.exercise_1a(book_title, author, year_published, available_copies)
Important Note: If you see All tests passed!, you can proceed to the next step. If there's an error message in red, follow the instructions to fix it, then re-run the exercise and test cells until you get the All tests passed! message. Repeat this process for all exercises in the assignment.


Exercise 1-B: Print Statements
Your Task:

Write a Python program using f-string that uses the above variables (book_title, author, year_published and available_copies) to print information about the book in the following format:

Title: <Book Title>
Author: <Author>
Published: <Year Published>
Available Copies: <Available Copies>
Make sure to use a separate print statement for every variable!

### START CODE HERE ###
​
# Print the Title: `book_title` using an f-string
print(f"Title: {# Add your code here}")
​
# Print the Author: `author` using an f-string
# Add your code here
​
# Print Published: `year_published` using an f-string
# Add your code here
​
# Print Available Copies: `available_copies` using an f-string
# Add your code here
​
### END CODE HERE ###
Expected Output:
Title: Brave New World
Author: Aldous Huxley
Published: 1932
Available Copies: 4
# Test your code!
test_your_code.exercise_1b()

Exercise 2: Checking Out a Book 📖
Now, let's imagine an user wants to check out the book "Brave New World".

Your Task:

Write a program that:

Reduces the number of available_copies by 1 (representing a book being checked out).
The current available_copies for the book "Brave New World" are 4.
Hint (Click here to open)
Prints a message confirming the checkout, including the book title (book_title) and the remaining available copies (available_copies).
The printed message should be in the format using multi-line f-string as, One copy of <Book Title> checked out. There are now <Available Copies> copies available.
available_copies = 4 ### DO NOT EDIT OR REMOVE THIS CODE LINE
​
### START CODE HERE ###
​
# 1. Reduce the number of "available_copies" by a value of 1
available_copies = # Add your code here
​
# 2. Print the message, confirming the checkout. Use multi-line f-string
# In your print statment, use "book_title" you implemented in exercise 1
# Use "available_copies" you calculated above
print(f"""
# Add your code here
""")
​
### END CODE HERE ###
Expected Output:
One copy of Brave New World checked out. There are now 3 copies available.
# Test your code!
test_your_code.exercise_2(available_copies)  

Exercise 3: Book Request 📚
An user wants to borrow "To Kill a Mockingbird". However, there are no copies currently available.

Book Title	Author	Year Published	Available Copies
To Kill a Mockingbird	Harper Lee	1960	0
Your Task:

Write Python code that:

Stores the name of the requested book in a variable called requested_book.
Prints a message telling the user that the book is currently unavailable, but they can request it.
The printed message should be in the format using multi-line f-string as, <Requested Book> is currently unavailable. You can request it from the library.
### START CODE HERE ###
​
# 1. Store the name of the book `To Kill a Mockingbird` in a variable called `requested_book`
# Add your code here
​
# 2. Print the message using multi-line f-string
# Add your code here
​
### END CODE HERE ###
Expected Output:
To Kill a Mockingbird is currently unavailable. You can request it from the library.
# Test your code!
test_your_code.exercise_3(requested_book)  
Submission Note:
If you have passed all the tests up to this point, you can submit your assignment for grading.

But before you submit your assignment, re-run the assignment just in case there are any unexpected errors present in the notebook once it goes for grading. To do so, follow these steps:

Restart the Kernel and select the Restart & Clear Output option. You can do this by clicking on the Kernel menu at the top of the notebook.Kernel Restart Image
Once the kernel restarts and all outputs are clear, run the cells from top to bottom again up to this point.
If you have followed these steps and still pass all of the tests, you can submit your assignment for grading. If you encounter any errors, please fix them before submitting.

To submit your assignment for grading, save your work by clicking the 💾 icon at the top left, then click the Submit assignment button at the top right. Good luck!

🎉 Congratulations on completing your first programming assignment! 🎉

You've taken a significant step on your journey to becoming a skilled programmer. Your dedication and hard work have paid off, and you should be proud of what you've accomplished. 💪

Remember, every line of code you write brings you closer to mastering this valuable skill. Keep pushing forward, stay curious, and continue to explore the endless possibilities that programming offers. 🚀

This is just the beginning, and there are many more exciting challenges ahead. We encourage you to keep up the momentum and continue through the course 👩‍💻👨‍💻
