## Activity: React Routing - Star Wars API - Pair Programming
![Header Mockup screen shot](https://github.com/carlotapearl/React-Dynamic-Routing-Star-Wars-API/blob/master/images/header.png)

## App Description  
In this project, you will add dynamic routing to the Star Wars API explorer app. To achieve this, you will need to implement:
* exact and dynamic routing
* links
* browser history
* component nesting
* conditional rendering (details page)
We have set up the basic structure and functionality of the app for you.

## Instructions  
The following functionality still needs to be implemented:
1. Routing, including an exact route to the home page.
2. Dynamic routing to 'details' page. This route should have a path set to /details/, plus the following parameters: endpoint and id.
3. Browser history.
4. Links and `NavLinks`.
5. Component nesting in `BaseLayout`
6. Component imports in `BaseLayout`

You'll be working with the following files:
* index.js
* layouts.js
* explorer.js
* people.js
* starships.js
* films.js
* details.js

There are detailed instructions in each file.

### Routing Instructions  
* Routing logic needs to be located in index.js.
  * Import `BrowserRouter`, `Route`, `Switch` from react-router-dom.
  * Import additional pages.
  * Nest `BaseLayout` within `BrowserRouter`.
  * Nest `Switch` within `BaseLayout`.
  * Nest `Route` components within `Switch`
  * Set paths for each Route component.
  * Set home page path using exact.
  * Set a dynamic route to /detail/ with the following additional parameters: endpoint and id.
  
* NavLinks
  * Import `NavLink` in `BaseLayout`.
  * Set appropriate `NavLinks` in the nav.
  * Set dynamic NavLinks to the details page for each of the component's li items (People, Starships, Films).

## Details page
  * The url needed for the API fetch call needs to be constructed using the following:
    *`this.props.match.params.endpoint`;
    *`this.props.match.params.id`;
  * Set the following states (componendDidMount): 'details' and 'endpoint'.
  * You will need to share the following props with the View child component: details and endpoint

## Getting started  

1. Download the zip file, and place where you keep projects
2. Change directories into the project
3. Install the dependencies - `npm install`
4. Fire up the server - `npm start`

## Mockup  
Home Page

![Home Page Mockup screen shot](https://github.com/carlotapearl/React-Dynamic-Routing-Star-Wars-API/blob/master/images/home.png)
People
![People Mockup screen shot](https://github.com/carlotapearl/React-Dynamic-Routing-Star-Wars-API/blob/master/images/people.png)
Films
![Films Mockup screen shot](https://github.com/carlotapearl/React-Dynamic-Routing-Star-Wars-API/blob/master/images/films.png)
Starships
![Starships Mockup screen shot](https://github.com/carlotapearl/React-Dynamic-Routing-Star-Wars-API/blob/master/images/startships.png)

## Your role as a student
Articulate their ideas as best you can. Try to facilitate effective collaboration with your paired student. Be willing to debate strategies for how best to approach your challenge, but don’t allow endless debate to keep you from making progress. Keep your eye on the clock and try to work yourself through the challenge at a reasonable pace. You and your partner should share the responsibility for authoring ideas and code. Finish your challenge and make certain that you call talk someone through the logic and strategies implemented by your group.
