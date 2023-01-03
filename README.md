# Worldscapes

- [Overview](#overview)
- [Wireframes](#wireframes)
- [MVP](#MVP)
  - [Goals](#goals)
    - [Libraries](#libraries)
    - [Component Hierarchy](#component-hierarchy)
    - [Component Breakdown](#component-breakdown)
    - [Component Estimates](#component-estimates)
  - [Post-MVP](#post-mvp)
- [Project Delivery](#project-delivery)
  - [Code Showcase](#code-showcase)
  - [Code Issues & Resolutions](#code-issues--resolutions)



### Overview

  Worldscapes is a photography store application that brings the wonders of travel right into your home! Shop and print images from your favorite destinations to compliment your home or office! 

<br>

### Wireframes 

<details>
<summary>Desktop- Home</summary>
<img src="https://user-images.githubusercontent.com/61858219/208339764-d2f19803-3b45-4313-a84d-a4e2930786fb.png" >
</details>

<details>
<summary>Desktop- CreateUser</summary>
<img src="https://user-images.githubusercontent.com/61858219/208341927-fb0dae85-b975-4326-8753-ad3edc1ef454.png" >
</details>

<details>
<summary>Desktop- LogIn</summary>
<img src="https://user-images.githubusercontent.com/61858219/208343873-90fa294f-c0ac-4312-9e14-afe838c84672.png" >
</details>


<details>
<summary>Desktop- Cart</summary>
<img src="https://user-images.githubusercontent.com/61858219/208344309-a5ae46a0-2f9a-4b0e-b022-046087a7b201.png">
</details>

<details>
<summary>Desktop- User-Logged-In</summary>
<img src="https://user-images.githubusercontent.com/61858219/208344138-1663df02-42af-4023-a32f-305d36a60e2a.png" >
</details>


<details>
<summary>Tablet- Home</summary>
<img src="https://user-images.githubusercontent.com/61858219/209052944-9cf363ba-38a9-4183-a6fa-9315f0f67361.png" >
</details>


<details>
<summary>Tablet- CreateUser</summary>
<img src="https://user-images.githubusercontent.com/61858219/209053017-d325e389-ee9a-4708-81ea-531048f009f9.png" >
</details>

<details>
<summary>Tablet- Login</summary>
<img src="https://user-images.githubusercontent.com/61858219/209053091-75e5ae3f-18da-47dc-b068-7891ba5765d4.png" >
</details>

<details>
<summary>Tablet-Login-Landing</summary>
<img src="https://user-images.githubusercontent.com/61858219/209053263-cd8f053f-5ab8-43f8-92ad-57783ae5b92a.png" >
</details>

<details>
<summary>Tablet- User-Logged-In</summary>
<img src="https://user-images.githubusercontent.com/61858219/209053155-162eb705-4cb0-4375-ad72-383c8f722f3b.png" >
</details>


<details>
<summary>Mobile- Home</summary>
<img src="https://user-images.githubusercontent.com/61858219/209702050-39c7634d-a2b6-4f13-afb7-b3158863c1e7.png" >
</details>

<details>
<summary>Mobile-Login</summary>
<img src="https://user-images.githubusercontent.com/61858219/209702112-2080a7f1-2fbe-41e9-908f-6ee68662995b.png" >
</details>

<details>
<summary>Mobile-CreateUser</summary>
<img src="https://user-images.githubusercontent.com/61858219/209705165-85b70f0d-0725-4e2a-9632-7f7907afb511.png" >
</details>

<details>
<summary>Mobile- User-Login</summary>
<img src="https://user-images.githubusercontent.com/61858219/209705259-e651c1b7-1a1a-496a-9c68-3c8e53b58112.png" >
</details>

<br>

### MVP
- Have Gallery of images
- Cohesive styling throughout application 
- User Login/Logout/CreateUser
- Add, Delete, Update shopping cart
- Use Stripe to complete checkout

<br>

#### Goals 

- Cohesive Design throughout application
- Enable seamless shopping cart usage with Stripe 



<br>


####Libraries 

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|   React Router   |  Using router to direct to different pages.   |
|     Link         |Will be using to link the pages to each other.   |
|    TBD              |     TBD                          |

<br>

#### Component Hierarchy
```
src
|__ assets/
      |__ tests
      |__ fonts
      |__ images
      |__ wireframes
|__ components/
      |__ header.jsx
      |__ nav.jsx
      |__ searchBar.jsx
      |__ images.jsx
      |__ imageLinks.jsx
      |__ Footer.jsx
```

<br>

#### Component Breakdown

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | function |  Y |    Y | _Will have page title._               |
|  Home  |  Button |  Y  |  Y | _Will provide links to separate components/pages_       |
|   Images   |  function    |Y   | Y     | _This will be the results provided by the api._      |
|ImageLinks  | Route/Link |   Y  | Y    | _Link function for individual photographs_                 |
|    Footer    |  |     |     | _Copyright info._ |
<br>

#### Component Estimates

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Create Backend framework    |    H    |     8 hrs      |      hrs     |     hrs    |
| Create Frontend framework |    H     |     8 hrs      |      hrs     |     hrs    |
| Add Auth to backend  |    H     |     6 hrs      |      6hrs     |    6hrs     |
| Connect backend and front end |    H     |     4 hrs      |    6 hrs     |     6hrs    |
| Enable Stripe on frontend|    H     |     8 hrs      |      8hrs     |    8hrs   |
| Test backend functionality |    H     |     3 hrs      |      3hrs     |     3hrs   |
| Test front end functionality |    H     |    5  hrs      |      hrs     |     TBD     |
| Add Styling |    H     |     12 hrs      |      hrs     |    hrs    |
| Finish Styling|    H     |     10 hrs      |      hrs     |     TBD     |
| Testing |    H     |     6 hrs      |       hrs     |     TBD     |
| Deploy |    H     |     6 hrs      |       hrs     |     TBD     |
| TOTAL               |          |     hrs      |     hrs     |     TBD     |

<br>

#### SWOT- Analysis
I will be using a combination of Youtube, google research and Docs to overcome any issues that 
arise. 

<br>

### Post-MVP

- Wishlist with CRUD capabilities 
  
<br>

## Project Delivery


### Code Showcase


### Code Issues & Resolution




