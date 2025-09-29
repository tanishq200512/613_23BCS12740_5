# 613_23BCS12740_5
You are developing a basic Library Management System to keep track of books. Each book has 
an ID, title (represented using numeric code), and availability status. The system allows you to 
display book 
details and check books in and out. Use inheritance to extend a base Libraryltem class. 
Create a superclass Libraryltem with the following attributes: 
itemid (int) 
titleCode (int) (a number that represents the book title) 
available (boolean) 
Then create a subclass Book that extends Libraryltem and includes methods to: 
Display book details 
Check out a book (mark unavailable) 
Return a book (mark available) Input Format 
An integer representing the Book ID (itemid) 
An integer representing the Title Code (titleCode) 
An integer representing Availability (1 available, O not available) 
One or more integers representing operations (each on a new line or space-separated): 
1- Check out 
2- Return 
3 Display Details 
Note: The input terminates when no more integers are available (EOF). 
Output Format 
After each operation, output as follows: 
For Checkout: 
If book is available: "Book Checked Out Successfully." 
If already checked out: "Already checked out." 
For Return: 
If book is not available: "Book Returned Successfully." 
If already available: "Already available." 
For Display: 
. Book ID: 
. Title Code: 
. Available: <true/false> 
For any invalid operation: "Invalid operation." 
Constraints 
itemld > O 
titleCode > 0 
availability is either 1 (true) or O (false) 
Operation codes must be integers among {1, 2, 3} 
All inputs are integers only 
Maximum of 100 operations can be assumed for normal usage 
Sample Test Case 1 
Input: 
1001 
501 
1 
1 
3 
Output: 
Book Checked Out Successfully. 
Book ID: 1001 
Title Code: 501 
Available: false 
 
Explanation: 
The book with ID 1001 and title code 501 was initially available. 
After performing a checkout, it became unavailable. 
Then, the display operation showed the updated details with availability marked as false.
