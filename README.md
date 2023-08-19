# CS255
System Analysis &amp; Design


# Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The DriverPass project was a project by the by the client, DriverPass, who wanted a system that made it easier for people to take online tests as well as schedule on-the-road tests to better their driving skills.

# What did you do particularly well?

I feel I completed the activity diagrams for some of the use cases in the use case diagram particularly well.  I felt good about the amount of detail I provided in the diagrams to showcase the more nitty-gritty information about a particular process and what happens behind the scenes.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

One of the documents I feel I could further revise is my class diagram I created for the system.  I believe that this document could better showcase the functionality available to the different classes in the system and what else they are able to do as well as the other attributes that I feel they still need to function properly.

# How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

When looking at the interview transcript, I was able to split up the requirements from the client based on what part of the system that requirement was needed.  One such requirement is the need for different users to have different access.  The client mentions in the transcript that users will have basic functionality, whereas admins such as the secretary, system admin, etc. will be able to add and modify items in the database.  Due to this I felt it would be best to create a parent class, "User", that had attributes and functions available to it that would be needed in all child classes.  Two of the main child classes are the "Student" and the "Admin", which when relating to roles, if a user is accessing something only an admin should, the system should check to make sure the user is of actor type, "Admin".

# How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

For me, the best approach was to take the needs of the client and create a requirements document.  This helps to know what functionality is going to be needed of those accessing the system as well as non-functional requirements that will be needed later such as hardware needs.  Using the functional requirements list, I felt the class diagram is a great diagram to create to understand the different actors of the system as well as how they interact with each other.  However, all of the diagrams created were very useful to show different types of information to help give an idea of how certain elements should function.
