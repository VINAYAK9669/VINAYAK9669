 <img src="https://i.imgur.com/xgLMhkG.png" alt="Masterimage">
<h1 align="center">Hi 👋, I'm Vinayak Kittad</h1>
<h3 align="center">A passionate React.js frontend developer</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=vinayak9669&label=Profile%20views&color=0e75b6&style=flat" alt="vinayak9669" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=vinayak9669" alt="vinayak9669" /></a> </p>

- 🌱 I’m currently learning **Backend [Node.js,Express, MangoDB, SQL]**

- 👨‍💻 All of my projects are available at [https://portfolio-vinayak-kittad.netlify.app/](https://portfolio-vinayak-kittad.netlify.app/)

- 💬 Ask me about **React.js, JavaScript-(ES6),Redux-toolkit,TailwindCSS,HTML,CSS**

- 📫 How to reach me **Email: vinay.reactdeveloper@gmail.com**

- 📱 Call/Whatsapp On **+91 7822020891**

---

<p align="center">
<img align="center" src="https://github-readme-stats.vercel.app/api?username=vinayak9669&show_icons=true&locale=en" alt="vinayak9669" />
 </p>
<br/>

<p align="center"><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=vinayak9669&" alt="vinayak9669" /></p>

---

<h1 align="center">React Projects</h1>
---

> ### Professional-Level Projects

 ***Why Professional-Level?***
- Well! These projects adhere to industry best practices not only in website development but also in terms of code readability, component structures, and performance optimization.
- In these applications, I've utilized cutting-edge technologies such as Redux Toolkit and Tailwind CSS, which elevate these projects to a professional level.
<br/> <br/>

> #### 1] React Pizza Order App [Responsive]

 ***Description***<br/>
 Welcome to the React Pizza Order App, a professional-level web application that takes you through the entire process from user registration to order confirmation. This app is built using the latest technologies and follows best practices in React development. <br/>

 ***Flow & Implementations*** <br/>
 - **`Home Page`** :
    - Collects `Username` , until user enter their name don't show the `Start Ordering Button`.
  
 - **`Menu Page`** :
     - Show the list in UI from API
     - Each product have a functionality of `Add to Cart` `Delete`, `Increase Qty`, `Decrease Qty`
     - At the Bottom show the `Quantity of Item`, `Total Price` and `Open Cart Option`
   
 - **`Cart Page`** :
    - It have `Back to Menu` button to go to the `Menu page`
    - Display added items in the cart with `quanitity`, also option to `Delete` ,`Increase Qty`, `Decrease Qty`
    - Finally it have two buttons `Order pizzas` and `Clear Cart`.
    - Once user clicks on the `Order pizzas` it will take user to the `Form Page / Order Form`
    
 -  **`Order Form`** :
     -  This form automaticaly takes First Name from the `Home Page`, it have another fields called 'Phone Number' and `Adress`.
     -  For Phone Number validation used `RegExp` and for Adress there is an option to `Get Position` by which we can fetch our location automatically.
     -  Also this form have an extra option to make the `order Priority`. For this extra charges are needed.
   
 -  **`Order Confirmation`** :
    -  It shows the datails of the order like `priority Status`, `Preparing order`, `Minutes left to Delivery`, `Order Name with price`, `Total Bill`  

 ***Tech Stack used*** <br/>
 *React.js | React Router | Redux-tookit | Redux-thunk | Tailwind CSS* <br/>

 ***Links***<br/>
 - [Netlify Hosted Link](https://react-pizza-ordering-app-by-advinay.netlify.app/)
 - [Github Repository](https://github.com/VINAYAK9669/Pizza_ordering_app)

***ScreenShot***<br/>
<kbd>
<img src="https://portfolio-vinayak-kittad.netlify.app/assets/img/Pizza_order_app.JPG" alt="drawing" width="350"/> 
</kbd>

---

> #### 2] 🌍 WorldWise Map Application - Desktop App 🗺️

 ***Description***<br/>
This React Vite Single Page Application enables users to efficiently interact with a map, allowing them to select locations for updating personal notes. Users can seamlessly add or delete cities, leveraging a mock API for local machine operations, as backend functionality is not available on the hosted website. <br/>

 ***Flow & Implementations*** <br/>
 - **`Home Page`** : It have `Landing Page`, Navigation bar for `Pricing`, `Product` and `Login`
   
 - **`Login Page`** : This will `secure the AppLayout page [Secured Route]`, only after succefull sign in user can able to use map application.
   
 - **`App Layout Page`** :
   - It have  `interactive Map `at right side and at the left side there is dyanamic side bar
   - It contains 'form' to add slected city information, 'city' and 'countries' tabs inside the sidebar which shows the list of cities added to the mock api and countries respectively.
   - Also whenever we click on the `map` it will send that location information to the URL and open the form to add note for cities. Later using `useParams` we will get the `lng` and `lat` from URL

 ***Tech Stack used*** <br/>
 *React.js | React Router | CSS modules | API* <br/>
 
***Implemented*** <br/>
*context-API | leaflet Library [For map] | Local server to GET, POST, PUT, DELETE*


 
 ***Links***<br/>
 - [Netlify Hosted Link](https://worldwise-desktop-map-app.netlify.app/)
 - [Github Repository](https://github.com/VINAYAK9669/WorldWiseWebAPP1/blob/main/README.md)

***Screen Shot***<br/>
<kbd>
<img src="https://portfolio-vinayak-kittad.netlify.app/assets/img/worldwise_poster.PNG" alt="drawing" width="350"/>
</kbd>

---



> #### 3] 🚀 React Quiz App

 ***Description***<br/>
The "React Quiz App" is a dynamic and engaging web application built with React.js. This project offers a variety of features, including a complete responsive design for seamless use on different devices, a clean and intuitive user interface, and a timed quiz with a progress bar to track your progress.

As you answer questions, the app instantly updates your score and provides a comprehensive scorecard once the quiz is completed. The quiz also includes an automatic submission feature when the timer runs out. <br/>

 ***Flow & Implementations*** <br/>
 - **`Home Page`** : This is basically a landing page shows the user `Number of questions` and `Button` to proceed.
   
 - **`Quiz Page`** :
    - It have `Progress Bar`, `Question Tracking`, `Marks Tracking`.
    - It is MCQ type questions , once user clicks on any option it will show the correct answer, if the answer is correct then it updates the marks else not, then shows the `Next Button` icon.
   
 - **`Result Page`** : It shows the `Total Marks`, 'Percentage' obtained and the `Dynamic Emojis` as per the result.

 ***Tech Stack used*** <br/>
 *React.js | CSS | API* <br/>
 
***Implemented*** <br/>
*State Mangement using `useReducer()`, Questions are fecthed from an API, timer using `setTimeout()`, Dyanamic `Progress Bar`*
 <br/>
 ***Links***<br/>
 - [Netlify Hosted Link](https://vinayak9669.github.io/React-QuizApp/)
 - [Github Repository](https://github.com/VINAYAK9669/React-QuizApp)

***Screen Shot***<br/>
<kbd>
<img src="https://portfolio-vinayak-kittad.netlify.app/assets/img/React_quiz_app_poster.PNG" alt="drawing" width="350"/>
</kbd>

---



> #### 4] 🚀 Booking Application with Calendar

 ***Description***<br/>
This project involves the creation of a Booking App with an interactive calendar to showcase venue availability. The app is built using React.js, Vite, Tailwind and Redux. It features a user-friendly calendar display, booking functionality for half-day slots, and a simple booking form with essential details. The booking procedure is streamlined with a popup window for confirming reservations.
<br/>

 ***Flow & Implementations*** <br/>
 - **`One Intial Render`** :
    - On the Home page shown `Calendar`, and at the right side it's dyanamic sidebar which shows `instruction`, `form`, `Book Slot Button` and `Date Selected`.
    - Initially the `Book a Slot` button is disbaled until date selcted from the calendar.
   
 - **`Once Date Selected from the Calandar`** :
    - Once the date is selected from the calander then `Book a Slot` button will now active.
    - Clicking on this will open the `form` which needs the field like `Name`, `Phone Number`, `Email`, `Purpose of Booking` and `Sots` to selects.
    - Here user have option to select `Morning Slot` or `Noon Slot`.
    - If both get booked then we have to lock the date for further booking on the same date and to show the `red mark` on it.
    - If the only one slot is selected then on that date we have to show  `yellow mark`
   
 - **`Once Booking is confirmed`** :
   - If the user is booked the slot then confirm the details once again with popUp.
   -  If the user confirm the details then show the `Yellow` or `red` mark on the dates as discussed above.

 ***Tech Stack used*** <br/>
 *React.js | Vite | Redux ToolKit | TailwindCSS | VS code* <br/>
 
***Implemented*** <br/>
*`Calendar from Scratch` Calendar is completely built from scratch, we can navigate through the months and years. We can select dates it means its completely a interactive calender.*
 <br/>
 ***Links***<br/>
 - [Netlify Hosted Link](https://booking-application-with-calendar.netlify.app/)
 - [Github Repository](https://github.com/VINAYAK9669/BookingApp-with-Calendar-from-Scratch?tab=readme-ov-file)

***Screen Shot***<br/>
<kbd>
<img src="https://github.com/VINAYAK9669/BookingApp-with-Calendar-from-Scratch/raw/main/public/screenshots/step-11.JPG" alt="drawing" width="350"/>
<img src="https://github.com/VINAYAK9669/BookingApp-with-Calendar-from-Scratch/raw/main/public/screenshots/step-14.JPG" alt="drawing" width="350"/>
</kbd>

---


> ### Advance-Level Projects [React.js Based]
<br/>

> #### 1] 🍿 Project - PopCorn [Movie Rating Web App] - Desktop App

 ***Description***<br/>
Experience the Movie Rating App – a seamless blend of user interaction and data representation. With a dynamic search bar, API integration, and a star rating component, users can effortlessly rate and manage their watched list. Dive into a personalized movie experience, discovering the power of React.js components, API handling, and UI enhancement.
<br/>

 ***Flow & Implementations*** <br/>
 - **`Landing Page`** :
    - It have `Navigation Bar` which holds `Logo`, `Input search bar`, `Count of Results`.
    - By `Input Search` we can search the required movie , and this data fecthes from an `API`.
    - The number of results fecthed from the API will show in the nav bar inside the `result found`.
   
 - **`Once the Movie name is searched`** :
    - Below the navigation bar there are two divisions of the screen left side we show the `List of the results` and  at the right side `Movie Details`.
   
 - **`Upon Clicking the any movie`** :
    - Once the user clicks on the movie, `Movie Deatils` will show at the right side and ask to `Rate the Movie`.
    - Once the user Rate the Movie then `Add to List` button will appear.
    -  Clicking on this will result into the saving the movie details to the `Local Storage` so that we need to prevent the user to rate this movie again.
    -  Also to show them the list of `Watched Movie List` and this information come from `Local Storage`
   
 - **`Upon Clicking Add to List`** :
    - Once the user click on `Add to List` Button the right side bar now will show you the list of the added movies in to the wastched list.
    - Now user can have the `Delete` option to delete the movie from `wacthed list`.

 ***Tech Stack used*** <br/>
 *React.js | CSS | API | VS code* <br/>
 
***Implemented*** <br/>

*`customComponents`, `starComponent`, `ErrorHandling`, `Loaders`  to show the loading, `Local Stroage`*
 <br/>
 ***Links***<br/>
 - [Netlify Hosted Link](https://vinayak9669.github.io/React_popcorn/)
 - [Github Repository](https://github.com/VINAYAK9669/React_popcorn?tab=readme-ov-file)

***Screen Shot***<br/>
<kbd>
<img src="https://portfolio-vinayak-kittad.netlify.app/assets/img/MovieRating_app_poster.PNG" alt="drawing" width="350"/>
</kbd>

---


> #### 2] IP Address Tracker 🌍

 ***Description***<br/>
This project is a solution to the IP address tracker challenge on Frontend Mentor. The goal of the challenge is to create a responsive web application that allows users to view their own IP address on a map and search for information about other IP addresses or domains.
<br/>

 ***Flow & Implementations*** <br/>
 - **`Landing Page`** :
    - On intial render this website access the user `IP ADDRESS` and this data we will given to the `ipify` api which deternmines the `Latitude` and `Longitude` of that IP address.
    - Once we get the `Latitude` and `Longitude` we will pass these data to the `Leaflet` map then it will show the location in the map.
 - **`Input search bar`** :
    - Once user add the valid `Ip Address` then the same process need to happen as discussed above.

 ***Tech Stack used*** <br/>
 *React.js | Tailwind | API | Leaflet Library | Ipify Geolocation API* <br/>
 
***Implemented*** <br/>

*`Map to show location based on IP Address`,`Error Handling`, `Loaders` to show page loading in UI,  `secured the API key` The solution involved referencing documentation to securely store the API key using a .env file*
 <br/>
 ***Links***<br/>
 - [Netlify Hosted Link](https://vinayak9669.github.io/IP-ADDRESS-TRACKER/)
 - [Github Repository](https://github.com/VINAYAK9669/IP-ADDRESS-TRACKER?tab=readme-ov-file)

***Screen Shot***<br/>
<kbd>
<img src="https://portfolio-vinayak-kittad.netlify.app/assets/img/IO_ADDRESS_TRACKER.JPG" alt="drawing" width="350"/>
</kbd>

---
> #### 3] MultiStep Form

 ***Description***<br/>
This project is a solution to the Frontend Mentor challenge, where I created a responsive multistep form. In this we have 4 steps to complete the form. To navigate between the steps I have used `React-Router` and for the form data, for all different pages are handles using `Redux-toolkit`
<br/>

 ***Flow & Implementations*** <br/>
 - **`Personal Information Page`** :
    - This will take the `Name`, `Email`, `Phone Number`.
    - At the bottom of the form need to show `Next Button`. It will allow user to next page when the fields are `Valid`
    - Also made sure that user cannot navigate to the steps until this form completion.
      
 - **`Select Plan`**
    - Here user need to select the plans. Here, there are 3 plans to select.
    - Also there is slider to select the monthly or yearly plan
    - At the bottom added `Go to Back` and `Next Button` 
    
- **`Picks Add-ons Page`**
   - Provides a user three option like `Online Service`, `Larger Storage`, `Customizable Profile`
   - Once user select any options need to send the data to the Global state.
   - At the bottom added `Go to Back` and `Next Button` 
    
- **`Finishing Up`**
   - This provides the summary of the order details.
   - It have the details of `Choosen Plan`, `Choosen Add-ons`, `Total Bill`
   - At the bottom added `Go to Back` and `Next Button`
   - Once the user clicks on the `Next Button` then `Thank You` interface will appear.

 ***Tech Stack used*** <br/>
 *React.js | Vite| Tailwind | React-Router | Redux Toolkit* <br/>
 
***Implemented*** <br/>
* For Global State Management utilized the `Redux-toolkit`, To navigate between steps implemented `React-Router`*
 <br/>
 
 ***Links***<br/>
 
 - [Netlify Hosted Link](https://multi-step-form-frontend-advance.netlify.app/)
 - [Github Repository](https://github.com/VINAYAK9669/MultiStepForm-Frontend-Mentor-Advance-Level/tree/main?tab=readme-ov-file)

***Screen Shot***<br/>

<kbd>
<img src="https://github.com/VINAYAK9669/MultiStepForm-Frontend-Mentor-Advance-Level/blob/main/public/assets/screenshots/multistep_form.JPG?raw=true" alt="drawing" width="350"/>
</kbd>

---

> #### 3] EduPath - Course Listing App

 ***Description***<br/>
EduPath is a web application designed to help students discover and enroll in courses. It features a Course Listing page with filters, a detailed Course Details screen, and a Student Dashboard to track enrolled courses.
<br/>

 ***Flow & Implementations*** <br/>
 - **`Course Listing Page`** :
    - Displays a scrollable list of courses with basic information.
    - Allows searching based on course name and instructor.
    - Clicking on a course redirects to its detailed information.
      
 - **`Course Details Screen`**
    - Displays comprehensive information about a selected course.
    - Information includes course name, instructor, description, enrollment status, duration, schedule, location, prerequisites, and syllabus.
    
- **`Student Dashboard`**
   - Provides a user-friendly interface to display enrolled courses.
   - Shows course name, instructor name, thumbnail, due date, and progress bar.
   - Allows marking courses as completed.
    
- **`Advanced State Management`**
   - Utilizes Redux for effective state management.

 ***Tech Stack used*** <br/>
 *React.js | Vite| Tailwind | API | Router* <br/>
 
***Implemented*** <br/>
*`Navigation through pages` using Router, `Accordian Tabs` to show the syllabus, `Reusable Component`, `Advance State Mangement `using Redux , `Search the courses` by `course name, instructor, description of the given course`*
 <br/>
 ***Links***<br/>
 - [Netlify Hosted Link](https://edupath-course-app.netlify.app/)
 - [Github Repository](https://github.com/VINAYAK9669/IP-ADDRESS-TRACKER?tab=readme-ov-file)

***Screen Shot***<br/>
<kbd>
<img src="https://github.com/VINAYAK9669/Alemeno_task--Online_Course/raw/main/public/screenshots/course_list.JPG" alt="drawing" width="300"/>
<img src="https://github.com/VINAYAK9669/Alemeno_task--Online_Course/raw/main/public/screenshots/course_details.JPG" alt="drawing" width="300"/>
<img src="https://github.com/VINAYAK9669/Alemeno_task--Online_Course/raw/main/public/screenshots/course_dashboard.JPG" alt="drawing" width="300"/>
</kbd>


