PART 1
2024-01-11
1415
installation of Microsoft Visual Studio and ASP.NET web app

2024-01-11
1130 
I did steps of first part , change title from welcome to hello world and also 
add a picture of smile face. I found this step very interesting. 

PART 2
2024-01-12
0215
add a controller to an ASP.NET web app by following the steps on the visual studio app web application .

PART 3
2024-01-13
2312
add a view to an ASP.NET core MVC app I found some difficulty for completing this task but I did it.

2024-01-17
2230
I am trying to change view and layout pages but would not able to complete this task.

2024-01-19
2251
I followed the step and able to change the vioe and layout of the page such as title, menu link in layout file.
when I run the application, it changed to movie app.

2024-01-19
2305

Passing data from controller to viewer
To complete this task, I changed the welcome method with new message and num value.
Next, I created a loop in the welcome.cshtml in hello world under view .
I run this in by clicking on https and type- HelloWorld/Welcome?name=Rick&numtimes=4
It give me output of rick for four time.

Part 4
2024-01-19
2356
Add a model

I added a model under MODEL by right click on it and press ADD >CLASS> give the file name : Movie.cs

2024-01-24
1015
ADD NU-GET PACKAGES
In Solution Explorer, I right-click the Controllers folder and select Add > New Scaffolded Item.

2024-01-24
1130
Add New Scaffolded Item
I followed the instructions Installed > Common > MVC.
Then selected MVC Controller with views, using Entity Framework< add.
 Add MVC Controller with views, using Entity Framework.

 2024-01-24
 1925

 Initial migration

 From the Tools menu, I selected NuGet Package Manager then Package Manager Console.
 In the package manager console i added the following command: 
 Add-Migration InitialCreate
 Update-Database

2024-01-24
2345

Testing the app
I followed the instruction step by step.
When i click on the Movie link tab it gives me error.
I tried again and again but do not able to find the output.
----------------------------------------------------------------------------------------------------------------------------------------------

2024-01-25
1235
I started a new project beacuse I got error and I would not able to find my error. 
So i decided to create a new project by the name of MvcMOvie

Part-5

2024-01-27
2030
I initially examine the database by follwoing the steps: 
From the View menu, open SQL Server Object Explorer (SSOX).
Right-click on the Movie table (dbo.Movie) > View Designer

Then I created a new class named as SeedData in Modal folder and run the code to seeded the data base.
After this step I deleted the data base and run the app. The app shows the seeded data.

Part-6 
2024-01-27
2105

Convert the releaseData in two words. I updated the movies.cs file in model 
folder and when i run the app , it run successfully.

Hence, I successfully run the task 6.

Part-7
2024-01-30
2004
Add search to an ASP.NET Core MVC app

Initially I updated the index method of Controllers/MoviesController.cs.
After updation, I would able to filter the movies according to the names.

Add Search by genre
To complete this task, firstly I created Movie GenreViewModel class in the model folder.

Add search by genre to the Index view
I Updated the  Index.cshtml in Views/Movies
After following the steps, I would able to run the app successfully.

Part-8
2024-01-31
1930

Add a new field to an ASP.NET Core MVC app.

Add a new field to the model.
I added a Rating property to Models/Movie.cs by follwoing the steps given in the tutorial.
I also edit the /Views/Movies/Index.cshtml file and add a Rating field.
I Updated the /Views/Movies/Create.cshtml with a Rating field.
Next, I Updated the SeedData class so that it provides a value for the new column.
In the end, I Migrate the new field to the database and app run successfully.
