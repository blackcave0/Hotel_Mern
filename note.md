# ===~===~===~===~===~===-:[BACK-END]:-===~===~===~===~===~=== #

# [*] First create a server in Server file 

# [*] Create a roter folder and create [auth-router.js] file
<!-- In this file we will Initialize path's for page navigation home, about login etc -->
<!-- After creating and Initialize function of router goto Index.js file define this router file path at the top... -->

<!-- END -->

# [*] Create a controllers folder
<!-- Controllers like mini app, In this file we can Create Methods or Function for login registration or etc and do main action here.. -->
<!-- Create a [auth-controller.js] file  -->

<!-- END -->

# [*] Create a util folder for database
 <!-- In this folder we can add file of mongodb connection -->
 <!-- Install packages of [npm i mongoose and dotenv] -->
 <!-- create a file in server folder [.env] for securing database url and password  -->

<!-- END -->

# [*] Create a folder name of model
<!-- This folder can contains [userSchema.js] file where we can define field of users values -->
<!-- After Creating **userSchema** goto [auth-controller.js] file and create method for storing data into database -->

<!-- ? Securing password using bcryptjs [npm i bcryptjs] -->
<!-- bcrypt use in auth-controller file and userSchema file -->

<!-- **JSONWEBTOKEN** -->
<!-- Authentication => Verifying the identiy of a user or client -->
<!-- Authorization => Determining what actions a user or client alowed to perform -->
<!-- This method use in (model) folder [userSchema.js] file -->
[https://jwt.io/introduction]
<!-- First Create a Instance or Function in Schema file using [methods] then use in [auth-controller.js] file -->
***END***

# [*] Create Login Route 
<!-- In [auth-controller.js] file Initialize Login Route -->
***END***

# [*] Zod Validation Package form 
<!--Install zod package form npm i zod, and Its a middleware  -->
<!-- Create a folder [validators] and create a file name of [auth-validator.js] -->
<!-- In [auth-validator.js] create Schema [signUpSchema] and export it, after this import in [auth-router.js]-->
<!-- After creation of Schema Create a folder [middleware] -->
<!-- In [middleware] folder, create a file [validate-middleware.js] for creating middleware -->
<!-- Go [auth-router.js] import [validate] module from [validate-middleware.js] -->
<!-- all error message and method defin in [error-middleware] -->
***END***

# [*] Error Middleware
<!-- This middleware is for all error show in one file and throw in fornt-end -->
<!-- Create a file [error-middleware.js] file in [middleware] folder -->
<!-- Initialize path in index.js  -->
***END***

# [*] Contact Form 
<!-- Create a file [contact-model.js] in [model] folder -->
<!-- Create Route of [contact-router.js] for this file in [Router] folder  -->
<!-- Create a file [contact-form.js] in [controller] folder.. ()then import in [contact-router.js] file -->
<!-- Initilialize path [contact-router.js] in [index.js] server file -->
***END-END-END***

# ===~===~===~===~===~===-:[FORN-END]:-===~===~===~===~===~=== #

# [*] ERROR OF CORS POLICY 
<!-- Install a package of npm i cors  -->
<!-- after installing this package Initialize the function and method after do all this code work fine... -->


# ===~===~===~===~===~===-:[BACK-END]:-===~===~===~===~===~=== #
# [*] JSON WEB TOKEN 
<!-- Create a route for user in [auth-router.js]  -->
<!-- Create a function [Users] in [auth-controller.js] and after creating the [Users] create the route for this function in [auth-router.js] -->
 <!-- Create a function [authMiddleWare] in [middleware] file, were the name [auth-middleware] -->
 <!-- After Creation of the middlewere use this in [auth-router][auth-Controler] route -->
***END***

# [*] SERVICES PAGE AND FETCH DATA FROM DATABASE
[backend-Process]
<!-- Create a file [service-model.js] in the folder of [models] and Initialize the (Schema) -->
<!-- After the Initializing of the schema, Create another file name of [service-router.js] in the folder of [router] and create the route for [service-model.js {schema}]-->
<!-- After the Initialization the of [service-model.js], create a file in folder of [controllers] for getting data and Init the function for (services) -->
<!-- At the end define the route of [service-router.js] in the [index.js]  -->

!!! install a package = npm i react-toastify for pop-up alert

# [*] ADMIN ROUTER AND PAGE 
<!-- Create a file in [router] folder [admin-router.js] -->
<!-- After this goto [controllers] and create a new file [admin-controlle.js] in this file create a function (getAllUsers) -->

# [*] CONTACTS ROUTER AND PAGE DATA ROUTE 
<!-- Create route for this in the [router][admin-router.js] as (/contacts) -->
<!-- Add middlewere for authorization user login -->

# [*] CREATION OF THE ADMIN ISADMIN 
<!-- Create a new file [admin-middlewere.js] in [middlewere] folder for the function or method of isAdmin  -->

# ===~===~===~===~===~===-:[FORN-END]:-===~===~===~===~===~=== #
# [*] DELETE THE USER
<!-- Delete user [AdminUser.jsx] = create a new route for delete user in [admin-router] -->
<!-- Initialize the delete function in [admin-controller.js] -->

# [*] UPDATING THE USER DATA [FRONT-END] 
<!-- In the [AdminUser.jsx] file, we can deal with EDIT button -->
<!-- Initialize the Route for this method in [admin-router] -->
<!-- After the Creation function or Route go to [admin-controller.js] and Initialize the method for updating the user edit  -->
<!-- Create a FrontEnd page Name [AdminUpdate.jsx] in {pages} folder -->

# [*] UPDATING THE USER DATA [BACK-END] 
<!-- Create Route for this method in [admin-router.js] start line [15] -->

# [*] CONTACT DELETE 
<!-- Create Route for this method in [admin-router.js] -->
<!-- ! there is the function name are same but route is different [userDelete] and [contactDelete] both are same function but working is proper way -->