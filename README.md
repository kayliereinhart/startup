# Daily Bread

[My Notes](notes.md)

A meal planning application.


> [!NOTE]
>  This is a template for your startup application. You must modify this `README.md` file for each phase of your development. You only need to fill in the section for each deliverable when that deliverable is submitted in Canvas. Without completing the section for a deliverable, the TA will not know what to look for when grading your submission. Feel free to add additional information to each deliverable description, but make sure you at least have the list of rubric items and a description of what you did for each item.

> [!NOTE]
>  If you are not familiar with Markdown then you should review the [documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) before continuing.

## 🚀 Specification Deliverable

> [!NOTE]
>  Fill in this sections as the submission artifact for this deliverable. You can refer to this [example](https://github.com/webprogramming260/startup-example/blob/main/README.md) for inspiration.

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] Proper use of Markdown
- [x] A concise and compelling elevator pitch
- [x] Description of key features
- [x] Description of how you will use each technology
- [x] One or more rough sketches of your application. Images must be embedded in this file using Markdown image references.

### Elevator pitch

Do you ever start making a recipe and then realize you don't have all the ingredients? Not anymore, with the Daily Bread application. Daily Bread lets you enter recipes, track your ingredients, and plan your meals. The planner tells you if you have enough ingredients to make a recipe, and predicts when ingredients will run out so you know when to go shopping. Users can also share and rate recipes, giving you new ideas for meals.

### Design

Here are images of the different pages on the website.

![Image 1](images/MealPlan1.jpg)
![Image 2](images/MealPlan2.jpg)
![Image 3](images/MealPlan3.jpg)
![Image 4](images/MealPlan4.jpg)

### Key features

- Secure Login over HTTPS
- User can enter recipes
- User can save recipes
- User can rate recipes
- Displays recipes on a Browse page and a My Recipes page
- Notification when users enter or rate a recipe
- User can enter and update on hand ingredients and amounts
- User can enter meals they plan to eat and the day they plan to eat them
- Predicts when ingredients will run out based on on hand amounts and planned meals
- Displays a calendar with planned meals in green if there should be enough ingredients to make them on that day, in red if not

### Technologies

I am going to use the required technologies in the following ways.

- **HTML** - Uses correct HTML structure for application. Eleven HTML pages, shown in the Design section of this README.
- **CSS** - Application styling that uses good whitespace, color choice and contrast.
- **React** - Provides login, displaying other user's recipes, applying prediction logic, and use of React for routing and components.
- **Service** - Call to a third party for a scripture. Backend service with endpoints for:
    - login
    - retrieving recipes
    - submitting recipes
    - submitting on hand ingredients
    - submitting planned meals
- **DB/Login** - Store users, recipes, on hand ingredients, planned meals. Register and login users. Credentials securely stored in database. Can't plan meals or submit recipes unless authenticated.
- **WebSocket** - As each user submits recipes, the recipes are given to all other users.

## 🚀 AWS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **Server deployed and accessible with custom domain name** - [My server link](https://daily-bread.click).

## 🚀 HTML deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **HTML pages** - Ten HTML pages that represent the abilities to login, plan/view meals, and add/view recipes, add/modify/view ingredients.
- [x] **Proper HTML element usage** - I properly used elements like BODY, NAV, MAIN, HEADER, and FOOTER in each of my HTML files.
- [x] **Links** - The heading on each page includes links to all of the pages. The Meal Plan page links to the Modify Plan page. The Pantry page links to the Modify Pantry page. The Browse Recipes page links to the View Recipe page.
- [x] **Text** - There is text displaying the recipe ingredients and instructions
- [x] **3rd party API placeholder** - On the Notifications page there is a placeholder for a scripture from a 3rd party API.
- [x] **Images** - I included an image of bread in the header on each page.
- [x] **Login placeholder** - There are input boxes and a submit button for login.
- [x] **DB data placeholder** - The recipe choices on the Modify Plan page represent data pulled from the database. The submitted recipes, ingredients, and planned meals represent data put in a database.
- [x] **WebSocket placeholder** - The Notifications page will show realtime data about recipes submitted.

## 🚀 CSS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Header, footer, and main content body** - I did not complete this part of the deliverable.
- [ ] **Navigation elements** - I did not complete this part of the deliverable.
- [ ] **Responsive to window resizing** - I did not complete this part of the deliverable.
- [ ] **Application elements** - I did not complete this part of the deliverable.
- [ ] **Application text content** - I did not complete this part of the deliverable.
- [ ] **Application images** - I did not complete this part of the deliverable.

## 🚀 React part 1: Routing deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Bundled using Vite** - I did not complete this part of the deliverable.
- [ ] **Components** - I did not complete this part of the deliverable.
- [ ] **Router** - I did not complete this part of the deliverable.

## 🚀 React part 2: Reactivity deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **All functionality implemented or mocked out** - I did not complete this part of the deliverable.
- [ ] **Hooks** - I did not complete this part of the deliverable.

## 🚀 Service deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Node.js/Express HTTP service** - I did not complete this part of the deliverable.
- [ ] **Static middleware for frontend** - I did not complete this part of the deliverable.
- [ ] **Calls to third party endpoints** - I did not complete this part of the deliverable.
- [ ] **Backend service endpoints** - I did not complete this part of the deliverable.
- [ ] **Frontend calls service endpoints** - I did not complete this part of the deliverable.
- [ ] **Supports registration, login, logout, and restricted endpoint** - I did not complete this part of the deliverable.


## 🚀 DB deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Stores data in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Stores credentials in MongoDB** - I did not complete this part of the deliverable.

## 🚀 WebSocket deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Backend listens for WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Frontend makes WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Data sent over WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **WebSocket data displayed** - I did not complete this part of the deliverable.
- [ ] **Application is fully functional** - I did not complete this part of the deliverable.
