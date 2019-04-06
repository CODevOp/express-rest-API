# Building a simple REST API with NodeJS and Express.
Tutorial Source: https://medium.com/@onejohi/building-a-simple-rest-api-with-nodejs-and-express-da6273ed7ca9


# Commands to create and run application
* Create a git repsository
    Reference: https://stackoverflow.com/questions/46877667/how-to-push-a-new-initial-project-to-github-using-vs-code
    ``` powershell
    git init
    git commit -m "Initialization of repository"
    git remote add origin "https://github.com/CODevOp/express-rest-API.git"
    git remote -v
    // before running the following command create the respository on github.
    git push -u origin master
    ```
* Push updates to git repository
    ``` powershell
    git push -u origin master

    ```
* Initialize a new express application
    ``` powershell
    npm install -g express-generator
    ``` 
* Install express in your application
    ``` powershell
    npm install express --save
    ``` 
* Run express app
    ``` powershell
    node app.js
    ``` 
* Ctrl-C to stop server
* Before adding/updating the repository add .gitignore file to prevent git from adding node_modules.
    ``` powershell
    // copy the file from github using raw file and curl command
    curl -o .gitignore "https://raw.githubusercontent.com/github/gitignore/master/Node.gitignore"
    git add .gitignore // adds new files
    git commit -m "Add .gitignore file" // commits change
    git push - u origin master

    ``` 



