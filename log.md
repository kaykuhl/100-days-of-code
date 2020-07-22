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

**Thoughts:** It was really exciting to get the response from the API and to actually be able to see the images. There are a LOT of new technologies in this course for me (Java, Thymeleaf, Springboot Framework), but I am following along well. I thought it was really cool how the Thymeleaf was able to loop through the API in the HTML code very easily to be able to display all the pictures from the API response. I am excited to continue to manipulate the response and front-end of the application to create something cool.  I believe that personal projects are the best way to learn, but it is also helpful for me to see how other people would tackle a problem and go about programming an application. Maybe I will do something space-y as a personal project after I am finished with this workshop.

### Day 4: July 15, 2020

**Today's Progress**: I worked for a couple hours with my group that I'm building the pet fostering website with and some time individually to figure out why our React app was not deploying to Heroku. After 2 1/2 hours! I figured it out! I changed a few things but the final thing ended up being that it couldn't find modules like "Express", which were in our DevDependencies and therefor wasn't being used in production.

![Image of Heroku](https://tse1.explicit.bing.net/th?id=OIP.fIjRtO5P8zc3pjs0E5hYkwHaDI&pid=Api)

**Thoughts:** It is problems like these that makes an hour seem like 10 minutes have gone by. And it is promising to just get a different error than you had before. But it is also pretty fun to think... "hm, what about this?? Maybe that would work?" and then the excitement of actually solving the problem is just so worth the whole process. 

### Day 5: July 16, 2020

**Today's Progress**: I didn't have a ton of time to code tonight, but I did make sure I spent an hour continuing to go through the Mars API workshop. Today was focused on the front end and making the images look nice (more like a gallery) with the help of Bootstrap.

![Bootstrapped Images](https://i.ibb.co/Vv2fLVD/7-16-2020.png)

**Thoughts:** Today was a pretty easy coding day, I was able to get a re-fresher on bootstrap (I am pretty familiar but haven't worked with it in a while) and in-line HTML styling as well as in-line logic with thymeleaf. It was interesting to see the combination of these languages all in the HTML file. 

### Day 6: July 18, 2020
**Today's Progress**: I got further in my Mars API Workshop. I was able to make some buttons that allows you to select different Mars Rovers and have their images show up.  This was done with Javascript, so it was the most familiar part of this tutorial for me so far.

![Buttons](https://i.ibb.co/Vjj1TJN/7-18-2020.png)

**Thoughts:** So far, I am understanding everything conceptionally going on in the tutorial. Manipulating the API URL call from the front end is pretty cool as it brings everyting together, next will be finishing up the front end of the application.

### Day 7: July 19, 2020
**Today's Progress**: I got further in my Mars API Workshop. I added a filter for the Sol day and was able to update the API get request to be able to change it on the front end with this value.

![Buttons](https://i.ibb.co/GWmKm5s/7-19-2020.png)

**Thoughts:** I was hoping to get a little more done today, but I ran into a strange error. This happened when trying to get the value to equal the param value (So that the value in the sol box would equal "5" if you were looking at day 5 pictures.  Otherwise, I am seeing the light at the end of the tunnel with this tutorial and I am hoping to finish it up early next week so that I can start working on my next personal project (haven't decided what to do yet) as well as get more headway on my group pet fostering website project.

### Day 8: July 20, 2020
**Today's Progress**: I worked on my group project for the animal fostering website and was able to display animal information on a card for all of the "adoptable animals" from my seeds for the MongoDB database.

![Card Template](https://i.ibb.co/N2Dgk4N/7-20-2020.png)

**Thoughts:**  The card still needs a lot of work, but the props info is there.  It is always challanging getting the front end and back end connected, but so far it seems like it will go smoothly in this project.

I also figured out my bug from the mars app. By figuring it out I started it up today and it was working.... might have been a caching issue?

### Day 9: July 21, 2020
**Today's Progress**: Today was fun with Thymeleaf and checkboxes! I added several checkboxes to the Mars API Application (I am following a tutorial for this application and learning a lot) and linked them up to the backend so that the boxes are checkable and we can now link the data (which cameras were selected) to the actual API call. I also learned better how to test an API through postman.

![Checkboxes for Mars Rover API App](https://i.ibb.co/6BNQrqY/7-21-20.png)

**Thoughts:**  I am enjoying learning about thymeleaf, it seems like a great timesaver (no pun intended). I am also just solidfying some of my knowledge on APIs that will come in handy in future personal projects (really using the power of Postman to test out different limits of the API for example). For the Mars application, this was the final piece of the front end (other than spiffing it up a bit with bootstrap to make it look nicer). Other than that, I just wanted to make note that using Java isn't as complicated as I thought it would be. While I am only really familiar with javascript, I didn't realize how much of the concepts are the same in different programming languages. It just all comes down to remembering syntax and knowing what is the best way to approach a problem.
