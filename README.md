# My Portfolio FullStack Project 


# Project created as part of the honors programme at the hong kong universty of science and technology.

    The notes below is the project requirements for the final project as part of the "Fullstack Certification"

    The project will combine all three courses:

            Front-End Web Development with React 
            Server-side Development with NodeJS, Express and MongoDB
            Multiplatform Mobile App Development with React Native                                                                                                                   

 ## Repo links: 

         The Repo's have commits that reflects the parts in this document you should be able to find your way around.

         https://github.com/xAirx/Coursera-UniversityofHK-ReactNative

         https://github.com/xAirx/Coursera-UniversityofHK-React

         https://github.com/xAirx/Coursera-UniversyofHK-ServerSideNode
         
         
 ## The "Future Section" -> Node School // Styled components and GraphQL
  
  In the bottom you will find a FUTURE section with extra development including styled components, graphql and more!
    
   
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   
# Architecture (subject to change): 

   
   Expected List of Features & Architecture
## Stacklist: 
    
  ### Website made in React.js
  
  #### Goals: 

      Express the general characteristics of JavaScript frameworks and libraries
      Create a new project using React
      Create React components within a React application
      Express what is meant by full-stack web development

      Develop a React router based navigation to various views in a React application
      Develop a single page application using the React router support
      Give examples of various types of React components

      Create uncontrolled React forms
      Create controlled forms and perform form validation
      Discuss the features of the Flux architecture
      Explain the Redux approach to implementing a variant of the Flow architecture

      Create Redux Actions
      Develop Redux actions using Redux Thunk
      Develop client-server communication using Fetch
      Develop Fetch-based communication with a REST API server

  
    __________________________________

    
   #### Features:
    
    Website made to support any type of business.
    
         Integrated font awesome "fonts and buttons"
        
         Form handling &  Redux integration for form handling 
         
         *********** Redux integration to create a "Loading Component" using the activity indicator component
         Trigger showing of message when data is fetched from server.

         ***********Redux integration to "Star products" and rate them

         ***********Redux integration to handle the customers favorite products
         
         Redux Thunk middleware 
         
         React Animations for animations
         
         Redux For Client server communication with fetch.
         
         Feedback through the feedback form by creating a new feedback service that accepts the form data and uses Restangular to record their feedback on the server.
    
  
  &nbsp;&nbsp;&nbsp;&nbsp;
  
   ## App made in React Native 
    __________________________________

     A React Native app, supporting the same features working with the same backend and API.
     
     The Native app is a mini version of the above React Frontend.
     
     The Native app will also be using the API and Backend created.
     
     The app also includes table reservation, with integration with the users calendar.
     
     
   ### Goals: 
     
     Summarize the salient features of hybrid mobile application development frameworks
     Create a React Native application
     Develop a React Native application using various React Native components and Layouts
     Build navigation within your application using React Native Navigation support
     
     Design the UI for the app using various React Native UI elements
     Express the Redux approach to implementing a variant of the Flow architecture in React Native
     Design forms within the application for data entry
     Employ alerts and Modals to present information to the user
     
     Build storage support within the application for persisting Redux state
     Employ animations to provide enhanced user experience
     Employ gesture-based interaction within the app
     Develop a way of alerting users
     
     Develop applications to use the native capabilities of the devices
     Employ the Expo SDK to access native device capabilities
     Develop applications that use sharing features of mobile devices
     Develop applications that can do user notifications
     
     
    
   #### Features:   
   
         React native Navigation & Components.
     
         Integrated font awesome "fonts and buttons"
        
         Form handling &  Redux integration for form handling 
         
         Redux integration to create a "Loading Component" using the activity indicator component
         Trigger showing of message when data is fetched from server.

         Redux integration to "Star products" and rate them

         Redux integration to handle the customers favorite products
         
         Secure storage - handling user login etc.
         
         Local notifications - Notification handling for reserving tables and based on calendar dates and integration with phone calendar.
         
        Social Sharing - Sharing of information to social media sites using the React Native Share API
        
        Email Integration for contact page.
        
        Interaction with users camera to obtain images for the user profile 
        
        NetInfo() and Network info, to check if device is offline or not.
          connectiontype, effectiveconnectiontype
          connectchange even fires when netwwork status changes etc.
          
          
  
  &nbsp;&nbsp;&nbsp;&nbsp;
    
    
  ## Backend and API + Authentication.
  
   ### Goals:
   
   
    Mongoose
    MongoDB
    Express ( REST API )
    Bodyparser
    Morgan
    Express Router
    
    
    Describe the use of Node for server-side development
    Create a Node application
    Demonstrate the use of Node modules in developing a Node application
    Develop a simple REST API server using the Express framework
    
    Demonstrate an understanding of data persistence using a database
    Design persistent data storage based on MongoDB, a NoSQL database
    Develop schemas and models for data storage using Mongoose
    Combine the REST API and the data persistance layer for a full-fledged server implementation
    
    Demonstrate the need for user authentication
    Evaluate varioius alternative approaches for supporting user authentication
    Develop a comprehensive user authentication system using Passport
    
    Develop a secure server based on the HTTPS protocol
    Design the Express server to handle CORS
    Develop user authentication based on OAuth protocol
    Demonstrate the various Backend as a Service approaches
    
   #### Features
     
     REST API with express mongodband Mongoose
     
     User login and authentication
     
     Basic Authentication
     
     Cookies, Express, Sessions and error handling.
     
     Mongoose Population
     
     HTTPS and Secure Communication
     
     Cross - Origin - Resource sharing
     
     Oauth and user authentication in conjunction
     
     Backend as a service.
     
     
     Extra: 
     
     Authentication based on being an admin or not.
     
     Admin based management, being able to see a user list, and the entire API.
     
     Comment and form support for the users to interact with the content.
     
     Support for a user to manage their own comments, delete functionality.
     
     API supporting various objects of which contains members of the “company” 
     
     
 
 &nbsp;&nbsp;&nbsp;&nbsp;
     
     
     
    
 # Development Notes  
     


 ## React website (Frotend)
 
 
#### Notes: 

https://onedrive.live.com/view.aspx?resid=897203C158E872F%2184124&id=documents&wd=target%28MERN%20stack%29
onenote:https://d.docs.live.net/0897203c158e872f/Documents/marcos%20notesbog/MERN%20stack/
                
  
     Frontend built in React.js, supporting react router based on Redux.
     Introduced new action types and action creators to support the fetching of the information from the server and update the Redux store.
   
   
  #### Part 1 & 2 :
      
      Setting up the project &. Creating components needed - done
      
      Created a new DishdetailComponent and added it to React application. - done

      Updated the view of the DishdetailComponent to display the details of the selected dish using an reactstrap card component. - done

      Updated the view of the DishdetailComponent to display the list of comments about the dish using the Bootstrap unstyled list component. - done

      Integrated the AboutComponent given above into the single page application. - done

      Added a new functional component named <RenderLeader> through the RenderLeader() function to AboutComponent.js that    renders the details of a given leader using the reactstrap <Media> component. - done
      
    Construct and render the list of leaders in the About Us page using the <RenderLeader> component implemented above. - done
      

#### Part 3:
       
      Configure The React application to make use of Redux   - done
       
      Provide a form to enable users to submit their comments   - done
      
      Validate the information entered by the users in the form   - done

      Set up the form as a local form using the react-redux-form    - done
      
      
 #### Part 4 : 
 
       Introduced new action types and action creators to support the fetching of the leaders information from the server and update the Redux store.

        Updated the Home and the About component to render the information about the leaders using the downloaded data from the server

        Add simple animations to the About component where the leaders information is displayed.

        Enabled the users to submit feedback through the feedback form by creating a new feedback service that accepts the form data and uses Restangular to record their feedback on the server.

 
     Appropriate action types and action creators have been added.
    The Home component is correctly using the leader data, and handling any errors that might arise.
    The About component is correctly using the leader data, and handling any errors that might arise.


    A new postFeedback() action creator is correctly implemented to post the feedback data to the server.
    The Contact component has been correctly updated to use postFeedback() to post the form data to the server.


    Appropriate animation has been added to stagger the rendering of the leaders in the AboutComponent.

 
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## Backend: 

#### Notes: 

https://onedrive.live.com/view.aspx?resid=897203C158E872F%2184124&id=documents&wd=target%28MERN%20stack%2FSQL%2FExpress%20Router%29


   #### Express and Routing

   #####  Part 1 :

    * Created a Node module using Express router to support the routes for the products REST API. - done
    * Created a Node module using Express router to support the routes for the promotions REST API. -done 
    * Created a Node module using Express router to support the routes for the leaders REST API. -done 

    Objective 1 

    * The REST API supports GET, PUT, POST and DELETE operations on /products/:dishId end point. -done 

    Objective 2 

    * The new Node module, promoRouter is implemented and used to support the /promotions end point. -done 
    * The REST API supports GET, PUT, POST and DELETE operations on /promotions and GET, PUT, POST and DELETE operations on /promotions/:promoId end points. -done 


    Objective 3 

    * The new Node module, leaderRouter is implemented and used to support the /leaders end point. -done 
    * The REST API supports GET, PUT, POST and DELETE operations on /leadership and GET, PUT, POST and DELETE operations on /leaders/:leaderId end points. -done



   ###### Part 2 : 

    Architecture and REST API and endpoints.

    Objectives:

    * Designing the overall architecture of application, from the front-end to the back-end.  apportioned the responsibilities to the front-end and back-end.

    * Design an appropriate REST API that should be supported by server-side. A good design would enable ease of implementation of both the front-end and the back-end and facilitate seamless communication.

    * Decide on the database schemas and the structure of the data, depending upon the database technology to implement the persistence of server-side data

    * Design the business logic to be implemented on the server-side to support the needs of the front-end.


    * Implemented the Promotions schema and model

    * Implement a REST API to support the /promotions endpoint, and the /promotions/:promoId endpoint enabling the interaction with the MongoDB database

    * Implemented the Leaders schema and model

    * Implement a REST API to support the /leaders endpoint, and the /leaders/:leaderId endpoint enabling the interaction with the MongoDB database


    Task 1
    * The Promotions schema and model correctly supports all the fields as per the example document given above
    * The label field is set to an empty string by default
    * The price schema is be supported with a new SchemaType called Currency.
    * The REST API endpoints /promotions and /promotions/:promoId are implemented to interact with the MongoDB database

    Task 2
    * The Leaders schema and model correctly supports all the fields as per the example document given above.
    * The REST API endpoints /leaders and /leaders/:leaderId are implemented to interact with the MongoDB database




   ###### Part 3 :

    User Authentication

    * Check if a verified ordinary user also has Admin privileges.
    * Allow any one to perform GET operations
    * Allow only an Admin to perform POST, PUT and DELETE operations
    * Allow an Admin to be able to GET all the registered users' information from the database
    * Allow a registered user to submit comments (already completed), update a submitted comment and delete a submitted comment. The user should be restricted to perform such operations only on his/her own comments. No user or even the Admin can edit or delete the comments submitted by other users.


     update all the routes in the REST API to ensure that only the Admins can perform POST, PUT and DELETE operations. Update the code for all the    routers to support this. These operations should be supported for the following end points:


    * POST, PUT and DELETE operations on /products and /products/:dishId
    * DELETE operation on /products/:dishId/comments
    * POST, PUT and DELETE operations on /promotions and /promotions/:promoId
    * POST, PUT and DELETE operations on /leaders and /leaders/:leaderId




   ##### Part 4 : 

    Backend as a service


    * Allowed users to select a dish as their favorite, and add it to the list of favorites that are saved on the server.
    * Allowed users to retrieve the list of their favorite products from the server
    * Delete one or all of their favorite products from their favorites list on the server.


    * When the user does a GET operation on '/favorites',   populate the user information and the products information before returning the favorites to the user.
    * When the user does a POST operation on '/favorites' by including [{"_id":"dish ObjectId"}, . . ., {"_id":"dish ObjectId"}] in the body of the message,   (a) create a favorite document if such a document corresponding to this user does not already exist in the system, (b) add the products specified in the body of the message to the list of favorite products for the user, if the products do not already exists in the list of favorites.
    * When the user performs a DELETE operation on '/favorites',  delete the list of favorites corresponding to the user, by deleting the favorite document corresponding to this user from the collection.
    * When the user performs a POST operation on '/favorites/:dishId', then   add the specified dish to the list of the user's list of favorite products, if the dish is not already in the list of favorite products.
    * When the user performs a DELETE operation on '/favorites/:dishId', then  remove the specified dish from the list of the user's list of favorite products.


    * A new favoriteSchema and Favorites model has been correctly implemented to take advantage of Mongoose Population support to track the users and the list of favorite products using their ObjectIds in the favoriteSchema and Favorites model.
    * The GET, POST and DELETE operations are well supported as per the specifications above
    * The app.js has been updated to support the new route.


 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## React Native 

The Native app is a mini version of the above React Frontend. 

The Native app will also be using the API and Backend created.

The app also includes table reservation, with integration with the users calendar.

#### Notes: 

https://onedrive.live.com/view.aspx?resid=897203C158E872F%2184124&id=documents&wd=target%28MERN%20stack%29
onenote:https://d.docs.live.net/0897203c158e872f/Documents/marcos%20notesbog/MERN%20stack/


#### Part 1 : Navigators and Components. - done

    The Contact Us page is showing the address of the restaurant in the card format as shown above. - done

       The history information about the restaurant is displayed in a card format as shown above using a functional component named History(). - done
       
       The corporate leadership information is shown in the About Us page in the format as shown above. The leader information is renedered inside a Card. - done

       The AboutComponent is a included using the Stack Navigator and in the Drawer Navigator. - done
       The ContactComponent is a included using the Stack Navigator and in the Drawer Navigator. - done

 
#### Part 2 : UI elements and Redux 

      Add an Action named ADD_COMMENT to the ActionTypes.js. 
      
      Add two action creators named postComment() and addComment(). The postComment() creator will receive the dishId, rating, author and comment as the four parameters. 
      
      Update the comments reducer function to handle the new ADD_COMMENT action and add the comment to the list of comments. The handling of the action should also ensure that appropriate ID will be added to the comment.


      The modal containing the form is correctly added to the DIshdetail component
      The form is correctly configured with the rating, author and comment fields.
      An Icon is added to the RenderDish Card that will trigger the showing of the modal.

      The ADD_COMMENT action is correctly added
      The postComment() action creator is correctly added
      The addComment() action creator is correctly added and will be dispatched by postComment() after a 2 sec delay
      The comment reducer is updated to handle the ADD_COMMENT action

    
#### Part 3: Animations, gestures and redux persist.

     The reservation form zooms in when the user navigates to the reservation view


    An alert containing the information from the reservation form is shown when the user submits the filled reservation form.
    If the user clicks on Cancel, then the form is cleared.
    If the user clicks on OK, then the form is cleared.


    When the user does a left to right gesture on the Dish details card in the Dishdetail component, toggle the comment form modal.

      
      
#### part 4:  Calendar event API, Image Picker API Reservation Functionality with users calendar.

   In this task will make use of the Expo SDK ImagePicker API to enable application to fetch an image from the photo library.

       Update LoginComponent.js to set up a function named getImageFromGallery() that fetches the image from the photo library on the device using the ImagePicker API support. Details of setting up the source to be the Photo Library can be found in the API documentation.
       Add a new button named Gallery that when clicked will initiate the process to enable the user to select a picture from the photo library using the ImagePicker API.
       Once the image is picked, it must be processed through the ImageManipulator to obtain a resized PNG version of the image as we did in the exercise.

   
   In this task will insert a new Calendar event into the default calendar on the mobile device for the table reservation.  will use the Calendar API from Expo SDK for this.  will implement this in the ReservationComponent.js file.

       When the user submits the reservation form,  will obtain the details of the reservation in the handleReservation() function.
       Implement a new function named obtainCalendarPermission() that will ask for permission to access the calendar on the device. The corresponding permission is Permission.CALENDAR.
       Implement another function named addReservationToCalendar() that receives the date information as a parameter. This function is invoked from the handleReservation() function.

      should use the createEventAsync() function from the Calendar API to insert the event into the default calendar (Calendar.DEFAULT). This function takes a title, the start and end time, timezone and location as the parameters.
       Use 'Con Fusion Table Reservation' as the title of the inserted event

       To specify the start Date and end Date,  can convert the Date ISO string into a Date object by using new Date(Date.parse(date)). Furthermore, the Date.parse() gives  the date value in milliseconds.  can set up the end time by adding 2 hours (2*60*60*1000) to the milliseconds and use it to generate the Date object corresponding to the end time of the event.

       For time zone use 'Asia/Hong_Kong', and the location as '121, Clear Water Bay Road, Clear Water Bay, Kowloon, Hong Kong'


       The LoginComponent.js is updated to implement the getImageFromGallery() function that uses the ImagePicker API to enable the fetching of the image from the photo library.

       The LoginComponent.js file is updated to include a button named Gallery that will initiate the procedure to enable the user to select a picture from the photo gallery.


       The image selected by the user is processed using the ImageManipulator to generate a PNG image


       The ReservationComponent.js file is modified to implement the obtainCalendarPermission() function that obtains permission to access the calendar

       The ReservationComponent.js file is modified to implement the addReservationToCalendar() function that inserts the event into the default calendar using the Calendar API.

       The details of the event are correctly inserted setting the title, start and end time and the location correctly.






# Roadmap Learning && "The future updates for the Fullstack Portfolio Project"

______________________________________________________________

## Styled Components


      Cant cache css, only load the css that the page needs 

      Faster initial load.

      Same load the rest of the time since you cant cache styled component.

      Seperation of concerns - All in one, Styled Components. 
      


## LINUX virtual machine
______________________________________


      MONGODB

           https://bitnami.com/stack/mongodb/virtual-machine

           https://www.mysoftkey.com/mongodb/how-to-set-up-vagrant-and-virtualbox-for-mongodb-security-in-window/

           https://codehangar.io/mongodb-image-instance-with-docker-toolbox-tutorial/


_____________________________________________________

 
##  GRAPHQL APOLLO, WEBSockets

     https://www.tutorialkart.com/nodejs/nodejs-tutorial

     https://blog.apollographql.com/full-stack-react-graphql-tutorial-582ac8d24e3b

      Read book 

      https://www.fullstackreact.com/


         ## Ekstra Tutorials.... 

           https://react.rocks/tag/FullStack


           https://graphql.org/@


           https://hackernoon.com/building-a-dashboard-with-react-graphql-de4203eee6c9


           https://medium.com/@nabendu82/build-a-complete-app-with-react-and-graphql-1-f8aff5f1ecc1

           https://www.packtpub.com/web-development/hands-full-stack-web-development-graphql-and-react

           https://hashnode.com/post/react-tutorial-using-mern-stack-ciiyus9m700qqge53mer0isxz

           https://levelup.gitconnected.com/using-graphql-api-with-node-js-and-react-forms-8b13f4b26361

           https://www.sitepoint.com/explore-graphql-with-apollo-react/

           https://levelup.gitconnected.com/the-rise-of-the-nrg-stack-node-js-react-and-graphql-6dfba468ba8a

           https://medium.com/reactbrasil/build-a-chat-with-graphql-react-and-new-stuff-75ee4ffd2f2e


____________________________________________________________________________________
