# Back End Code Challenge (Nest.js)

This is a simple coding task not a coding challenge. This has only **Create and Read** of the small CRUD part for the 
client section of the application.

## Task
1. Create an API endpoint(/users) that accepts following fields  
  1.1 Name
  1.1 Gender
  1. Phone 
  1. Email 
  1. Address
  1. Nationality
  1. Date of birth
  1. Education background 
  1. Preferred mode of contact (select one from email, phone, none)
1. You can be creative with the fields.
1. Add relevant validation to the fields
1. After form submission, if fields are valid persist the data to disk (json file or database)
1. Create an API end point (/users) to retreive the list of users with all the fields.

### Things to consider

1. As the task is easy, we will look into the software design part of things, just making it work is not enough.
1. Naming classes, methods and variables properly will be checked.
1. Simple code is better, still think how easy will it be easy to add things like update and delete client later.
1. The way you construst URLs will also be evaluated.
1. Your git commit history will tell a story of how you thought of the solution please be mindful of it. If you use Pull reqeust to come to your solution its even better.
1. Code it so that the next person who continues that work will like it and not hate the code. Think maintainability of code.
1. Tip: First break your task into logical parts then code it. (First solve the problem. Then write code. - John Johnson)
1. Tip: Commented code is bad, relavant comments about code will be necessary. docs are right places will be appriciated.

### Rules/Requirements

1. You  must use NestJs (https://docs.nestjs.com/)
1. Code must be comply with **ESlint standards** or any coding standard. You can use [styleci](https://styleci.io/) for this or use the one suggested in nestjsdocs (if any).
1. You must have a readme.md file in the root, **well formatted in markdown** (like the one you are reading now) that explains your solution.
1. Use of any extra open-source library or package is allowed only via **npm**. You will need to explain why you used it in the read me file.
1. You must use git and submit this task as a **private or public git repository on github/bitbucket** another option is a zip/tar file.

### Bonus points

1. If you can add detail view page to the listing page, it will be good.
1. Adding pagination will earn you some more point.
1. Adding any form of automated tests like unit or functional will be a plus point. **Refer nestjs docs***
1. Wiring up your tests with a continuous integration (CI) service and reporting coverage is a huge plus. **Wercker.com is a good free CI even for private repos**. If you open source your code and use Travis CI that is also fine.
1. Application level logging with saving logs in a cloud logging service (like logentries.com) **is preferred**. For example log that the user is created successfully.
1. Hosting your small application in free service provider will earn you additional points. Think of first level security too. You can host in on [Zeit](https://zeit.co/) with now-cli, or Heroku or any free host. If you use a free host do mention how you deployed the application. 
1. If you can run your repo through a code quality checking service like [codeclimate](https://codeclimate.com/) it would be great. 
1. Any relevant details in the readme.me file **is a plus**.

### Final Note 

Just completing the task might be at 2-6 hour job. If you just complete the requirements of the task its like getting 40 out of 100. You have been given 7 days so roughly 24 hours (work time) considering that you will invest time in learning things you might not know like automated testing, CI and logging with libraries like monolog and even deploy the app. If you surprise us with a dockerfile in your solution we will be happy.

This task can be done by a student, a software engineer with 1 year experience or a software engineer with 5+ years of experience. The main **question is do you aim for 100/100 or just 40/100** that will just pass you in the task, take a wise decision. Don't do things to just make it work, think about making it maintainable too.
