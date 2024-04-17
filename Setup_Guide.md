# Set Up Guide
Do the following steps from the Main branch.  This will be the only time we will code frmom the Main branch.

Step 1: Create Your Repository on Gitub.  Be sure to click the "Add Readme Button" and select the "Node Gitignore Template"
> It's important to note right at the top that a proper MERN stack application has 3 package.json files.
> The first one is created when we run our "npm init" command.  The job of the first package.json is to run both the front end and backend servers at the the same time.
> In most cases the only package we need to install on the root level in the "concurrently" devDependancies. 


Step 2: Clone the Repository to your computer with your ssh key.
Step 3: Cd into project root and run npm init -y
Step 4: run npm create vite@latest
Step 5: Name the vite project "client"
Step 6: Select React from the list
Step 7: Select Javascript from the list.
Step 8: CD into the client and run npm install.
Step 9: Run npm run dev from inside the client folder. Confirm that you see the starting vite project page.
Step 10: Close the client server and cd .. back to the root.
Step 11: run mkdir server to create a server folder.
Step 12: CD into the server folder and run npm init -y 
Step 13: From inside of the server folder run "mkdir config models schemas utils" to create the backend folders
Step 14: CD into config and run "touch connection.js"
Step 15: CD.. back into the server folder
Step 16: CD into the models folder and run "touch index.js User.js"
Step 16: CD.. back into the server folder
Step 17: CD into schemas and run "touch index.js resolvers.js typeDefs.js"
Step 18: CD.. back into the server folder and run "touch server.js"
