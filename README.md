# Getting started
 Make sure you have the Angular CLI installed globally. We use npm to manage the dependencies, so we strongly recommend you    to use it. 
 
### Install npm packages ###

------------------------------
A) Install the npm packages described in the package.json and verify that it works:

    npm install 
    
B) We used json server for mock API usage. JSON file is located at root folder.  

    Run : json-server mockJSON.json 
    Resources:
        http://localhost:3000/account
        http://localhost:3000/entitlement
        http://localhost:3000/attributes
        http://localhost:3000/acctdetails


 This will run server on http://localhost:3000.
 
### Run application ###

------------------------------------
 Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of    the source files.
 
        ng serve
        
        
### Unit Tests ### 

-----------------------------------------

TypeScript unit-tests are usually in the src/app folder. Their filenames must end in .spec.ts.
Look for the example src/app/app.component.spec.ts. Add more .spec.ts files as you wish; we configured karma to find them.

        npm run test
        



