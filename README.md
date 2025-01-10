# -Key_component_traceability_system

-i will present to you my project which has been implemented to solve the problem of recording the barcode of the components like (Led bar, PCB, open-cell) Inside the TV set 
We worked on our project in the TV factory at #ElAraby_Group*
Before we started, there was a *Japanese* system called *Snoopy*.
This system was a manual scanner that scanning the serial number on the components and stored it on a database in the factory , but this system has defects presented in the picture below(1) 👇 The first defect was: The technician must be well trained on using the manual scanner which needs a suitable distance from the serial number to scan it.
The second defect was : the scanner has low sensitivity, it can only read 25 digits only, and therefore it neglects any data higher than 25.
The third defect was : This system depends on servers, when the servers go down the network on the laptops also go down , and thus the production line will stop for hours (and this system is not subject to modification).
Therefore, we created a mobile application to be an alternative to this system,
as the mobile camera has much higher sensitivity than any manual scanner available in the global markets.
Watch the video(2)(Vedios in comments) to see how the program works as a scanner in the Production Line and then it records data on the Database (Firebase database)‚show image(A).
We choose it(Firebase) because it is a product from Google and it has well security, also there are giant companies that use it, we also added a feature in this program that allows you to *Search* for any components recorded on the database from the production line.
watch the video to see(3).
__
-After we solved the problem of recording the components and creating a database,
we tried to take advantage of this database , so we focused on the most important problem in any company , which is customer service.
So we made another application which the customer can use by scanning the barcode on the guarantee certificate, then inputting his data and send it to the company as shown in the video (4), 
this data received on Google Sheet shown in the image (5).
This sheet we added 3 advantages to it.
the first one is that it is connected to the database, so as soon as the device’s barcode received , the rest of the data of the components inside this device appears immediately. 
The second feature, is receiving the customer’s data with time and date, so that customer service informs the customer of the date that the technician goes to fix his device.
The last advantage is that we have created a dead line to respond to the customer as a maximum of four days as long as I have reached the deadline , it will be green , if there is a delay, it will be red, if you finish the solution by closing it, it will be gray.
__
-Team M Triple A members:
Amira Mohamed , Mahmoud Elbasit , Ammar yasser ,Alaa Amin Elgezery     
