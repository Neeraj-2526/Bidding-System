# Bidding-System
Designed a bidding system

* Vendors can come and put their products up for bidding for a given slot within a date and time duration.
* The registered users can visit the page to check the different products (by category), which are up for bidding. They can choose and bid for a product of their choice.
* Each product has a base price, and the bidding for that product can be done with a price which is higher or equal to this base price. A bidding for a lesser price should throw an error.
* At the end of the slot duration for a given product, choose the winner and send a communication to them.

Designed the backend system for this problem.
1. Designed micro-services with <br/>
  a. Well defined API contracts <br/>
  b. Used protocol - REST <br/>
  c. Well defined status code and messages, error handling. <br/>
2. Used Java Springboot backend tech, MySQL and MongoDB databases and designed a clean data model, with solid reasoning.
3. Codebase have good coverage for Unit Tests.
4. Applied design patterns wherever applicable.
