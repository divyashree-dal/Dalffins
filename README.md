# Group 03: Dalffins

* ‘Dalffins’ is an online tiffins system that provides its end users to sell and order food in a much easy, healthier, and efficient manner. ‘Dalffins’ is the only application that has provided the flexibility and opportunity for students
to earn from their Culinary skills.

 
## Intended Features: 

### User Profile Management

* Tasks: user registration, user login, forgot user password, update user profile, delete user profile, logout.


## Creation and Modification dates

* Date Created: 27 07 2021
* Last Modification Date: 30 07 2021



## Authors

* Divyashree Bangalore Subbaraya (dv520656@dal.ca) – Developer 



## Built With

* React: Front-end development framework
* Node: Back-end server
* Express: Back-end framework
* Database: MongoDb



## Project Name

* Group03_Dalffins


## Deployed Application link

* https://dalffins.herokuapp.com/



## Softwares used

* Microsoft Visual Studio Code
* Postman
* MongoDb compass



## List of files and its author details


### Frontend files



<table>
  <th>
  File Name
  </th>
  <th>
  Author
  </th>
  <tr>
    <td>1.SignUp.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>2. Login.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>3. MyAccount.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>4. HomePage.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>5. forgotPasswordEnterCode.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>6. ForgotPasswordGetCode.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>7. ResetPassword.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>8. footer.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>9. AboutUs.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>10. ContactUs.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>11. FAQs.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
   <tr>
    <td>12. menu.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
 </table>



### Backend files


<table>
  <th>
  File Name
  </th>
  <th>
  Author
  </th>
  <tr>
    <td>1. jwt.config.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>2. mongodb.config.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>3. passport.config.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>4. token.config.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>5. user.controller.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>6. user.model.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>7. user.route.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>8. app.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  <tr>
    <td>9. server.js</td>
    <td>Divyashree Bangalore Subbaraya</td>
  </tr>
  </table>


## Front-end Framework used

# Material UI

* We have used Material UI as part of for front end development.

Justification: 

		 * Material UI is an open-source, user-friendly React front-end framework [1].

		 * Material UI provides extensive documentation that makes it simple to traverse the framework. 

		 * Material UI is a flexible 12-grid system that enables developers to design responsive websites [1]. 

		 * Material UI allows us to reuse code while also customising it to meet our design needs while providing a high-quality digital experience. 

		 * Material UI offers diverse, vibrant design options that entice people to check them out and include them in their development.

		 * Material UI is a trendy framework utilised by numerous firms such as JP Morgan, Walmart, Spotify, and many more, paving the door for fantastic job prospects [2].



## Back-end Development

# Node and Express 

* We have used the combination of Node and Express as part of back end development.

Justification: 

		 * Node.js is an open-source, cross-platform runtime environment that allows JavaScript developers to build a variety of server-side tools and applications [3]. 

		 * The most popular Node web framework, Express, allows us to install middleware packages at any stage in the request pipeline [3]. 

		 * Most of the high profile companies use the same combination, which helps developers to achieve the targets of the companies during employment. 



## Database

# Mongoose

* We have used MongoDb and Mongoose as part of database development.

Justification: 

		 * Mongoose is an Object Data Modeling (ODM) framework for MongoDB and Node.js [4]. 

		 * Mongoose handles data associations, does schema validation, and is used to translate between objects in code and their representation in MongoDB [4].

		 * MongoDB is a NoSQL document database that does not require a schema. It implies that you may store JSON documents in it [4].

		 * The format of these JSON documents might vary because it is not mandated like SQL databases [4]. 

		 * The above reasons mark the benefits of adopting NoSQL since it speeds up application development and minimizes deployment complexity [4].



## Other frameworks used

# Passport

* I have used passport for user authentication

Justification:

		 * Passport is a Node.js authentication middleware. Passport is very versatile and modular, and it can be seamlessly integrated into any Express-based online application [5].

		 * Passport understands that each application has its own set of authentication needs. Individual authentication techniques, known as strategies, are bundled as modules [5]. 

		 * Applications can select which techniques to use without introducing additional dependencies [5].

		 * The local authentication technique uses a username and password to authenticate users [6]. 

		 * The local authentication technique necessitates a 'verify' callback, which receives these credentials and calls 'done' when a user is provided [6].



# Json Web Tokens(JWTs)

* I have used Json Web Tokens for user authorisation

Justification:

		 * Authorization and information sharing are supported using JSON Web Tokens (JWTs) [7].

		 * Allowing clients to save their session information after signing in is a typical use case [7]. 

		 * The server may trust that the client is a registered user by keeping session information locally and sending it to the server for authentication when performing requests [7].



# Email JS

* I have used Email JS for email integration to send the OTP to the user for the purpose of resetting their password.

Justification:

		 * Emailjs is used to send emails with text, attachments to any smtp sever while maintaining security [8].

		 * Emailjs provides greater flexibility is customising the templates for email according to the project requirements. 



## Colour theme

         * Since our project Dalffins is all about food, we have used white as our colour background theme to enhance readability for our customers. There will be multiple food images displayed on the dashboard, therefore, having a white background will allow users to view the images clearly and order food accordingly. 



## Additional code sources used

We have referred the following:

         * The main documentations of React and material-ui mainly for detailed syntaxes of different tags like typography, paper, text-fields, forms, checkbox, snack bar, card area, Input Adornment, MuiPhoneNumber, MuiAlert, Dialog Title and its actions on MyAccount page, Menu Item for the navigational bar, Accordion for Contact us page. Moreover, we have also used the material icons for all text fields that are part of the user registration, user profile, reset password, user login [2].

         * After creating a cluster in mongoDB cloud, Mongoose and its functions were used since it provided greater code flexibility in developing backend API calls [4].

         * We have used the local strategy and user authentication was done easily using email ID and password [6]. 

         * For token authorisation, We have included authorisation header as a mandatory one from response. Using the token, I have set then local session storage for registered/logged in user [7]. 

         * After logout and delete tasks, token would be removed from the session allowing only loggedIn users to order food [7].

         * We have created a simple template for Dalffins project for sending the OTPs to the customer in order to reset their password [8]. 

         * Usage of material-ui framework with React [9].  

         * The image for the card area for all the pages of user profile management. [10]. 

         * To integrate backend with frontend, we have used axios instances [11]. 

         * Parallax scrolling effect for homepage [12].



## References

[1] "What is Material UI in React?", Educative: Interactive Courses for Software Developers, 2021.[Online] Available: <https://www.educative.io/edpresso/what-is-material-ui-in-react> [Accessed: 7 June 2021].

[2] "The world's most popular React UI framework - Material-UI", V3.material-ui.com, 2021. [Online] Available at: <https://v3.material-ui.com/> [Accessed: 05 June 2021].

[3] "Express/Node introduction - Learn web development | MDN", Developer.mozilla.org, 2021. [Online] Available: <https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/	Introduction#introducing_express> [Accessed: 18 July 2021].

[4] "Introduction to Mongoose for MongoDB", freeCodeCamp.org, 2021. [Online] Available: <https://www.freecodecamp.org/news/introduction-to-mongoose-for-mongodb-d2a7aa593c57/> [Accessed: 18 July 2021].

[5] "Documentation", Passport.js, 2021. [Online] Available: <https://www.passportjs.org/docs/> [Accessed: 18 July 2021].

[6] "passport-local", Passport.js, 2021.  [Online] Available at: <https://www.passportjs.org/packages/passport-local/> [Accessed: 18 July 2021].

[7] "How To Use JSON Web Tokens (JWTs) in Express.js | DigitalOcean", DigitalOcean, 2021. [Online] Available: <https://www.digitalocean.com/community/tutorials/nodejs-jwt-expressjs> [Accessed: 18 July 2021].

[8] "emailjs",  npm, 2021. [Online] Available: <https://www.npmjs.com/package/emailjs> [Accessed: 18 July 2021].

[9] "Getting Started – React", Reactjs.org, 2021.[Online] Available at: <https://reactjs.org/docs/getting-started.html> [Accessed: 04 June 2021].

[10] "Photo by Rachel Park on Unsplash", Unsplash.com, 2021.[Online] Available: <https://unsplash.com/photos/hrlvr2ZlUNk> [Accessed: 07 June 2021].

[11] "axios", npm, 2021. [Online] Available: <https://www.npmjs.com/package/axios> [Accessed: 18 July 2021].

[12] "react-spring", react-spring, 2021. [Online] Available: <https://react-spring.io/components/parallax> [Accessed: 28 July 2021].

