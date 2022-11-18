﻿2022-10-21 1243
Built the initial default application
prepend my name - 'MonicaBookStore'
Individual Account Authentication
Added Razor runtime - just for fun! ;
Hit create and then reviewed the default app.
1246
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Second attempt started from scratch 
2022-11-10 11:30a.m
Created a newproject and named MonicarBookStore
Indicvidual Account Authentication
Added Razor runtime
Hit Create and then reviewed the default
in launchSettings.json comment sslport
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2022-11-11:45am
_viewsStzrt.cshtml,migrations are checked following the instructions
in startup.cs options=>options.SignIn.RequireConfirmedAccount=true is removed
create a gitrepository with Repository Name Monicar and make it public
Go to Bootswatch.com
Goto wwwroor and replace the existing bootstrap.css this is done following lib>bootstrap>dist>css these steps
replace the existing site.css file found in the main css folder
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------A
add stylesheets and scripts to _Layout.cshtml from CSS_JS.txt file
To the Navbar a drop down is added.
drop down is working
-------------------------------------------------------------------------------------------------------------------------------------------
2022-11-10 Add and modify 
Three projects are added and named as MonicarBook.DataAccess,MonicarBooksModels, MonicaBooksUtility
Installed required Nuget packages in MonicarDataAccess
Migrations folder deleted
name space is modified, At this point I have errors
Deleted class1.cs from all the folders
I could not build the project because of errors
I continued with the remaining steps inspite of errors 
Added required references
Changed ErrorViewModels.cs to .Models.ViewModels
tried rebuikding the project but could not run it due to errors
I am clsoing at this point
It is 2:00 PM
--------------------------------------------------------------------------------------------------------------------------------------
2022-11-11 12:15PM
I tried fixing the errors occured the daybefore
I could fix the errors and proceeded with the remaining steps
In the utility project a class SD.cs created
project reference to the main project added
In the DataAccess project project references to Models and utility are added
1:00PM Add a "Customers" area to areas is done
HomeController.cs moved to the Area>Customer>Controllerfolder and Data and Models are deleted in controller folder
namespace is modified in HomeController
Ran the application 
It does not give me the desired output 
--------------------------------------------------------------------------------------------------------------------------------------------
Since my project which I created did niot give me the output
3rd attempt
2022-11-11 at 10:50PM
created a new project named MonicBookStore
checked startup.cs and option=>statement followed by it are removed
10:59PM creating a Git Repository
Git Repository created and pushed.
------------------------------------------------------------------------------------------------------------------------------
11:04PM started with 1.1 Review
views/shared/_Layout.cshtml in footer a small change is made
Remaining files are checked in views/shared
11:12 Debugging 1.2 started
--------------------------------------------------------------------------------------------------------------------------------
11:30PM Bootswatch.com
downloaded united theme and replaced the originalbootstrap.css in wwwroot with downloaded version 
existing site.css is replaced with the code given
I have warnings after site.css code is replaced
view/Shared>_Layout.cshtml the file name is changed from min.css to bootstrap.css
Additional properties added in the footer
I relaxed for sometime
---------------------------------------------------------------------------------------------------------------------------------
12:00AM 2022-11-12 continued with the project
Hope I get it correctly this time
_LoginPartial.cshtml removed references to text-dark
Ran project to see the changes
_Layout.cshtml additional stylesheets and scripts are added from the CSS_Js.txtfile
A dropdown added to the NavBardropdown changed to the Content Management
Ran the application to check if the dropdown is working
so far so good
12:54 AM Committed the changes 
-------------------------------------------------------------------------------------------------------------------------------------------
2022-11-12 2:30PM I switched back with the project created second time and decided to continue with it because my third attempt project was not giving output correctly
I started with the second part of the project I rebuild the solution it did not give me any 
In package Manager Console add-migration AddDefaultIdentitypeMigration choosingMonicarBooks.DataAccess
I have an error saying "Exception has been thrown by the target of an invocation." how to fix this?

MissingMethodException: Method not found: 'Boolean Microsoft.EntityFrameworkCore.Migrations.IMigrationsModelDiffer.HasDifferences(Microsoft.EntityFrameworkCore.Metadata.IModel, Microsoft.EntityFrameworkCore.Metadata.IModel)'.
Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore.DatabaseErrorPageMiddleware.Invoke(HttpContext httpContext)﻿
3rd attempt
2022-11-11 at 10:50PM
created a new project named MonicBookStore
checked startup.cs and option=>statement followed by it are removed
10:59PM creating a Git Repository
Git Repository created and pushed.
------------------------------------------------------------------------------------------------------------------------------
11:04PM started with 1.1 Review
views/shared/_Layout.cshtml in footer a small change is made
Remaining files are checked in views/shared
11:12 Debugging 1.2 started
--------------------------------------------------------------------------------------------------------------------------------
11:30PM Bootswatch.com
downloaded united theme and replaced the originalbootstrap.css in wwwroot with downloaded version 
existing site.css is replaced with the code given
I have warnings after site.css code is replaced
view/Shared>_Layout.cshtml the file name is changed from min.css to bootstrap.css
Additional properties added in the footer
I relaxed for sometime
---------------------------------------------------------------------------------------------------------------------------------
12:00AM 2022-11-12 continued with the project
Hope I get it correctly this time
_LoginPartial.cshtml removed references to text-dark
Ran project to see the changes
_Layout.cshtml additional stylesheets and scripts are added from the CSS_Js.txtfile
A dropdown added to the NavBardropdown changed to the Content Management
Ran the application to check if the dropdown is working
so far so good
12:54 AM Committed the changes 
worked on this, encountered errors in the part-4 assignment2, still in the firstpart of it. 
----------------------------------------------------------------------------------------------------------------------------------
-I don't have track of my attempts
May be 5th attempt
11:30AM created EdaMonicaBookStore with three projects following the steps carefully hoping not to have any errors
I am not repeating the steps
I started with 1.1, proceeded with 1.2, 1.3 and rebuild the solution. going on smoothly
Reached 1.4 moving on, I see errors in startup.cs 
services.AddDbContext<ApplicationDbContext>(options =>
.AddEntityFrameworkStores<ApplicationDbContext>(); ApplicationDbContext with red line
after a long time, I figured out to solve this error
followed steps after that like moving models from main project to EdaMonicaBook.Models and Areas Customer Area and Admin Area added and SD.cs also is created
I don't have any errors, but when i run program it says LocalHost page cannot be found. I did this on chool computer commmitted changes but nothing is being updated on my 
laptop, again I had to repaeat the process and mean time I could not push my committs,
I pulled and pushed my commits and I noticed that my main project is unloaded
instead of dwelling upon that I again started 6th attempt
------------------------------------------------------------------------------------------------------------------------------------------------------
6th attempt 2022-11-18, 12:30 From scratch
up to fourth i.e 1.4 i did okay
Later, I have an error
Severity	Code	Description	Project	File	Line	Column	Suppression State
Error	CS0246	The type or namespace name 'ErrorViewModel' could not be found (are you missing a using directive or an assembly reference?)	EdaMoniBookStore	C:\Users\edamo\source\repos\EdaMoniBookStore\obj\Debug\netcoreapp3.1\Razor\Views\Shared\Error.cshtml.g.cs	31	88	Active
Error	CS0246	The type or namespace name 'ErrorViewModel' could not be found (are you missing a using directive or an assembly reference?)	EdaMoniBookStore	C:\Users\edamo\source\repos\EdaMoniBookStore\obj\Debug\netcoreapp3.1\Razor\Views\Shared\Error.cshtml.g.cs	92	71	Active
I spent lot of time on this project, I want to solve the errors and get good marks, hope things work out well for me.



