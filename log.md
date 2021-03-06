# 100 Days Of Code - Log

### Day 44: February 24, 2017
* Learned how to follow links and handle paging with [Scrapy](https://scrapy.org/)

### Day 43: February 23, 2017
**Today's Progress**: 
* Scraping easy content with [Scrapy](https://scrapy.org/)

### Day 42: February 22, 2017
**Today's Progress**: 
* Recherche and Tutorial Project for [Scrapy](https://scrapy.org/)
* Wrote my own Spider for a different web site to see if I can do it on my own.

**Resources**: 
* [Tutorial to scrape StackOverflow Questions](https://realpython.com/blog/python/web-scraping-with-scrapy-and-mongodb/)


### Day 41: February 20, 2017
**Today's Progress**: 
* Found a few good articles about progressive web apps and did a little recherche. I'm thinking of creating a small app to prove and test what I read. 

### Day 40: February 19, 2017
**Today's Progress**: 
* Working on the auto-login after the account verification… I got some problems with generating the token within a feathersjs hook.

### Day 39: February 18, 2017
**Today's Progress**: 
* recherche about how to authenticate a user from the backend and send the generated token to the frontend. I need this to automatically sign in a user after he verifies his account.


### Day 38: February 17, 2017
**Today's Progress**: 
* refactored the ui (moved from bootstrap to [react-bootstrap](https://react-bootstrap.github.io) and [react-router-bootstrap](https://github.com/react-bootstrap/react-router-bootstrap)
* made changes to make the frontend more mobile friendly
* fixed some bugs in the work flow

**Link to work**: 
* [react-feathers-boilerplate](https://github.com/areiterer/react-feathers-boilerplate)
* [TRY IT LIVE](www.reiterer.lederhaas.st)

### Day 37: February 16, 2017
**Today's Progress**: 
* Completed the PM2 configuration for the backend
* Added a loading indicator to the frontend
* Fixed my web server which threw a 404 error as soon as you navigated directly to a link (a .htaccess modification did the work)

**Link to work**: 
* [react-feathers-boilerplate](https://github.com/areiterer/react-feathers-boilerplate)
* [feathers-demo](https://github.com/areiterer/feathers-demo)
* [TRY IT LIVE](www.reiterer.lederhaas.st)


### Day 36: February 15, 2017
**Today's Progress**: 
* Today I finished the email verification / resend email verification part and checked everything in.
* Also I read about PM2 configuration, so that I can use environment variables on the production environment.

**Link to work**: 
* [react-feathers-boilerplate](https://github.com/areiterer/react-feathers-boilerplate)
* [feathers-demo](https://github.com/areiterer/feathers-demo)


### Day 35: February 14, 2017
**Today's Progress**: 
* Finished refactoring the login page - now it should be able to handle different actions like "verify", "resendVerify", etc.
* If a user has not verified his email address, he is not allowed to log in.
* Worked on the "resend verification mail" routine. I got the UI and the (redux-)actions but I'm struggeling with the backend. Somehow the authManagement-Service of FeathersJS behaves different than I thought. I am expecting a plain object with the user data (which works when calling the notifier by myself from a hook after a new user is created). If the service route is called from the outside and authManagement comese into play, I get something much bigger. It contains the data of my user, but it is nested in a lot of crap. 

**Plans for tomorrow**: 
I want to finish this by tomorrow, so that after registration, a user receives an email to verify the email address. Also, if a user tries to log in without having verified his email address, he should be able to re-send the verification mail.

**Resources**: I use the following resources to build the verification part between backend and frontend:
* [FeathersJS Docs - Authentication/Management](https://docs.feathersjs.com/v/auk/authentication/management.html)
* [How to set up email verification in FeathersJS](https://medium.com/@codingfriend/how-to-setup-email-verification-in-feathersjs-72ce9882e744)
* [How to set up email verification in FeathersJS - Client Side](https://medium.com/@codingfriend/how-to-setup-email-verification-in-feathersjs-2-client-side-6082ce0da55e)

### Day 34: February 13, 2017
**Today's Progress**: 
* Did some refactoring and bugfixing on the mail-verification of react-feathers-boilerplate. There is still much to do on the client side regarding the general flow of the verification process / resending of the verification mail / etc.

### Day 33: February 7, 2017
**Today's Progress**: 
* Worked on the react-feathers-boilerplate: Started to change the Login route to support email verification and other possible actions like "Password reset", "Resend Mail Verification", "Change email address", etc.

### Day 32: February 6, 2017
**Today's Progress**: 
* Learned how to deploy and operate a NodeJS backend with [PM2](http://pm2.keymetrics.io)
* Built a verification service for new users (email verification) for the [feathers-demo](github.com/areiterer/feathers-demo) - will check this in as soon as it is finished.

### Day 31: February 5, 2017
**Today's Progress**: 
* Introduced [react-notifications]() to the auth-demo
* Refactoring and code cleanup
* Renamed the auth-demo to react-feathers-boilerplate

**Thoughts**:
Today I found out, that everything I had done for the react-auth-demo is reusable for future projects. Since I kept it as clean as possible, it can be used as a boilerplate for new projects. Therefore I decided to transform my auth-demo to a boilerplate, which I want to use for my next projects.

**Link to work**: 
* [react-feathers-boilerplate](https://github.com/areiterer/react-feathers-boilerplate)

### Day 30: February 4, 2017
**Today's Progress**: 
* Finished the PR for [login-flow](https://github.com/mxstbr/login-flow).
* Transformed registration functionality to redux actions (react-auth-demo)

**Link to work**: 
* [Pull Request for login-flow](https://github.com/mxstbr/login-flow/pull/30)
* [react-auth-demo](https://github.com/areiterer/react-auth-demo)


### Day 29: February 2, 2017
**Today's Progress**: 
* Still working on the PR for [login-flow](https://github.com/mxstbr/login-flow). Basic functionality is finished - some
code cleanup and styling is still necessary.
* Modified a wordpress template for a friend

**Thoughts**: At the moment it's hard to find the time and the concentration for the challenge.
I may reduce the effort a little bit for the next days to get my brain free and keep up the work.


### Day 28: January 31, 2017
**Today's Progress**: 
* Worked on a PR for [login-flow](https://github.com/mxstbr/login-flow)

### Day 27: January 30, 2017
**Today's Progress**: 
* Introduce redux to react-auth-demo
* Create actions for login / logout
* Refactor components

**Thoughts**: Today was a good day. I could refresh my knowledge about [redux](https://github.com/reactjs/redux), put it in the demo app
and connect the wires. Also I put a little effort in cleaning up my codebase. 

At this moment the functionality of the demo application includes logon / logoff and a page which is
only displayed to logged on users. Tomorrow I want to 
* add an action for the sign up procedure
* develop a ErrorMessage component to display error messages. Also I have to add some functionality to handle errors - 
I didn't consider this for now.


**Link to work**: 
* [react-auth-demo](https://github.com/areiterer/react-auth-demo)
* [feathers-demo](https://github.com/areiterer/feathers-demo)

### Day 26: January 29, 2017
**Today's Progress**: 
* Prepared Backend to support Signup and Login
* Added a service to serve demo data only to authorized users 
* Learned about router redirecting (e.g. after Login / Sign up)
* Preparation to introduce redux to the react app

### Day 25: January 28, 2017
**Today's Progress**: 
* Set up a raspberry pi as a development web server
* Recherche about Auth with FeathersJS

### Day 24: January 27, 2017
**Today's Progress**: 
* Further requirement analysis and spec writing for the next app
* Created boilerplate for a demo app to practice registration/login with ReactJS and FeathersJS
* Recherche about Authentication / Registration&Login Flows 

### Day 23: January 26, 2017
**Today's Progress**: 
* Did some codewars 
* FreeCodeCamp Algorithm Challenges
* Planning & Requirements analysis for the next side project.


### Day 22: January 25, 2017
**Today's Progress**: 
* Did some codewars 

### Day 21: January 24, 2017
**Today's Progress**: 
* Moved Wolo to a private repository (sorry for that)
* Started requirements analysis for my next side project: (A contact management app.?) 

### Day 20: January 23, 2017
**Today's Progress**: 
* Did some major refactoring on the Statistics Component (and Components below)
* Added functionality to delete goals and activiites

**Link to work**: 
* [Wolo on GitHub](https://github.com/areiterer/wolo)


### Day 19: January 22, 2017
**Today's Progress**: 
* Added functionality to set new goals
* Refactored the Components, did some splitting
* Built the functionality to calculate the percentage - this is not finished yet, will commit tomorrow

**Link to work**: 
* [Wolo on GitHub](https://github.com/areiterer/wolo)

### Day 18: January 20, 2017
**Today's Progress**: 
* Fixed a bug in the circle percentage component, which appeared when you put in a percentage less than 50 percent.

**Link to work**: 
* [react-native-percentage-circle](https://github.com/areiterer/react-native-percentage-circle)

### Day 17: January 19, 2017
**Today's Progress**: 
* Improved styling for other scenes than Statistics/Goals
* Did some slight refactoring, added master data like action types into the api to get a central point to fetch data
* fixed a bug when selecting the date
* Created the pull request which adds functionality to change the inside color of the circle for [react-native-percentage-circle](https://github.com/JackPu/react-native-percentage-circle) 

**Link to work**: 
* [See Wolo in action](http://www.giphy.com/gifs/l3q2GnLvx5C0ze3lu)
* [Wolo on GitHub](https://github.com/areiterer/wolo)

### Day 16: January 18, 2017
**Today's Progress**: 
* Added support for Icon.ToolbarAndroid from [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)
* Introduced the toolbar to the AddActivity scene and removed the buttons for Add and Cancel.
* Added module [react-native-percentage-circle](https://github.com/JackPu/react-native-percentage-circle) for the statistics scene
* Built a mock scene to get a feeling for the look of the app (and as a preparation for styling).
* Use icon set [MaterialDesignCommunity](https://materialdesignicons.com/) with the help of react-native-vector-icons
* Found a suitable [color pallete](https://www.materialpalette.com/blue-grey/lime) for the app and began to style it.

* Forked [react-native-percentage-circle](https://github.com/JackPu/react-native-percentage-circle) because it sets the
background color in the middle of the circle automatically to white - at the moment I copied the control directly into my 
project and made the changes so that I am able to use it.


**Link to work**: I did not finish the work on the design yet, I will do the tidy up tomorrow. At the moment the StyleSheets and styles ess and are
quite a mess and scattered all over the place. But as a proof for my work, here is a Screenshot:

![Statistics Screen](img/DesignStatistic.png)

### Day 15: January 17, 2017
**Today's Progress**: 
* Replaced TextInputs for date and activity type with DatePicker and <Picker /> to provide a better user experience
* Began to clean up the AddActivity scene and added a little bit of styling

**Link to work**: [Wolo on GitHub](https://github.com/areiterer/wolo)


### Day 14: January 16, 2017
**Today's Progress**: 
* Replaced the temporary storage with AsyncStorage - which is the official module for a simple permanent key/value storage. 
I used [react-native-storage](https://github.com/sunnylqm/react-native-storage) for it, which I thought was the best wrapper for my requirements.

**Thoughts**: After some self introduced problems I got it running - well you should read the docs carefully before making
assumptions of how things work. Over all I spent some time to find a good wrapper for the AsyncStorage. It provides functionality
to save/update, fetch and remove items from the key/value store. The reason why I chose this library was, that it doesn't only
store the data within defined keys, but also stores additional IDs. This way you can fetch just one item out of the list instead
of fetching the whole stringified array and parse the respective item out of it.

**Link to work**: [Wolo on GitHub](https://github.com/areiterer/wolo)


### Day 13: January 15, 2017
**Today's Progress**: 
* Cleaned code from yesterday and commited the progress to GitHub
* Introduced a simple "API" to temporarily store activities and provide an interface to fetch / add / update activities. 
(The temporary storage part will be replaced with a permanent local storage soon)
* Changed "Add activity" scene to provide input fields. These input fields will be replaced by better controls soon to reduce
the amount of data the user has to type in when adding a new activity.

### Day 12: January 14, 2017
**Today's Progress**: 
* Solved problem from yesterday - Floating Action Button is on the right spot now
* Created a custom TabBar for the react-native-scrollable-tab-view with Icons - this one was a little bit tricky first,
but worked out in the end.

Tomorrow I want to clean the code and check in the current solution. Afterwards I will focus on the add functionality
and kind of a local data storage.

### Day 11: January 13, 2017
    
**Today's Progress**: 
* Added a tabbed view for the main scenes. Here are the components I tried:
  * [react-native-tab-view](https://github.com/react-native-community/react-native-tab-view): I liked it because of the
  smooth animations and the possibility to switch the tab bar between the top and the bottom (read about this in "thoughts") 
  * [react-native-scrollable-tab-view](https://github.com/skv-headless/react-native-scrollable-tab-view): I think I stick with it 
  because it is easier to use (less code) and it should fit my needs. We will see when it comes to icons in the tab bar.  
* Replaced the AddButton Component with [react-native-action-button](https://github.com/mastermoo/react-native-action-button)
which is a fully functional "Floating Action Button" which is compliant to the Material Design Guidelines.
* Decided to use [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) because it is cross platform 
compatible and it consists of a bunch of awesome icons.

**Thoughts:** Today I spent much time on trying tab bars and reading the [Material Design Guidelines](https://material.io/guidelines/components/bottom-navigation.html).
The latter was also the reason why I changed the tab bar to the bottom. According to the guidelines, bottom navigation
is the preferred navigation pattern between top-level scenes. On the contrary, tabs are used to group content into different views.
While I tried to find a control for a bottom navigation bar, I found out that a tab bar at the bottom will do the job.
During my research I also found another tab control, which I tested afterwards.

I won't check in my work today. It is not finished and I am still facing issues:
* I'm not sure which tab control suits best
* I did not find out how to combine the Floating Action Button correctly with a Bottom Navigation Bar: 
According to the guidelines, the Bottom Navigation Bar has to have 56dp height. The FAB seems to have an offset
of 30dp from the bottom end of the screen. I'm not sure if it is okay to increase the offset to stay above the control, but that's 
something for tomorrow.


**Link to work:** Since I did not check in, just a giphy [Screen Video](http://www.giphy.com/gifs/l3q2FvS4gnKakJMDS)


### Day 10: January 12, 2017
    
**Today's Progress**: 
* Added Navigator to provide functionality to change scenes (Screens/Pages are called scenes in React Native)
* Added placeholder Components for "Statistics" and "Add new Activity"
* Built navigation routes between the three scenes.
 
**Thoughts:** Took me some time to understand how Navigator is working but in the end it was quite easy 
for my basic routes. 
I had some help from a very good blog post on [Medium](https://medium.com/react-native-training/react-native-navigator-navigating-like-a-pro-in-react-native-3cb1b6dc1e30#.jvy9qjbpp)
where I could find everything I needed. Tomorrow I will replace the blue buttons with a navigation bar. I just put the 
buttons in because I wanted to test it as quick as possible. 

**Link to work:** 
* [WorkoutLog](https://github.com/areiterer/wolo)
* [See it in action](http://www.giphy.com/gifs/l3q2Rnk6bdvAzJ7KU)

### Day 9: January 11, 2017
    
**Today's Progress**: 
* Added an "Add Activity" button - similar to the one I created yesterday - to the app. Since I just need one add 
function, it does not display more buttons on click. Instead it just calls a passed function.
* Did some recherche for React Natives Navigator. 
 
**Thoughts:** Today there was not much outcome to show because I spent more time on recherche for the Navigator.
It is necessary to display different Screens (or "Scenes") and it behaves different to the Router I know from React.
Navigator keeps a stack of Scenes which are pushed and popped - I found out how to do this, but I still don't know 
how to define a different Scene to be rendered. Tomorrow I want to finish the Add-Scene - this means I have to find
out how to push the "Add" Scene to the stack and render the form.  

**Link to work:** [WorkoutLog](https://github.com/areiterer/wolo)

### Day 8: January 10, 2017
    
**Today's Progress**: 
* More work on the design of Wolo - still on paper. I want to have an idea of how all the screens look like and which 
functionality they provide. Also I want to get an overview of all possible transitions between the screens.
* Created a sample app with react native to rebuild the "Add" button from the google mail / google calendar app. 
![ButtonControl](img/ButtonControl.gif)

* Started with coding the screen for the activity history. Learned much about ListView and flex when styling the basic 
design.

**Link to work:** [WorkoutLog](https://github.com/areiterer/wolo)


### Day 7: January 9, 2017
    
**Today's Progress**: 
* Decision to develop a Workout Logging App with React Native
* Worked on the requirements
* Initiated a react project and set up a new GIT project
* Tested and tried React Native and debugging on the smart phone
* Played around with the [KitchenSink](https://github.com/GeekyAnts/NativeBase-KitchenSink) app from [NativeBase](http://nativebase.io/) 
* Started to build a new button component - will check this in separately as soon as I can show something.

**Link to work:** [WorkoutLog](https://github.com/areiterer/wolo)


### Day 6: January 8, 2017
    
**Today's Progress**: 
* Played around with CSS until I got a useful design for mobile and desktop UI
* background color changes by cloudyness (provided by OpenWeatherMap API)
* weather icon changes depending on the weather - used [Meteocons](http://www.alessioatzeni.com/meteocons/) for that.

**Thoughts:** I really suck in designing things :) But slowly I get a feeling where to get ideas from and how to build semi
good looking UI without being a graphics designer. 
At this point I label the WeatherMeter project as finished but will work on it for improvements or extensions if something 
comes to my mind.

At this point I try to find a new project for the next days - maybe something with React Native and a NodeJS backend.


**Link to work:** [WeatherMeter](https://github.com/areiterer/react-weathermeter)

### Day 5: January 7, 2017
    
**Today's Progress**: 
Added Bootstrap to WeatherMeter and tried to get everything in a nice shape - well this did not work out like I
wanted it to. So I will have to work on it again tomorrow. 

**Thoughts:** I am really bad at designing things - but I want to finish WeatherMeter with a quite good design - 
 so I may put a little bit more effort in it than I planned to do. 

### Day 4: January 6, 2017
    
**Today's Progress**: 
* Added a input field for specific location search
* Added Values for wind speed, humidity and air pressure
* Changed labels for min/max temperature, humidity, air pressure and wind speed to icons

**Thoughts:** The app is still ugly but the main functionality is almost finished now. Next steps will be 
the big icon for the current weather state and overall styling. 

**Link to work:** [WeatherMeter](https://github.com/areiterer/react-weathermeter)

### Day 3: January 5, 2017
    
**Today's Progress**: 
Since I found no time slot for a quiet hour of coding on the WeatherApp, I decided to do some Codewars during my 
morning and evening commute. Since I go to work by train for ~40 minutes per direction, there is at least the possibility
to stay on track by completing some challenges there.

**Thoughts:** I really like codewars - especially because you can compare your code to the solutions of other coders as 
soon as you finished a kata.
 

### Day 2: January 4, 2017

**Today's Progress**: 
This day I refactored the WeatherData component to take every single piece of information as a separate prop.
I did this because this way I can make the WeatherData component as pure and predictable as possible.

Also, I put some logic into the root "App" component to retrieve the current geolocation and fetch the current weather 
data from OpenWeatherMap.

**Thoughts:** Today's tasks were pretty straight forward. I still did not spend any time on design or styling - I want at least finish the basic functionality
first, so that I can find the right position for every piece of information I want to show.

As my next steps I plan to 
* add a input field so that users can enter different locations
* display humidity, wind speed, air pressure, etc.
* introduce icons instead of the labels
* add a big icon somewhere to display the current weather

**Link to work:** [WeatherMeter](https://github.com/areiterer/react-weathermeter)

### Day 1: January 3, 2017

**Today's Progress**: 
I started with the FreeCodeCamp "Show the Local Weather" project as my first project of this challenge.
At the moment, it just shows sample data. I added some test data from the API and a overall component which shows the 
name of the city and the temperature.
This will be refactored soon, as it is just my starting point.

**Thoughts:** I first tried to do this in CodePen - since it's a FreeCodeCamp project, but I soon decided to work locally 
and storing my progress on GitHub because I may want to extend the app later on and get a folder architecture I am more used to.

**Link to work:** [WeatherMeter](https://github.com/areiterer/react-weathermeter)



