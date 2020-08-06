# 100 Days Of Code - Log

### Day 1: July 12, 2020

**Today's Progress**: Spent 1 hour on working on a tutorial/workshop where I am building an application using the Mars Rover API (my first time building something in Java). The link to the course is here: https://proffesso.com/Mars-Rover-Api-Workshop. Today's progress was getting some of the API mapping and classes figured out. The next portion of the course will be on the front end and getting the mars rover pictures to display.

I also spent an additional hour working on a group project that I am working on with a few girls from my coding bootcamp that we graduated a few months ago.  One of the girls fosters dogs and saw a need for an improvement to their website, so we are building a foster website using React, MongoDB, and Express/Node on the backend. I am taking on the responsibilities for the back-end of the website. Today, I was able to 
1. Modified the server.js file and set up an API route to the mongoDB to "get" the data so we will be able to display the adoptable animals on the website
2. Created seeds to be added to the API when the user uses the command line to run "npm run seed"
3. I verified that the seed was being inputted correctly using Postman. As you can see in the screenshot, it took me a few tries in my history to understand what was going on. But, I was very happy to successfully get the response I was looking for!

![Image of Postman GET request](https://i.ibb.co/nwQHwn3/7-12-2020.png)

**Thoughts:** I am excited to get a better handle on Java by doing a tutorial before diving into a personal project using Java. I am also excited to be working on the backend of this collab project with Ashley and Haylee. I definitely have found that I gravitate towards the backend development. It has been a while since I've worked on a group project and it is refreshing since that is one of the things I missed most about my coding bootcamp that I graduated back in March, 2020.  As far as this project, I am more familiar with MySQL, so using MongoDB is a good challenge for me.

### Day 2: July 13, 2020

**Today's Progress**: I spent around 3 hours working on my React Portfolio. I had a lot of CSS tweaking to do and changed around some content.

I was also very happy I was able to get my github pages to be hosted on a domain I purchased, www.blissfullycoding.com.

![Image of Updated Portfolio](https://i.ibb.co/Lzwfntz/port.png)

**Thoughts:** I thought the actual hosting onto my domain went a lot smoother than I was anticipating. I was happy that github and the website I used, NameCheap, were able to link up. I had to go through the Advanced DNS settings and add a few records (ports?) as well as a CNAME record linking to my GitHub. I am happy with my porfolio, but I wish I had more of a design background to make it more slick.  While I do enjoy monkeying with the CSS, I still do thrive more in the back-end side of web development at the moment. But, I would love to be able to become more familiar with website design and how to play with space and colors.

### Day 3: July 14, 2020

**Today's Progress**: I continued on my progress on the Mars API Workshop. I was able to follow along with Trevor Page and was successfully able to get the pictures from the REAL mars rover show up on localhost!

**Thoughts:** It was really exciting to get the response from the API and to be able to see the images. There are a LOT of new technologies in this course for me (Java, Thymeleaf, Springboot Framework), but I am following along well. I thought it was cool how the Thymeleaf was able to loop through the API in the HTML code very easily to be able to display all the pictures from the API response. I am excited to continue to manipulate the response and front-end of the application to create something cool.  I believe that personal projects are the best way to learn, but it is also helpful for me to see how other people would tackle a problem and go about programming an application. Maybe I will do something space-y as a personal project after I am finished with this workshop.

### Day 4: July 15, 2020

**Today's Progress**: I worked for a couple of hours with my group that I'm building the pet fostering website with and some time individually to figure out why our React app was not deploying to Heroku. After 2 1/2 hours! I figured it out! I changed a few things but the final thing ended up being that it couldn't find modules like "Express", which were in our DevDependencies and therefore wasn't being used in production.

![Image of Heroku](https://tse1.explicit.bing.net/th?id=OIP.fIjRtO5P8zc3pjs0E5hYkwHaDI&pid=Api)

**Thoughts:** It is problems like these that make an hour seem like 10 minutes have gone by. And it is promising to just get a different error than you had before. But it is also pretty fun to think... "hm, what about this?? Maybe that would work?" and then the excitement of actually solving the problem is just so worth the whole process. 

### Day 5: July 16, 2020

**Today's Progress**: I didn't have a ton of time to code tonight, but I did make sure I spent an hour continuing to go through the Mars API workshop. Today was focused on the front end and making the images look nice (more like a gallery) with the help of Bootstrap.

![Bootstrapped Images](https://i.ibb.co/Vv2fLVD/7-16-2020.png)

**Thoughts:** Today was a pretty easy coding day, I was able to get a refresher on bootstrap (I am pretty familiar but haven't worked with it in a while) and in-line HTML styling as well as in-line logic with thymeleaf. It was interesting to see the combination of these languages all in the HTML file. 

### Day 6: July 18, 2020
**Today's Progress**: I got further in my Mars API Workshop. I was able to make some buttons that allow you to select different Mars Rovers and have their images show up.  This was done with Javascript, so it was the most familiar part of this tutorial for me so far.

![Buttons](https://i.ibb.co/Vjj1TJN/7-18-2020.png)

**Thoughts:** So far, I am understanding everything conceptionally going on in the tutorial. Manipulating the API URL call from the front end is pretty cool as it brings everything together, next will be finishing up the front end of the application.

### Day 7: July 19, 2020
**Today's Progress**: I got further in my Mars API Workshop. I added a filter for the Sol day and was able to update the API get request to be able to change it on the front end with this value.

![Buttons](https://i.ibb.co/GWmKm5s/7-19-2020.png)

**Thoughts:** I was hoping to get a little more done today, but I ran into a strange error. This happened when trying to get the value to equal the param value (So that the value in the sol box would equal "5" if you were looking at day 5 pictures.  Otherwise, I am seeing the light at the end of the tunnel with this tutorial and I am hoping to finish it up early next week so that I can start working on my next personal project (haven't decided what to do yet) as well as get more headway on my group pet fostering website project.

### Day 8: July 20, 2020
**Today's Progress**: I worked on my group project for the animal fostering website and was able to display animal information on a card for all of the "adoptable animals" from my seeds for the MongoDB database.

![Card Template](https://i.ibb.co/N2Dgk4N/7-20-2020.png)

**Thoughts:**  The card still needs a lot of work, but the props info is there.  It is always challenging getting the front end and back end connected, but so far it seems like it will go smoothly in this project.

I also figured out my bug from the mars app. By figuring it out I started it up today and it was working.... might have been a caching issue?

### Day 9: July 21, 2020
**Today's Progress**: Today was fun with Thymeleaf and checkboxes! I added several checkboxes to the Mars API Application (I am following a tutorial for this application and learning a lot) and linked them up to the backend so that the boxes are checkable and we can now link the data (which cameras were selected) to the actual API call. I also learned better how to test an API through postman.

![Checkboxes for Mars Rover API App](https://i.ibb.co/6BNQrqY/7-21-20.png)

**Thoughts:**  I am enjoying learning about thymeleaf, it seems like a great timesaver (no pun intended). I am also just solidifying some of my knowledge on APIs that will come in handy in future personal projects (really using the power of Postman to test out different limits of the API for an example). For the Mars application, this was the final piece of the front end (other than spiffing it up a bit with bootstrap to make it look nicer). Other than that, I just wanted to make note that using Java isn't as complicated as I thought it would be. While I am only really familiar with javascript, I didn't realize how much of the concepts are the same in different programming languages. It just all comes down to remembering syntax and knowing what is the best way to approach a problem.

### Day 10: July 22, 2020
**Today's Progress**: While I did no actual writing of code today, I am counting it towards this endeavor. I spent 45 minutes meeting with my group on our foster website and did another hour of pseudo coding and looking up some information as I am trying to figure out the best way to display the animals on the adoption page.

**Thoughts:**  My thought is to have a list of small cards that give basic info on the pet, and then when you want to learn more about a specific animal, you can click and it will expand (to a new page or another component on the page) to show the rest of the data about the pet and a longer description. I am researching if there is a way with my current skills with react to create a different HTML route for each animal in the database so their info can be displayed (and so people could "share" a particular link). Or if using the components in react to have something more dynamic would make more sense in this scenario.

### Day 11: July 23, 2020

**Today's Progress**: Got further in the Mars API Rover Workshop. I started the process of the if then statements for the API call based on the camera. It is a little complicated because not all rovers have the same camera types.  Unfortunately, I ran into a bug and my unfamiliarity with Java is failing me I think.

![Debugging](https://i.ibb.co/02j5jLy/7-23-20.png)

**Thoughts:** I am having a little trouble understanding this part of the backend and how everything is coming together. I will take another look tomorrow and see what is going on. It seems like sometimes coming back to a problem after sleeping or with a fresh set of eyes sometimes allows you to see what you didn't see beforehand.

### Day 12: July 25, 2020

**Today's Progress**: Still stuck in on the same problem in the Mars API Rover Workshop. 

**Thoughts:** I thought I could figure this out and finish up this app today but it was a day of debugging.


### Day 13: July 26, 2020

**Today's Progress**: Refactored some dry code (all of the 9 if else statements) into 6 lines of code, and then added some code to the front end in order to disable cameras when the rover does not have them.

![Disabled checkboxes added to Mars API Web App](https://i.ibb.co/DCN2sgN/7-26-2020.png)

**Thoughts:** I made a lot of headway on the Mars API App Workshop! I am pretty much completed with the application and just have a few things to finish up.  I have really enjoyed this tutorial. I've learned a lot about Java and Springboot and it was really helpful for me to watch Trevor debug and go through the code line by line.  I have concluded that doing your own personal projects are the best way to learn, HOWEVER, being able to watch an experienced coder and actively try to pick up their good habits and watch their thought process brings a ton of value to me.

### Day 14: July 27, 2020

**Today's Progress**: Final steps of the Mars Rover API App! I added checkbox to save preferences and added code to connect to mySQL database and create tables/columns based on the information for the API call on the UI based on user selection.

![Creating mySQL tables](https://i.ibb.co/tHbK5X8/7-27-2020.png)

**Thoughts:** I have no idea why, but I LOVE databases. For some reason, they just make sense to me. It was one of the ways I got introduced to software development (I would query access databases in one of my chemistry jobs).

### Day 15: July 29, 2020

**Today's Progress**: Team zoom call (foster pet website) to update our progress and then tried to get the Mongodb to work on heroku (and get the seeders added). Everything works locally, but when I try to deploy, I am not able to figure out how to get MLab/Heroku/Mongoose/Mongodb/seeds file all jiving together.

![Mongoose](https://i.ibb.co/HpgnKLV/7-29-2020.png)

**Thoughts:** I definitely tend to shy away from MongoDB (MySQL just makes a lot more sense to me) Definitely a lot of stack overflow today, which is okay.  I know with enough time, I will be able to figure it out.

### Day 16: July 30, 2020
**Today's Progress**: Made some bug fixes with the Mars API App.

**Thoughts:** Bug fixes always take time but so rewarding when you figure it out.

### Day 17: July 31, 2020
**Today's Progress**: Might have my first freelance client??? My SO has a friend who is looking to make a Wordpress website for his business. I have played around with Wordpress a bit in the past, but I excited to learn more and help our friend build a professional looking website.

![Wordpress Logo](https://s.w.org/about/images/wordpress-logo-stacked-bg.png)

**Thoughts:** I am also interterested in having more freelance clients in the future, so this will be a great experience for me.

### Day 18: August 2, 2020
**Today's Progress**: I hopped around to a few things today. My main priority is getting our MongoDB database up and working for the foster website. For some reason, I am having a lot of trouble and been doing a lot of research as to why this is not working. I also researched more on how to build sites on Wordpress.

**Thoughts:** I think I should create a better schedule for which projects to work on since I feel distracted and want to work on multiple things at once! I think that is okay, but a little structure would help me organize my thoughts. I am also counting down the days I get to start my new job as a software developer! I am wondering if it will affect the energy for my side projects. I would really like to continue this challenge but will be making my new job my first priority.

### Day 19: August 5, 2020
**Today's Progress**: I am done with my Mars API Application Workshop and I have a cool Mars Rover Application to show for it. This is an application to view pictures from the various Mars API Rover cameras. The application allows for filtering by Sol day as well as camera type. The database also uses a database (MySQL) to save search preferences.

![Mars API Application](https://i.ibb.co/GWtz8DW/8-5-2020.png)

**Thoughts:** I followed the Mars Rover API Application Using the workshop provided by Trevor Page on Proffesso titled, "Mars Rover Api Workshop". (View the tutorial at https://proffesso.com/Mars-Rover-Api-Workshop) I highly recommend this course for anyone looking to make a fun application using the Mars Rover API. I enjoyed that this was a full stack application. Since I know Javascript, HTML, and CSS, I was familiar with a lot of the concepts, but I also learned a lot. The main things I got out of this tutorial were:
* My first experience building a Java Spring Boot Application
* Learned about the possibilities with Thymeleaf (Java template engine)
* Getting familiar with the Mars Rover API Calls and using Postman to test these calls (I have done this before, but it was a good exercise since this API call has a lot of variables that can be manipulated (sol day, camera type, rover)
