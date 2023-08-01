Nxt Trendz Authentication
Easy
In Progress

Helpful
In this project, let's build Nxt Trendz app with authentication by applying the concepts we have learned till now.

Refer to the image below:

nxt trendz authentication desktop output

Design Files
Click to view
Extra Small (Size < 576px), Small (Size >= 576px), and Medium (Size >= 768px)
Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login
Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home
Set Up Instructions
Click to view
Download dependencies by running npm install
Start up the app using npm start
Completion Instructions
Functionality to be added

The app must have the following functionalities

When invalid credentials are provided in the login form and Login button is clicked, then the respective error message from the response should be displayed
When the username and password are provided correctly and Login button is clicked, then the page should navigate to Home Route
API Requests & Responses

loginApiUrl

API: https://apis.ccbp.in/login
Method: POST
Description:
Returns a response based on the credentials provided

Sample Success Response
 
JSON
Sample Failure Response
JSON
Components Structure

nxt trendz authentication login component structure breakdown

nxt trendz authentication home component structure breakdown

Implementation Files

Use these files to complete the implementation:

src/App.js
src/components/LoginForm/index.js
src/components/LoginForm/index.css
src/components/Home/index.js
src/components/Home/index.css
src/components/Header/index.js
src/components/Header/index.css
Quick Tips
Click to view

You can use the box-shadow CSS property to apply the box-shadow effect to containers


box shadow
You can use the cursor CSS property to specify the mouse cursor to be displayed when pointing over an element


cursor pointer
You can use the below outline CSS property for buttons and input elements to remove the highlighting when the elements are clicked

Important Note
Click to view

The following instructions are required for the tests to pass

Home route should consist of / in the URL path
Login route should consist of /login in the URL path
No need to use the BrowserRouter in App.js as we have already included in index.js
User credentials

Resources
Image URLs
https://assets.ccbp.in/frontend/react-js/nxt-trendz-logo-img.png alt should be website logo
https://assets.ccbp.in/frontend/react-js/nxt-trendz-login-img.png alt should be website login
https://assets.ccbp.in/frontend/react-js/nxt-trendz-home-img.png alt should be clothes that get you noticed
https://assets.ccbp.in/frontend/react-js/nxt-trendz-log-out-img.png alt should be nav logout
https://assets.ccbp.in/frontend/react-js/nxt-trendz-home-icon.png alt should be nav home
https://assets.ccbp.in/frontend/react-js/nxt-trendz-products-icon.png alt should be nav products
https://assets.ccbp.in/frontend/react-js/nxt-trendz-cart-icon.png alt should be nav cart
Colors

Hex: #1e293b
Hex: #ffffff
Hex: #475569
Hex: #e6f6ff
Hex: #d7dfe9
Hex: #e2e8f0
Hex: #64748b
Hex: #0b69ff
Hex: #ff0b37
Hex: #0967d2
Font-families
Roboto
Things to Keep in Mind
All components you implement should go in the src/components directory.
Don't change the component folder names as those are the files being imported into the tests.
Do not remove the pre-filled code
Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
