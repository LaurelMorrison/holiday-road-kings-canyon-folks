# Holiday Road from Nashville

As a team, we created a site to help build a trip to a national park, with an option to add eateries or attractions along the way. We focused the website on wheelchair-accessibility, and making sure people had the information they needed to have independence while traveling.

## My contributions

I focused on the eatery database to make sure that module was functioning and adding to the itinerary. I also helped to design out the CSS and format the HTML.

## Feature List

### Building the Itinerary

* List all national parks in a dropdown. When user chooses one, display the name of the park in the **Itinerary Preview** section.
* List all bizarraries in a dropdown. When user chooses one, display the name of the bizarre attraction in the **Itinerary Preview** section.
* List all eateries in a dropdown. When user chooses one, display the name of the eatery in the **Itinerary Preview** section.

### Itinerary Details

* In the **Itinerary Preview** section, there should be a button labeled _Save Itinerary_. It should be disabled by default.
* When the user has selected a park, and the name of the park has been added to the **Itinerary Preview** section, query the Open Weather API and display the 5 day forecast for that location. This will allow the user to see if they want to make the trip soon.
* When the user adds any item to the **Itinerary Preview**, there should be a _Details_ button next to the name of the item.

* When the user clicks on any detail button for an itinerary item, a dialog box should be presented to the user with more information about that item _(description, address, etc...)_.
* Once the user has selected a park, a bizarre attraction, and an eatery, the _Save Itinerary_ button should be enabled.
* When the user clicks the _Save Itinerary_ button, the chosen items should be saved as an object in your own, local API that is managed by `json-server`. Each saved itinerary should appear in an aside bar on the right side of the UI.


## National Park Service API

* API home: https://www.nps.gov/subjects/digital/nps-data-api.htm
* API documentation: https://www.nps.gov/subjects/developer/api-documentation.htm

### List All Parks

https://developer.nps.gov/api/v1/parks?api_key=your_api_key

## Weather API

https://openweathermap.org/api

## Bizarre Destination

http://holidayroad.nss.team/bizarreries

## Eateries Destination

http://holidayroad.nss.team/eateries


## Personas

## Charles

![](./personas/persona-charles.png)
