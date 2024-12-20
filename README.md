# [Sabah Bus Route Chart](https://amasraff.github.io/sabah-bus-routes/)
Currently there are no known public bus transit route created or made to public.

## Current problem
There are no known routes where the bus driver will take except by asking them directly or others who often commute by them. Even with that, the information are still quite vague. As of now, Google Maps doesn't support "transit" feature in this city, hence leaving the current public transit in the shadows. There are bus stops being erected, however that doesn't mean there will be any bus that will take the route to there.

## Aim
To create public bus transit map chart to assist anyone who are planning to commute via these bus transits. By just using google map links.

## Bus Transit Routes?
They're divided into NORTH WEST SOUTH EAST OTHER INTERCITY regions and each one of the bus' destination are colour coded. Their specific routes and destination are then designated with number paired with a letter. E.G [16A] that goes to Tanjung Aru area/region.

## Contributing
You're free to contribute to this project by sending a pull request. As of now there are no good formating to use for each of the regions yet. Do refer to the contributing.md file

## Limitation
This will consume time and money in order to observe record and memorise the route that they will take reliably. Of course, the drivers can be asked on which route they will take by showing them the map and let them show us the route that they take. Some of the routes will undef/incomplete to indicate that the route are not confirmed yet. I wanted to make localisation simple without data redundancy especially on the google map link part for easier data maintenance and sanitization, but I'm very bad with json + javascript. If you're keen on changing it to make it better and efficient, feel free to do so

# License
This is under personal license

# Privacy Policy
I prohibit the use of any data found in this repo/site to take advantage, extort, or bring any harm to the well-being of the users as well as the public bus drivers. This small project are meant to help anyone who wanted to commute via public buses.

# FAQ

## Aren't they supposed to be centralised?
No, The public bus transit in Kota Kinabalu (KK) are clustered, meaning that almost each one of the bus drivers are independent to one another. The chart of their routes are not maintained even by the city hall I don't think.

## Fares
They're generally a minimum of MYR2.00 upon boarding and it will increase on farther destination. Just ask the driver how much the fares by stating where you boarded the bus. Don't worry, they won't scam you.

## Schedule
Generally they don't have any departure schedule, some of the busses may take longer while some take shorter time to depart. It will be stated on each destination's note/condition.

## Why there are 2 routes?
Inbound and Outbound will have slight deviation to their routes due to how the roads are laid out

## `undef` and `partial`?
`undef` means the the data/information are unknown. Set as undef if the data is only obtained once. 
`partial` means the data gathered for at least multiple times, at least twice, usually the case of their end to end routes.
