
Objective:
  1. Log charging sessions for both residential users and non-residential users. Include in the charge session data the amount of kwhs(kilowatt hours) collected during the charging session.
  2. Provide in the charging sessions page the costs of charging an ev at home and at public charging stations.
  3. Have the app estimate how far the electric car will go on one charge in a trip planner. If the car will run out of energy before reaching the user's destination, then the app should display the nearest charging station to charge.
  4.  Finally, the app should ask the user some questions to estimate how much the user should expect to pay in fueling expenses each month or each year.

Users:
  The majority of my users will be electric vehicle owns who would like to keep track of their fueling expenses and would like to know how to efficiently plan their trips. The remaining user base will be  those who don't own an electric vehicle and are curious about the costs associated with them and would like to compare evs and gas cars.


Issue:
  The issue is that many people don't know the actual cost of driving an electric vehicle. With this app, it will help ev owners manage their fueling expenses and also help inform non-electric vehicle owners the costs associated with driving an electric vehicle.


Files:
  The files that this project will be an index.html, main.scss, main.js, bootstrap, vue.js, and a database. I will also be using a few apis.

Design Objectives:
  My first page will be called Charging Sessions. This page will contain a spreadsheet that will show the user's previous charging sessions and it should also contain a graph showing the fueling costs over time. The second page will be called the Fuel Cost Estimator. This should contain a questionnaire form that will then provide a rough estimate on how much it would cost to charge an electric car based on certain criteria such as the user's zip code, the car's mpge rating and if the person will be charging their car at home or at a public charging station. The third page will be called EV Trip Planner. This page should contain a map and fields for text input such as their starting location and and their destination. The page should also have enough space to include responsive messages based on the user's input.

Data:
  The data will come from multiple sources. Some of these sources will be from a few apis. The first api will be from https://openei.org/wiki/Utility_Rate_Database this api contains the cost per kwh based on the person's zip code. The google map's api https://developers.google.com/maps/documentation/ to get the distance and elevation information for the trip information. The third api I am considering using is open charge map https://openchargemap.org/site. This is to get the location of different charging stations if the user doesn't have access to a residential charging station. I will also use a database to keep track of the users information.

  The user will be able to input the time they charge their car and when they finished. The user will also be able to plan a trip by inputing their current address and a given destination. The user should expect to see a message stating whether or not the user can make it to their destination on one charge or if they should go to a public charging station. Finally, the citizen should be able to fill out a questionnaire which in turn the app will provide the user with a monthly or yearly estimate on fueling expenses.

Inspiration:
  I would like to make a website similar to ev explorer (https://gis.its.ucdavis.edu/evexplorer/#!/locations/startin) in the way that it is able to pull up information from fueleconomy.gov and eia.gov and use that information to calculate the annual vehicle energy costs for the three vehicles used to compare the costs between all electric vehicles and gas vehicles.
