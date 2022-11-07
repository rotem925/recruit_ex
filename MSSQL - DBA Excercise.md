# DBA - MSSQL exercise


Dear candidate,
In order to proceed to the next step with us, you will need to succeed in the following exercise.  
Please follow each step bellow and try to do as much as you can. If you're not sure, continue to the next step.  
The goal of this exercise is to understand the way you approach code and to make sure you have the relevant experience.  


Please use any public git repository(github is perfect for that), so that we can follow your commits and review the code.
Once done, you will need to send us a link to your public repository(make sure it is public) for a review.
We will get back to you as soon as possible with an answer.

Thank you for taking this exercise, it is much appericiated!  

**Best of luck!**


## Tools needed:

* MSSQL Management Studio
* Git
* Sql Server Express for LocalDB testing

## Mission: 

1. Create a script for creating a users table with the following columns: UserID, LoginName(unique), FirstName, LastName, EmailAddress(unique), CreatedAt, IsActive
2. Create a script for creating the books table with the following columns: BookID, BookTitle
3. Create a relationship table where users might have multiple books, but not the same book twice.
4. Create a procedure named: usp_find_user_email_by_login (@loginName) which will select a table containing only the userId and emailAddress which are active. **Make sure you have the appropiate indexes for that query.**
5. Create a view named uv_userBooks that will select: UserID,FirstName,LastName,BookID,BookTitle
6. Create a procedure named usp_user_book_count that will select a UserID,NumOfBooks. **Make sure you have the appropiate indexes for that query.**
7. Create a partition table for the Users table with it's indexes. The partition function should use the CreatedAt field to determine the partition (Use any value you desire).
8. Create a rebuild index script for each of the created indexes as a maintenance script.


# GOOD LUCK 
