Root Coding Problem 
Riley Patrick 

This project allows the user to type in the name of a file within the directory. The application then 
reads that file and generates a report about the drivers listed in the txt file. I programmed this 
assignment in Java because I have the most experience writing in that language. And more 
specifically, I have a great deal of experience writing tests in Java. 

To create this project I started by making a model for each driver. Having driver objects allowed me 
to house all the data in one place. Each trip would update that driver's information. I only added 
times and miles to each driver because I felt that adding information like start and stop timse would 
just add extra unneeded variables. Therefore, just having one object was ideal. 

I originally started out using repositories and databases to house my driver objects. But I quickly 
found that this approach was adding too much unnecessary complexity. I then switched to using an 
ArrayList, which offered many of the benefits of a database. The ArrayList offered the necessary 
functions to add objects, to access data within those objects, and to sort those objects. I have 
also found ArrayLists quick to test, which added to this decision. Switching to using an ArrayList 
helped simplify my project without compromising any functionality. 

I tested using the test driven development method. I started the project over during the early 
stages so that I could better code TDD. Using TDD allowed me to quickly see where my issues 
were and fix them. I was able to code confidently, knowing I had my tests to guide me. Restarting 
with TDD saved me a great deal of time that would have been spent on struggling to find bugs. I 
believe that testing is a key aspect of writing clean, workable code. 