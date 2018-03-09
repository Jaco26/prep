This application will draw current weather data from the Open Weather Map API, for locations specified by app users, at three hour increments daily.  Users will specify a zip code (or zip codes...maybe) in which they wish to track weather data.  A user will be able to view any weather data for whichever zip codes they specify, for any time stretching back to the date/time that they hit the "TRACK IT" button. 


*** Base goals ***
- Create a landing page for site to explain the basics of using the app 
- Add authentication to site that allows a user to register
- Create a view for new users to land on after they've logged in
    - it will feature a form for a user to enter a zip code in which they wish to track the weather
- Create a view for users to view tracked weather data
    - Tracked weather data will come back from the database in week-long chunks
    - The view will include a form for the user to specify which span of time for which they would like to view weather history
    - The view will feature a date/time selector interface which users can mouse over and have pertinent data for that date and time display in a table on another part of the window
    

 *** Stretch goals ***

 - integrate google map api to allow map-click location selection for the choosing which area to track.
 - Make an interface to display current weather from the open weather api 
 - Use HTML5 Canvas to create background animations representative of the weather data currently being viewed