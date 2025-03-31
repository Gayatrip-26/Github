#######BACKEND########
1. Tool Required - vs code, chrome, node.js, git, Github
2. Frontend Technologies - HTML CSS JS , REACT, Bootstrap 
3. Backend Technologies - node,Express, yargs
4. Database Configuration - mongoDB
5. Testing framework - Jest
6. Deployment Platform -aws

Major Component of project -1. console commands-
                               init, add file.text, commint<>- a separate id is generate which is basically folder name, create with a msg , (push, pull, revert - want to go back to previous commit Useful when return deleted file  using id EX. node index.js revert commitID) This three the code in our system is store in cloud permantly for this login to s3 bucket of aws
                            2. Frontend components-
                                (i)Authentication
                                (ii)Dashboard
                                (iii)Repository
                                (iv)Issue
                                3. Database Schema and Model-(i)User Schema
                                                             (ii)Repository Schema
                                                             (iii)Issue Schema
                            4. API Endpoints-
                                Ex./allUsers all are write in routers issue, main, repo, user related are basic endpoints.Every endpoint is link with there corresponding controller.means as ex. if you click delete issue link with issue controller its redirect you to the that delete function which you have created.


**Index will going to attached with main router and main router is attached to the three router user, repo and issue. 

**Start backend---(commands)
1.cd backend
2.npm init -y (-y to select defalut option yes at time of package installation).
#Write a  script as node index.js Ex. "Start":"node index.js" or server.js as per file name.
#aws-config file to coonect bucket
#In controllers make all six command files. 
3.npm install yargs - This command helps us to to reads command from internal. and redirect to that comand file.
4.node index.js init 
5.node index.js add filename.txt
6.npm install uuid - for every commit its crate a new uniqe ID. V1-V5 versions are available V1 had simpliest ID and V5 is hard (236 bits)and strong secure ID.


***Backend Files***
Index.js - Use to understand the command and to the respective controller pass the overall 
          controll.
          yargs is a important dependency to read the commands.and hidebin is a utility of yargs 
          helps to read arguents.
          demandCommand -
          
***Controllers Folder Logic***
init.js = By giving the init command in terminal the controller which is write in index.js file give that init controll to the init.js file.
add.js = 
Commit.js logic- We have kept a temperary file in staging folder we have to a new folder with a commit id and that folder we have to move that file along with creating a json file where we storing time stang (when we store).







    
