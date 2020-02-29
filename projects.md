# Projects
## Rate My Co-op
At [HackBeanpot](https://hackbeanpot.com/), my team created a webapp to allow students to rate their co-op and interview experience. 
- Inspiration: At Northeastern, students are prompted to review their courses at the end of the semester in an internal system. These anonymous reviews are then visible to other students to read through when they pick their own courses to take. This information has been really helpful for us during our college careers as it has allowed us to understand our workloads better when building schedules, and ensuring that we take courses with the professors we think are best fit to our learning styles. We wanted a similar system for co-ops, being able to review a co-op experience or interview experience helps provide valuable informatino to students to know what they're getting into. For example, knowing that an interview process is long and that a company typically takes a while to respondis helpful for a student working with tight deadlines. Knowing more about the culture at a company can help a student decide whether or not they think they are a good fit.
- Implementation: We used Vue.js for our front-end and Flask as our back-end, with MongoDB to store our data. Although I helped to debug our Python Flask code, I primarily worked on the front-end for this project. I created our home page which displays the companies in our database, our company adding form, and review forms. I also worked on the routing for our front-end, where our main challenges were passing data between our components.

Our project can be found [on github](https://github.com/estern1011/trace-4-coop).
Here's a [video](https://vimeo.com/390266154) of it in action!

## CS:GO Live Match Stats Tracker
- Inspiration: Sometimes when I'm playing a game of Counter-Strike, my friends will ask me how my game is going. I wanted to be able to show them exactly how well it was going!
- Implementation: I used [Valve's Game State Integration](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Game_State_Integration) to receive data about my games. I did this by setting up a Flask server that could receive POST requests at the address I configured for CS:GO. Then, I set up a Vue.js client to be able to make GET requests to the Flask server, and update a table for my stats in real time. 
- Limitations: With Game State Integration, I can only get data that the game would allow me personally to know in real time (as getting data about other players could be exploitable in the game). As a result, I could only display my statline.

My project can be found [on github](https://github.com/estern1011/csstats)

## The BatComputer 2.0
- Inspiration: He's batman. Also, I had to do it for a grade. I had a partner for this project and we bonded a lot over quoting Batman movies.
- Implementation: This project was mostly about the database, we used MySQL to design a database to track Gotham's villains and crimes. We added in features such as triggers for new data that didn't match up (such as adding a prisoner to a prison at capacity), and stored procedures for situations like a prison break. Then, we used Flask and its templating tools to create a CRUD interface. 

## The Easy Animator
- Inspriation: If I didn't do it I would have failed a class. The idea behind the project was to create a program that could create visualizations of animations given text files describing them. 
- Key Points:
    - Pair programmed for this project
    - Iteratively updated the project in new assignments to learn concepts of object oriented design.
        - For example, we had to swap views with another group at one point using a common interface
    - The project was a MVC Java application, using Java Swing, SVG output, and text output for our views
    - We implemented features such as animation looping, scrubbing, and shape layering

Since this was a class assignment, I can't expose this in a public github repo. If you would like to see it, please contact me.
