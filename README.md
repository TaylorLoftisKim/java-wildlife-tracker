# _Comic Book Prototyper_

#### _An application that allows users to report sightings of animals in a specific area, 04-08-2017_

#### By _**Taylor Loftis-Kim**_

## Description
_An application that allows users to report animal sightings in any area that happen to be in. The user can report either normal animals or endangered ones. A Timestamp will be saved along side their sighting to then be logged in the data base. Sightings of multiple animals can be seen, as well as multiple sightings of a single animal._


## Specifications

| Behavior                                  | Input                               | Output                                  |
|-------------------------------------------|-------------------------------------|-----------------------------------------|
| Will return instance of a Animal          | "Deer"                              | "Deer"                                  |
| Will return all instances of Animals      | "Deer", "Bear"                      | "Deer", "Bear"                          |
| Will clear List of Animals                | "Deer" --> Animal.clear();          | *List Cleared                           |
| Will instantiate each Animals with an ID  | "Deer", "Bear"                      | 1, 2                                    |
| Will return Animal with Same ID           | "Deer", "Bear"                      | 2                                       |
| Will add a Sighting to Animal             | "Portland, OR"                      | Animal: "Deer" Sighting: "Portland, OR" |
| Will return instance of a Sighting        | Sighting: "Portland, OR"            | "Portland, OR"                          |
| Will return all instance of Sightings     | "Portland, OR", "Seattle, WA"       | "Dear", "Bear"                          |
| Will clear List of Sightings              | "Portland, OR" --> Sighting.clear() | *List Cleared                           |
| Will instantiate each Sighting with an ID | "Portland, OR", "Seattle, WA"       | 1, 2                                    |
| Will return Sighting with same ID           | "Mike"                              | 1                                       |



## Setup/Installation Requirements

* _Clone the repository_
* _Run the command 'gradle run'_
* _Open browser and go to localhost:4567_


### License

Copyright (c) 2017 **_Nathaniel Meyer, Blake Womack, Chance Magno, and Taylor Loftis-Kim_**

This software is licensed under the MIT license.




* `CREATE DATABASE wildlife_tracker;`
* `In terminal, "not in psql", type psql wildlife_tracker < wildlife_tracker.sql`
* `Perform "gradle run" in terminal.`
