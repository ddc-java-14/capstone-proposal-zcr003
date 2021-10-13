## Summary

My proposed capstone project is an app for live music lovers that are interested in finding out information about a venue they are attending/in general.

This application would allow users to search for their favorite venues/find new venues across the country (maybe just ABQ to start) and access information such as: Business hours, Food options, Alcohol selection, Security policies, Current entertainment offerings, Nearby hotels, Hot spots, and much more! 



## Intended users

- A user that is following their favorite band and travelling to a city for their first time.

>My favorite band, Phish, is always travelling to new cities and venues, and I don't know where to begin in a new city. I want an app that gives me info about the city/venue I'm visiting in one concise place so I don't have to individually search for all that information. 


- A local that is looking for a new place to see music and get out for a night. 

> As a local music lover, I'm always looking for new exciting venues and events to attend. I want an app that tells me new venues to check out and maybe some new info about the ones I regularly attend without having to put in too much effort.









## Client component

### Functionality

A user will be able to: 

- Search for a nearby venue or for one of their choosing.
  - Once a venue is found it will be shown on a map with information such as: 
    - Hours of Operation
    - Food Options 
    - Alcohol Selection 
    - Covid policies
    - Security policies
    - Other nearby venues, food, and hot spots. 
    - etc. 
- Navigate through menus that explain information about the venue, along with other relevant info.
- Add frequented venues to a favorites folder and get updates from their favorite venues.



### Persistent data
- Persisting previous site activity (e.g. storing the contents of a previous session)
- Saving some data and assets locally so a site will be quicker to download, or be usable without a network connection.
- Saving web application generated documents locally for use offline such as direction to the venue. 




### Device/external services

- Location
- Map Services
- Real-time Weather


## Server component
               

### Functionality

- Venue search
- Access to venue information
- Cloud storage of favorite Venues




### Persistent data
- Venue information
  - food selection
  - alcohol selection
  - events
  - hours of operation
  - security policies
  - covid policies
  - etc.
- Favorites
- Search History
- Google Sign-in
- Secondary data
  - nearby hotels
  - hot spots
  - restaurants
  - etc.


    
### External services

- Search function
- Spring Security
- API for finding the venue information

    
## Stretch goals/possible enhancements 

- Potentially connect to ticketing service to allow users to purchase the cheapest available tickets within the app.
- Ability to like your favorite bands and receive notifications when they're nearby or coming soon.
- Implementation of friends list to share venues with friends and add points-of-interest for other users to see and/or comment on or update.  