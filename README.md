# CS360_MAaP

*Briefly summarize the requirements and goals of the app you developed. What user needs was this app
designed to address?

-The requirements of the app I developed were to track users weight. Keep track of the users goal weight
and to provide a login system and sms notifications for the users. The user would be able to input a 
goal weight and then track day by day their progress. 

*What screens and features were necessary to support user needs and produce a user-centered UI for 
the app? How did your UI designs keep users in mind? Why were your designs successful?

-The screen I began with was your usual login screen with the title of the application and an editable
Username field and an editable Password field. A create account button and a login button. The second
screen initially was a sort of menu to get you to the weight screen however ended up changing that to
have the table for weight information be on the same screen and be able to add to the table from there. 
I did this in order to reduce the number of screen changes to make navigation easier. 

*How did you approach the process of coding your app? What techniques or strategies did you use? How 
could those techniques or strategies be applied in the future?

- I approached the coding for this app by first starting with the design and layout of the app. I created
 the login screen as well as the main app screen that took in user weight and displayed the table.
 Once the layouts were created I was able to then create how the app usages interact with one another
 and display. Implementing the SQLite database into a scrollable field was a good choice to keep the
 information on display while limiting needed space to view tha information. This can be used in the
 future for any sort of data viewing. I could further implement a new screen that shows the full table
 if clicking on the scrollable view.

 *How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

- My testing started with correcting syntax within my code. Once that was done I ran the app in a
 virtual device in debug mode in order to see what is causing an app failure should there be one.
In the end I was unable to get the app to run due to a variable refactor misclick. When creating
the id variable it changed some within the gradle build as well in files I could not find to correct.
This process is important because you can not send an app for use if it does not run.

 *Consider the full app design and development process from initial planning to finalization. 
 Where did you have to innovate to overcome a challenge?

 - One area I had to overcome a challange in was the implementation of SQLite and database creation.
  I had not done this before so reading about implementation and uses was interesting.

 *In what specific component of your mobile app were you perticularly successful in demonstrating your
 knowledge, skills, and experience? 

- I feel the layout of the app showcase my abilities in design and the SQLite implementation is ok
 however overall I am not happy with the outcome of the final app and feel like its vision could
 have been better implemented. 
 
