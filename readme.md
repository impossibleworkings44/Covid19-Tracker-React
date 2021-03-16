# Getting Started with Covid19 Tracker React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
This is a Covid19 React App build using React Hooks, Material UI and deployed using Google Firebase also In this we have chartjs for graphs and Leaflet for map
and also used Numeral js for i.e. javascript library for formatting and manipulating numbers.


# Follow steps to make it run on your machine :-
Prerequisite : Node.js must be installed on the machine

Clone the project
1) In CLI write npm install
2) In CLI write npm start

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `Fetching api`

In this project we are fetching api from disease.sh
For data of all countries, link : https://disease.sh/v3/covid-19/countries

### `Packages used command`

1) npm i react-chartjs-2 chart.js//reactchartjs
2) npm i numeral
3) npm i leaflet
 
 Its just for reference you can directly do npm install to download all required packages
 
 ### `Deploying on google Firebase`

 1) In CLI write npm i -g firebase-tools
 2) firebase login
 3) firebase init ,then you will see the below options and choose hosting
 ![Capture](https://user-images.githubusercontent.com/76193921/111273832-4bb0f900-865a-11eb-86fa-da8be8c0b67a.PNG)
 
 4) Choose existing project  
 5) Then it will ask what do you want to use as your public directory ?
    -> Write build 
    
    ![Capture2](https://user-images.githubusercontent.com/76193921/111274119-9df21a00-865a-11eb-8e79-296dbafaf3ee.PNG)
 
 6) In CLI write npm run build
 
 7) then finally write firebase deploy
 
 8) done !!

   
### Sneak Peak
The app is deoployed at this link, you can checkout it out here : 
https://covid-19-tracker-1574c.web.app/


image.jpg
![ss](https://user-images.githubusercontent.com/76193921/111274267-d09c1280-865a-11eb-8fa7-d4b3075ba177.PNG)



