# Online + Offline Budget Tracker

[Check the live application](https://pacific-journey-32299.herokuapp.com/)

This application was adjusted from an existing Budget Tracker and was improved to allow for offline functionality.

<img src= "https://github.com/Hannybiggs/online_offline_budget_tracker/blob/main/Assets/Screenshot%202021-07-09%20143941.png">

## How to Use:
To use the user inputs their transaction name, transaction amount, and chooses to add the amount or subtract the amount from the running total. The amount is then updated in the chart down below and shows the trend over time. Additionally, it is added to the table directly under the transaction input.

## Goals when undertaking:
- Retain the existing functionality of the online budget tracker
- Commit to Github frequently to keep track of progress
- Add needed code to enable offline functionality 


## Adjustments for offline functionality - enable access to cache
- Add db.js - checks database, save records, fetches, etc. 
- Add service-worker.js - contains files to cache, activates the needed service worker
- Add manifest.webmanifest


## Results
The budget tracker functions as intended both online and offline. When accessing the budget tracker online it can be accessed via the live Heroku link (found at the top)
