
# BookmyShow LLD - Classes and Design Patterns 

BOOK MY SHOW - Classes:
==================================

1. User is viewing on the movies - Class "Movies"
   Data Members -
   - Language - eg) Hindi, English, marathi
   - Genre - eg) Action, Romantic
   - Format  eg) 2D, 3D
  
   Functions -
   - showList() of movies 
   - filterList()  - based on genres, language, format

# UML DESIGN -
  
Note - There can be different movies - movie1, movie2, movie3 - These will be different classes extending Class Movies
![image](https://github.com/Gautami56/bookMyShowLLD/assets/62929436/d0089836-774d-46eb-8468-411405ca6c36)

https://lucid.app/lucidchart/113ca846-5d10-422f-a272-5bb449cc137b/edit?viewport_loc=-522%2C-96%2C3330%2C1557%2CHWEp-vi-RSFO&invitationId=inv_0a01bc3a-5cf3-42b9-bc1f-195a5ec2faa2



Note - MovieItems have diffrent object and hence it si Factory Pattern

# TYPES OF DESIGN PATTERNS -
1. Design Factory Pattern - We can use this pattern when we have multiple object creation of the same class
   eg) Type of Movies - Shows, Comedy, Action, Romantic

2 Observer Design Pattern - We can use this pattern for any notifications or any task that is in queue and will be processed once the conditions are met
This has Subject - the observable that is the one that will send notification
         Observers /Listeners - they are subscribers or listners receivig the notification
         
3. Singleton Design Pattern -  We can use this pattern when we have single objects of the same class. The same object instance wil be used everywhere and wont be modified
   eg) Database , Cache - only one server ,
   Note - Here we use only static were objects are not reinstatinated. They dont use classes

4. Stratergic based Design Pattern - We can use this pattern when we have any alogrithms of decision making or ANY filtering logic applied
   eg) Recommended movies based on type of movie, language selected in past
       Algos to filter and sort the movies list
       Various Payment methods applied
       Availability of seats / movies based on ratings
       Show Top most rated movies based on ratings and feedbac




  
   
