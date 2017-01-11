# 100 Days Of Code - Log

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



