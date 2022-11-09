# ASP.NET MVC Exercise 

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

* Windows
* Git
* Visual Studio
* Sql Server Express for LocalDB

## Mission: 
1. Create a new ASP.NET(.net framework) MVC application project - you can use Microsoft default new website template.
2. Add dependency injection to the newly created project (You can choose Autofac, or anything else you fimiliar with).
3. Create another Class Library project and add it to the solution.
4. Add EntityFramework6 to the class library project and configure it to use any LocalDb/SQL Server connection string.
5. Configure EntityFramework with Code First pattern - Configure a DbContext instance.
6. Create an interface called IUserService with an implementation of a UserService class.
7. Configure ASP.NET to inject the newly created IUserService and the DbContext.
9. Define a Code First table for our User class as bellow (add any annotation or modify as required):

	```csharp 
		public class User
		{
			public int ID{get;set;}
			public string FirstName{get;set;}
			public string LastName{get;set;}
		}
	```
10. In the UserService class, define the following methods and implement them using entity framework.
	* List<User> GetAllUsers()
	* <User> AddUser(firstName,lastName)
	* void DeleteUser(userId)
	* EditUser(userId,firstName,lastName)	
11. Create a new MVC page called users in order to display a list of users inside an html table.
12. Style the table with CSS3 as you whish.
13. Add some CRUD operations to that table, Add new user,Edit a user, Delete a user. **Make sure the CRUD operations are used with Ajax requests and jQuery/boostrap.**


# GOOD LUCK 
