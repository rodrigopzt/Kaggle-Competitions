This is still a draft - WIP!

# Competition Objective

Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.

Help save them and change history!


## Description of the data

<br />

**Variable Notes**

**PassengerId:** A unique Id for each passenger. Each Id takes the form `gggg_pp` where `gggg` indicates a group the passenger is travelling with and `pp` is their number within the group. People in a group are often family members, but not always.

**HomePlanet:** The planet the passenger departed from, typically their planet of permanent residence.

**CryoSleep:** Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. 
Passengers in cryosleep are confined to their cabins.

**Cabin:** The cabin number where the passenger is staying. Takes the form `deck/num/side`, where side can be either `P` for *Port* or `S` for *Starboard*.

**Destination**: The planet the passenger will be debarking to.

**Age:** The age of the passenger.

**VIP:** Whether the passenger has paid for special VIP service during the voyage.

**RoomService, FoodCourt, ShoppingMall, Spa, VRDeck:** Amount the passenger has billed at each of the *Spaceship Titanic*'s many luxury amenities.

**Name:** The first and last names of the passenger.

**Transported:** Whether the passenger was transported to another dimension. *This is the target of the project.*


### Submissions

Best submission: 0.80336 - LightGBM Model

My submissions on the competition so far


```console
fileName        date                 description                                      status    publicScore  privateScore  
--------------  -------------------  -----------------------------------------------  --------  -----------  ------------
predictions.csv  2023-03-04 16:59:48  LightGBM tuned, no scaler                       complete    0.80336
```

## Competition Link

* [DataRepository](https://www.kaggle.com/competitions/spaceship-titanic/data) - Link to the data repository.

## To-Do

- Add a repo structure section to Readme file
- Add a summary table on all features present in the dataset 
- Test different algorithms and hyperparameter optimization techniques
- Use a standard scaler in train / test datasets