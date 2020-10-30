# PROS and CONS of TDD 
## PROS
* Encourages more modular design in order for the code to be unit testable.
* Encourages development in small chuncks to avoid dependencies for unit testing.
* Collaboration is made easier as unit tests act as sanity checks to make sure your code has not broken others' code.
* Refractoring old code is also made easier because unit tests ensure the code is still working.
* Forces clarity of requirements for inputs and outputs because tests are written.

## CONS
* More overhead because testing is down in parallel with development.
* Dependencies can make testing difficult during the development phase.
* Early refractoring requires test classes to be refractored as well.
* Everyone on the team must maintain their unit tests or else it risks degradation of the system.
