# WebAPI1Project

This is a simple CRUD app made using Code first approach where we don't create table manually. Instead we write class and then run some commands ( here we are using Entity FrameWork Core as ORM) to generate the tables.

These are the different API Endpoints which we have created to Create, Read, Delete and Update data from Student Database.

![image](https://github.com/mrinmay7875/WebAPICrudApp/assets/33797909/ef24e3c5-488f-43e4-b580-dd71f6e1cdbf)


-  `Add-Migration InitialCreate`
-  `Update-Database`

When we run the above two mentioned commands then it creates a DB as "StudentDB" and creates a Table as "Student" inside the table as well.

It creates a DB locally. You can connect to the DB from SSMS
#### 📦Server URL: (localdb)\MSSQLLocalDB
