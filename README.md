# What are the Repository and Unit of Work Patterns?
According to the official MS Docs, repositories are classes or components that encapsulate the logic required to access data sources. 
They include methods for common operations, providing better decoupling and maintainability.
The Unit of Work pattern is used to aggregate multiple operations into a single transaction. 
With this we ensure that either all operations succeed or fail as a single unit.

# DbContext
DbContext class is a combination of the Unit of Work and Repository patterns, where the DbContext is an abstraction of the Unit of Work pattern and a DbSet is an abstraction of the Repository pattern.
+ Link to article: https://www.linkedin.com/pulse/repository-unit-work-patterns-net-core-dimitar-iliev/
+ Implement DbContext with UoW and Transaction: https://dotnettutorials.net/lesson/unit-of-work-csharp-mvc/
+ https://www.c-sharpcorner.com/article/repository-and-unitofwork-pattern-part-1/
+ https://www.c-sharpcorner.com/article/repository-and-unitofwork-pattern-part-2/
+ https://www.c-sharpcorner.com/article/repository-and-unitofwork-pattern-part-three/
+ https://enlabsoftware.com/development/how-to-implement-repository-unit-of-work-design-patterns-in-dot-net-core-practical-examples-part-one.html
+ https://enlabsoftware.com/development/how-to-implement-repository-unit-of-work-design-patterns-in-dot-net-core-practical-examples-part-two.html
+ https://codewithmukesh.com/blog/repository-pattern-in-aspnet-core/

# Getting Started
+ Startup project: UnitOfWorkRepositoryPatterns
+ Visual Studio -> Tools -> Package Manager Console -> Update-Database

# Add more features
+ Import from csv using CSVHelper: https://www.syncfusion.com/blogs/post/handling-csv-files-in-asp-net-core-web-apis.aspx
+ Import from csv using CSVHelper: https://code-maze.com/csharp-read-data-from-csv-file/
