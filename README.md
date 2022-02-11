# swe-inventory-app-starter
React Boilerplate code for SWE Mod-1 Project

## How to use 
1. Fork this repo
2. `npm install`
3. `npm start`
4. In a seperate terminal, `npm run start-dev`
5. Find your bliss!

## Agile Development Plan

### 1.1.1 Agile Development
* Opportunity: PlantShed is one of the most popular plantstores in NYC. Not only do they sell a wide variety of houseplants and flowers, they have a local coffeeshop where customers can enjoy a fresh brew before shopping. PlantShed is hoping to expand into the e-commerce space, where customers can view the inventory of plants, flowers, and coffeebeans and shop from home.

### 1.1.2 Personas
#### Persona #1
* Sarah is a plant lover who is broswing the inventory.
* Needs: to know which plans she can buy
* Frustrations: unable to know full scope of plants on sight alone

#### Persona #2
* Jim is wanting to purchase a Bluestem - is it in stock?
* Needs: to purchase a bluestem plant
* Frustrations: It's his wife's favorite, but he doesn't know where to buy it.

#### Persona #3
* Hailey is a coffee fiend.
* Needs: to buy coffee or face sure collapse
* Frustrations: she currently does not know if there is coffee available at this store

### 1.1.3 Requirements
#### Functional Requirements
| ID | Priority | Description |
| :-----------:| :-----------: |:-----------: |
| FR1 | MUST | show all plants |
| FR2 | MUST | show individual plants |
| FR3 | MUST | show all coffees |
| FR4 | MUST | show individual coffee |
| FR5 | SHOULD | add items to cart |

#### Non-Functional Requirements
| ID | Priority | Description |
| :-----------:| :-----------: |:-----------: |
| NFR1 | MUST | The application code must be documented in a manner that it would be easy for a new developer to understand. |
| NFR2 | MUST | The application code must be written in React. |
| NFR3 | MUST | The application code must be stored in a Github reposistory. |
| NFR4 | MUST | There must be documentation which describes: * how to run the application * features of the application * design <br> decisions * team roles & responsibilities * links to UML use case, class and sequence diagrams * <br> links to the database design * links to a unit test coverage report |

### 1.1.4 User Stories
1. As a user, I can view all plants so I know what's in inventory.
2. As a user, I can view individual plants so I know more specifics.
3. As a user, I can view all coffees so I know what's in inventory.
4. As a user, I can view individual coffee so I know more specifics.
5. As a user, I can add items to cart so I can keep shopping.
6. As a user, I can checkout from cart so I don't need to go in to the store.
7. As an admin, I can add plants to site so inventory can be accurate.
8. As an admin, I can add coffees to site so inventory can be accurate.
9. As an admin, I can edit plants on site so inventory can be accurate.
10. As an admin, I can edit coffees on site so inventory can be accurate.

### 1.1.5 MVP
* User can view homepage and nav bar
* User can click links in navbar to navigate to plants and coffee pages
* User can view individual coffee/plant

