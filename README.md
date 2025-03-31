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





    
