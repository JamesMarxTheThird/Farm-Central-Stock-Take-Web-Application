# Farm-Central-Stock-Take-Web-Application

Background

This C# ASP.NET web application was built to accurately track farmers’ stocks and for employees to view their profiles and items. This is all done on a simple UI and doesn’t have issues with accuracy or speed. A video demonstrating app use is attached as well as another video showing all the source code of the app.
Login details for the users are under the functionality section of their user types.

This is a 3rd year assignment at Varsity College done for Programming.

Getting Started

Note: This app only works in Visual Studios 2019 Pro or Visual Studios 2022! This is due to a database configuration that comes along with the pro version and is incompatible with other versions. If you login and get the error “"The Database cannot be opened because it is version 904, this server support version 852 and earlier.."” note that it won’t work.  Otherwise see attached screenshots for a better idea on the project.

Download the “.zip” file and extract it onto your pc. Then open the “FarmCentral_ST10114442” visual studios file and run it inside Visual studios.

You will be presented with a login page and based off your account attributes you will either have a farmer or an employee profile. Please look at the appropriate functionality and login details for your desired account type.

![LoginPage_](https://user-images.githubusercontent.com/101861214/178948707-04f04db7-02d7-4e77-9ead-924770f41834.png)


Functionality 

Employee 

Username: emp	
Password: emp

If you have logged in as an employee, you will see a basic home page. On the top is a navigation bar where you can go from the home page to the view stock page, to the add farmer page.

The view stock page shows all items added by any farmer loaded to the site. You can filter these items accordingly. First off you need to select a farmer name on the drop-down list on the left. Once you have chosen this, the list will get smaller, only showing that farmers data. Now you can filter further by date or product type. For the date make sure you have selected a user, then select a start and end date. After this, click the “Filter by date” button and it will filter the items from that user, between the dates specified. If you want to filter by product type / category you need to first click “Reset list”. Then select a farmer again, then select a type from the category on the right-side drop-down list. Lastly click filter by type and it will show results for that user, with items of that type.


![empViewpage](https://user-images.githubusercontent.com/101861214/178948803-0fa07fea-ef75-4c71-8e34-78038cb94246.png)

The other page is the add farmer page. Employees can add new farmer profiles by clicking add new farmer. Here you just need to fill in the textboxes and click “Create farmer profile”.


![add_farmer](https://user-images.githubusercontent.com/101861214/178948870-3ffae01c-72f7-4d8c-a910-5e24d7fb12a9.png)


Farmer

Username: farmer
Password: farmer

The farmer has a basic homepage and can add a new item to their profile.


![farmer_homepage](https://user-images.githubusercontent.com/101861214/178948940-9afd35c9-7d55-41e8-a9a4-cd925480a9dd.png)


Click the add new item link on the navigation bar. Here all a farmer needs to do is fill in the 2 textboxes, select a date on the calendar, and then select a product type. After this click “Add stock item”. You will see the list of items below will update and add the new item to it, indicating its been added to the database.


![addproducts](https://user-images.githubusercontent.com/101861214/178948999-03453b10-e885-400e-a6a4-76e9d4951e90.png)

Conclusion

It was quite unfortuunate running into an unsolveable database error, but the app is not yet in its final stage, as i'm sure you can see. Either way the app came out nicely. I’m happy with the functionality but know that the interface is quite difficult on asp.net. The app is fast, accurate and easy to use meaning it checks all the boxes, but with a bit more design and validation it would be perfect.
