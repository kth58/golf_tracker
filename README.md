# golf_tracker
This is an app to track golf stats.

# Initial Design
We will need to talk to go over the design of the application, but below is some of the notes that we came up with while we were talking:
1. Add a golf course with the: 
  - course name
  - slope
  - rating
  - handicap
  - holes (with par, yardage)
2. We will need to add functionality that will allow us to select a course and load the holes and other information while we are playing 
3. Once we hit the ball we will need to track our shots, the normal flow will be like this:
  - Hit the ball
  - click on start this will get your geolocation to start tracking how far your shot went
  - then click on [Left, Center, Right] . One we click on LCR that will get your geo-location again to determine how far your shot went.  
    - Clicking on Left Center Right will change depending on how far away you are from the hole. (Drives it will be considered as Left, Center (or Fairway), Right. When on approach or fairway shots this will be considered as left, center, right of where you were aiming. This will be determined by the application knowing if it is the first shot or not.
  - This will end your shot.
4. We would use this data to feed into our app to help you improve and then track your tendencies. 

# Things you will need to do to setup on your machine. 
1. We are going to use Python for the backend of the application. So you will need to download and install Python 3.8. **Make sure you install python to your path.**
2. Instal Git and the Git command line interface to your computer. 
3. Download Visual Studio Code to your computer. 
4. Download Zoom to your computer. 

# Things you should look at while you are first starting out:
1. Basic Python Programming:
  - You should know the basic data types: [String, Integer, Double/Float, List, Dictionary, Set] 
  - You should know the basics of programming controls: 


### Notes:
1. We found this golf database api that provides all the information for golf courses: [here](https://golf-course-database.com/api-v1-0/)
