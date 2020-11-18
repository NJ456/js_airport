# Airport Challenge in JavaScript

## Introduction
This is the JavaScript attempt at the Airport Challenge. The main parts are:
- plane.js
  - the JavaScript module for the Plane class
    - land()
    - takeOff(destination airport)

- airport.js
  - the JavaScript module for the Airport class
    - land(plane)
    - takeOff(plane)
    - isItStormy()
    - isHangerFull()

- weather.js
  - the JavaScript module to randomise the weather
    - look()

- feature.test.js
  - the feature testing file, basically runs a number of scenarios


## Run / Test the solution
fork the repository, then run the feature tests from the root directory
  - ```$ node src/feature.test.js```
    - creates a number of objects
    - Plane01 takes off from initial airport (airport01)
    - plane01 lands at second airport (airport02)
    - Move plane01 back to airport01 for additional tests
    - check that plane02 can't take off with incorrect destinations set
    -  check that a plane can't land if the airport hanger is full


### Next steps
- visual (HTML) dashboard showing status of objects?
