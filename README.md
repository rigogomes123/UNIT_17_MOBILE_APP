# Produce designs for a mobile app to meet identified requirements:

### Introduction:

You have been contacted by a local wellness spa and gym. They know you have completed a lot of research on mobile applications previously and have seen your web article. They want you to create a bespoke habit tracking application. Their only key requirements are the following:

Should be able to track the amount of water someone has drunk in a day (Such as counting glasses of water drunk or litres etc)
Should be able to track the number of workouts
Should have a timer that can be used during workouts. 

#### Wireframe:
Desighning the wireframe was the first activity i started after reading the scenario, Here's what I've done:

Default Android studio main page:

screenshot:

##### Wireframe(Android Home Page) :

![image](https://github.com/user-attachments/assets/9683a15d-54d1-4c7f-8d2a-bc1a2c633bc1)

In my first wireframe design of the home screen of an android, i recreated what it would look like in android studio. The main default page

##### App's main page/ Home screen:

![image](https://github.com/user-attachments/assets/eba4a41f-9a4b-4c18-9302-0497cc911ff1)

The main application page will contain a background image which will probably be black or a dark style, It will contain a message welcoming the user to the application and a button(Get Started) wich will lead to start the whole application it seldf

##### App's Lanidng page:

![image](https://github.com/user-attachments/assets/dbc9095f-c012-407c-8176-0104af606ede)

For this Page I decied to only implemnet 2 option which were Option one which allows the user to track the amount of water the user have intaken and option 2 which allows you to track the amount of workouts and it also have a timer implemented to allow the user to time themselves when working out. Regarding The background image I will implemnet a fitness like image in order to motivate the users.

##### Water Tracker Page:

![image](https://github.com/user-attachments/assets/648581be-57c3-4505-b2d9-ebe1f42db889)

For this specifict design It will have two main screen, the first screen will allow the user to inter the amount of water they have drunk in either glass or ml, the secound screen will output the infomration and store it that way the user is able to keep track of their intake, regrading the background image I will probably implemnet a inmage of a person drinking water.

I got my aspiration from the following design:

![image](https://github.com/user-attachments/assets/db85e7f7-c36d-4a4c-9a2e-cb963580c700)


##### Timer and workout Page:

![image](https://github.com/user-attachments/assets/45f99c17-a098-41d2-9ca9-3f90274a9b48)

Just like the previous deisgn thiis design will also contain 2 inputs and 2 output the first input will allow the user to keep track of the amount of workouts they have done, and the secound input will be a timer wich will have 3 options START,STOP and RESET.

# Case diagram:

![image](https://github.com/user-attachments/assets/9ef60e5c-71f6-40d2-bc1f-761b7d6b5338)

By using the case diagram it provides calrity and understanding, the functions of the application such as water intake,monitoring and calculating workouts by utilising a timer and how the users will interact with them are clearly and visually represented.

The primary actor such as the user and how they will interact with various system components are easuly readable and understandable.For instance:

"Track water intake" --> The user enters the amount of water consumption.

"Track Workouts" --> The user can record workouts that are finished.

"Workout Timer" --> During exercise, the user intiates and stops the timer.

# Psuedocode:

![image](https://github.com/user-attachments/assets/a5539247-d58e-491c-984f-67fc2ab74290)
![image](https://github.com/user-attachments/assets/d6c46935-89df-497f-bab3-3b00a80c55bd)

In the psuedocode I create above The syntax is very easy to understand. Th reason I chose to design a psuedocode was because:

###### Structure and Clarity:

Before getting into the complicated details of real code,psuedocode assisted me in outlining the structure and logic of my future application in simple, human redable terms. I was able to see how each feature such as timer, workout counting, and drink tracking and would function together thanks to this.

###### Easier Collaboration:

A universal instrument for communication is psuedocode. Psuedocode is understandable and accessible for stakeholders and team members.

###### Foundation for development:

For developing this projetc, psuedocode served as a blueprint.Since the logic and flow have already been sketched out, it is considerably simpler to conver psuedocode into actual code.

Overall Psuedocode was a useful tool for designing ans sketching out how my program/code will look.

# Review the mobile app designs with others to identify and inform refinements:


From the feedback I recived from two of my classmates I decied to better my design 

Feeback from "Astin Uka-wanna":


Feedback from "Favour Ajiduah":

![image](https://github.com/user-attachments/assets/64b9b48b-7ef3-4ebc-b007-2df263f4d6eb)


###### Changed made:

I will now show the chaces made in my wirefram from the feeback which I recived.



# Mobile app produced:

home Page produced:

![image](https://github.com/user-attachments/assets/569212dc-268a-493d-b6a5-5e8f088c1fa8)

How it met the design criteria:

The welness spa and gym application's Home page succesfully create a friendly, fitness focused environment. The eye catching background image instantly establishes the ideal mood for users by capturing the energy of the gym. The "Get Started" button which is stands out in the middle of the screen, is an abvious and captivating call to action that encourages people to start their wellness journey. A personal touch is aslo added by the welcoming message, which immediately connects users to the app's mission. All things consideres, the design is eye catching and complemnets the app's fitness and health theme nicely.


menu page:

![image](https://github.com/user-attachments/assets/b3fc9b2a-8302-4c09-a87e-04854d8b5594)


How it met the design criteria:

The wellness spa and gym app's menu page is well designed and easy to use,with obvious ways to acess its three main features, water tracker, workout counter, and timer. Users can easily comprehend and acess any option with a single tap thanks to the button' Large display and veritcal alingnment. The "Back" button at the top allows for seamless movement to the previous screen, while the colour scheme's consistency preserves visual harmony. Users can navigate the app with ease and effective manage their wellness habits thanks to its simple and practical structure.

Timer Page:

Water Tracker Page:

workout counter page:




# Test plan for functionality, usability, stability and performance:


| Test Scneario | Feature | Test Type | Description | Pass or Fail |
|-|-------|-------|-------|-------|
|    The "Get started" button works and moves on to the next page  |    Button   |   Stability    |    To make sure thate the button succesfully leads to the next page "menu page"   |     Pass  |
|   Timer continues counting corrcetly over time    |   Timer    |   Stability    |    To make sure the timer operates pricesly and doesn't crash or freeze for long stretches of time   |       |
|       |       |       |       |       |
|       |       |       |       |       |
|       |       |       |       |       |
|       |       |       |       |       |
|       |       |       |       |       |
|       |       |       |       |       |
|       |       |       |       |       |
|       |       |       |       |       |
|       |       |       |       |       |





# A review to which extend the mobile application met the identified requiremnets:






# Justification of how decisions made during the design process ensured the design for the application will meet indentified requirements:



# Optimised version of the mobile application and how it met the client requirements:


# Evaluate the design and optimised mobile app against client requiremenets



# Demonstarte individual responsibility, creativity and effective self - managemnt in the design, development and revirw of a mobile app.

