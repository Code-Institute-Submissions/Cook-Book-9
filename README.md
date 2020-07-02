# Data Centric Development Milestone Project

 <p align="center">
   <img  src="static/images/images_for_readme/blend_it.jpg">
 </p>

# **BLEND IT**

"Blend It" is a website with a collection of smoothies recipes. It has a choice of recipes in three different categories, the possibility to add, edit, or delete a recipe, intuitive design, and list of recommended blenders.

## [Click To visit "Blend It" !](https://smoothie-cookbook.herokuapp.com/)

---

# **Table of Contents**

## 1. [UX](#ux)

- **[Project Goals](#project-goals)**
- **[User Goals](#user-goals)**
- **[Site Owner's Goals](#site-owner's-goals)**
- **[Developer Goals](#developer-goals)**
- **[User Stories](#user-stories)**
- **[Website Design](#web-site-design)**
- **[Wireframes](#wireframes)**

## 2. [Features](#features)

- **[Existing Features](#existing-features)**
- **[Features Left To Implement](#features-left-to-implement)**

## 3. [Technologies Used](#technologies-used)

## 4. [Testing](#testing)

## 5. [Deployment](#deployment)

## 6. [Acknowledgments](#acknowledgments)

---

## [UX](#ux)

### [Project Goals](#project-goals)

- To build a full-stack site that allows users to manage a common dataset about a particular domain.
- To build a MongoDB-backed Flask project.
- To build a project with 'CRUD' functionality.
- Deploy the project to Heroku.
- To build a useful, userfriendly, attractive webpage with collection of healthy recipes.

### [User goals](#user-goals)

- Friendly interface
- Intuitive navigation
- Attractive design which will motivate to try recipes
- Comfortable representation of recipes and access to each
- Ability to choice categories of recipes
- Ability to find, share, store edit and delete recipes.

"Blend It" met these goals: <br>
Based on feedback from users.

- "Home" page giving clear information about the website.
- Easy to navigate through the website. The navigation bar represent a list of pages.
- Easy to open and read information about each recipe. Also possible to open a few recipes at the same time and compare list ingredients or methods.
- Recipes split into three most popular categories of smoothies. Very comfortable and easy to switch between categories.
- Functionality of adding, editing, and deleting recipe has easy access and made in a simple and understandable manner.

### [Site Owner's goals](#site-owner's-goals)

- Promote a brand of cooking tools.

"Blend It" met these goals:

- Website share a collection of blenders. Collection include: image, specifications and straight link to the web-shop.

### [Developer Goals](#developer-goals)

- Create a website that allows users to store and easily access cooking recipes.
- Create a representation of each recipe with different fields: recipe image, name of recipe, category, ingredients, instruction, link to the source where the recipe was found.
- Create forms to allow users to add, edit and delete recipes.
- Provide results in a manner that is visually appealing and user friendly.
- Create a search by a category of recipes.

### [Wireframes](#wireframes)

The wireframes were created using [Balsamiq Wireframes](https://balsamiq.com/).

Web site design and mobile display [here](static/images/wireframes_images/)

---

## [Features](#features)

### [Existing Features](#existing-features)

#### **Navigation bar**.

All elements responding on mouse click or finger touch on mobile devices.

- **Blend It**. Website name. Working as a link to the 'Home' page.
  List of website categories:
- **Recipes**. Opening a collection of recipes.
- **Add your recipe**. Opening a form for creating a new recipe.
- **Choose your blender**. Opening a collection of blenders.

#### **Home**.

- Text in paragraph taken from [Philips website](www.philips.co.uk).
  Words : collection, blender, recipe are working as links to the "Blend It" website pages.

#### **Recipes**.

All elements responding on mouse click or finger touch on mobile devices.

- **Categories of recipes**:
  All: displaying a collection of all recipes.<br>
  Fruit: displaying a collection of "Fruit" smoothies.<br>
  Green: displaying a collection of "Green" smoothies.<br>
  Protein: displaying a collection of "Protein" smoothies.

- **Recipe card**:
  All recipe details loading from the MongoDB database.<br>
  Recipe image: represent a smoothie from the current recipe.<br>
  Clickable chevron: opening a 'card-body' with recipe details.<br>

  Name of the recipe.<br>
  Ingredients: list of ingredients for the current recipe.<br>
  Category: one of three existing.<br>
  Instruction.<br>
  Source: link to the website where the recipe was found. (not required)<br>
  'Edit' button opens a form where a user can edit a recipe.<br>
  'Delete' button opens a modal window with a question. If a user gives a positive response, the recipe will be deleted from the website and database.<br>

- **Pagination**:
  Allowed to navigate between pages of the current category of recipes.<br>

#### **Add Your Recipe**.

"Add Recipe" form<br>
Allows user to create own recipe.<br>
Fields which required: <br>
recipe name, category, ingredients, preparation, image link. <br>
Fields which are not required:<br>
sourse link.<br>
Buttons 'Submit' and 'Cancel'<br>

#### **Edit Recipe**.

Displaying when user click on 'Edit recipe' button in the recipe card.<br>
Allows editing the existing recipes.
All fields are filled with existing information
Buttons 'Save' and 'Cancel'.

#### **Choose Your Blender**.

Displaying a collection of blenders.<br>
Each card has an image, blender details and link to the web-shop.

<p align="center">
   <img width="500" height="" src="static/images/images_for_readme/">
 </p>
  
  #### Mobile devices display

  <p align="center">
  <img width="150"  m-5 height="" src="static/images/images_for_readme/">
   <img width="150" pl-2 height="" src="static/images/images_for_readme/">
   <img width="150" p-2 height="" src="static/images/images_for_readme/">
   <img width="150" p-2 height="" src="static/images/images_for_readme/">
 </p>
   
#### Tablet display

  <p align="center">
  <img width="200" height="" src="static/images/images_for_readme/">
  </p>

### [Features Left to Implement](#features-left-to-implement)

- Add an authorization. Create a registration form.
  Make permition only for registered users add, edit or delete recipes.
  (Was not in requirements from CI for current project )

- Create a search by ingredients.
  If collection or recipes will grow the search can help users to find what they need faster.

- Add extra list element in Recipe card called "Recommended blender" Create a feature which will add a link to a recommended for this recipe blender, from an existing database

---

## [Technologies Used](#technologies-used)

This project used HTML, CSS, Python, JS as coding languages.

- **[Flask](https://flask.palletsprojects.com/en/1.1.x/)**
  The project uses Flask as web framework
- **[MongoDB](https://mongodb.com/)** <br/>
  The project uses MongoDB as database for recipes collection.
- **[Balsamiq](https://balsamiq.com/)** <br/>
  The project uses Balsamiqo to build wireframes in the planning stage of development.
- **[GitPod](https://www.gitpod.io/)** <br/>
  The project uses GitPod to build the website.
- **[JQuery](https://jquery.com/)**<br/>
  The project uses JQuery as JS library to make HTML document traversal and manipulative
- **[Bootstrap](https://getbootstrap.com/)**<br/>
  The project uses the Bootstrap framework to help create some elements
- **[FontAwesome](https://fontawesome.com/)**<br/>
  The project uses FonAwesome to use an icons from the library.
- **[Google Fonts](https://fonts.google.com/)**<br/>
  The project uses Google fonts to style the website fonts.
- **[GitHub](https://github.com/)**<br/>
  To store and share all project code remotely.
- **[Google Chrome - Dev Tools]()**<br/>
  The project used Google Chrome Dev Tools to debug code. Check responsiveness.
- **[Favicon generator](https://favicon.io/)**<br/>
  The project uses Favicon generator to create a puzzle favicon
- **[Google](https://www.google.com)**<br/>
  Recipes for the project were found by using Google search.
- **[Color Hex Color Codes](https://www.color-hex.com/)**<br/>
  To chooise colors and take a code for the project

---

## [Testing](#testing)

# Automated Testing

### Validation services

Services used to check the validity of the code:

[W3C Markup Validation used to validate HTML.](https://validator.w3.org/)<br>

[W3C CSS validation used to validate CSS.](https://jigsaw.w3.org/css-validator/)<br>

---

# Manual testing

Information about all manual testing that has been done
to make sure all areas of the website are working as expected.

Browsers: **Google; Opera; Firefox ; Microsoft Edge.**

Browser width

xs = Extra small <576px

sm = Small ≥576px

md = Medium ≥768px

lg = Large ≥992px

xl = Extra large ≥1200px

|         | XS  | SM  | MD  | LG  | XL  |
| ------- | --- | --- | --- | --- | --- |
| Google  | Ok  | Ok  | Ok  | Ok  | Ok  |
| Firefox | Ok  | Ok  | Ok  | Ok  | Ok  |
| Opera   | Ok  | Ok  | Ok  | Ok  | Ok  |
| ME      | Ok  | Ok  | Ok  | Ok  | Ok  |

In each browser in each size were tested :

Web page :

- Open/Close .
- Switch between navigation bar links.
- Refresh.
- Resize with browser window.
- Responsiveness with dev tools

Design :

- Colors.
- Text
- Fonts
- Images

Layout :

- Bootstrap Grid Layout.

Website functionality:

- Loading of Images
- Loading of Links from database
- Loading of text from the database
- Open a close recipe card.
- The functionality of forms:
  create recipe
  edit recipe
- Delete recipe
- All buttons are working
- A modal window is working

------------------------------------------------------------------------

# Problems discovered

1.  **Problems with closing the very first recipe card as soon as other opens:**

    - **Problem:** <br>
      The accordion element in the first recipe closing as soon as the user opens any other recipe.
      It not happening in other cases.
      All other recipes stay open.
      To keep very first open, users have to open it again as soon as other recipes open.

    - **Solution:** <br>

2)  **Categories of recipes flashing white :**

    **Problem** <br>
    Categories of recipes flashing white, if to fast keep switching between them very fast.

    - **Solution:** <br>

    No special solution found. It happens only if switch to fast. What users did by checking the functionality of the website.

# Real-Time Testing.

Asked my friends and family to check the website on their devices.
Go through the collection of recipes, open/close recipe cards. Despite many times. Press all buttons.
Move through the navigation bar menu back and forward. Resize screen. Use forms to add/edit the recipe. Delete recipe.
**Feed back**.

The website was checked on different mobile devices and desktops.
Everything working apart from problems which were in the description above.


---

## [Deployment](#deployment)

## [Acknowledgments](#acknowledgments)

- Text within this project was written by the developer.

- Project idea and design were created by the developer

- The HTML and CSS code was written by the developer
  Code taken from Bootstrap or other sorses - marked by comments

**Special thanks to:**

Code Institute Mentor Spencer Barriball for his help and support.
Code Institute Tutor support
Code Institute Slack Community for the shared experience.

## [Disclaimer](#disclamer)

The "Blend It" project is created for educational purposes only.
