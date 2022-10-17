# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package. json file is the heart of any Node project. It records important metadata about a project which is required before publishing to NPM, and also defines functional attributes of a project that npm uses to install dependencies, run scripts, and identify the entry point to our package.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
route. used to give npm to identify the project. takes care of dependencies
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build command
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env and env.js
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
$ heroku logs or View Logs with the Heroku Dashboard
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Clone the repository from GitHub to your local device: git clone <YOUR HTTPS URL FROM GITHUB>
Make your changes, and commit them to GitHub
Login to your Heroku account
Set remote for your project
Push to Heroku master to deploy updates
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching allows teams of developers to easily collaborate inside of one central code base
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
 after all automation checks and before the working branch merges with the main branch (source code)
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merge
```