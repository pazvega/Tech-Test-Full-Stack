# Technical Test for Junior Full Stack Developers

***

The technical test will involve creating an application and answering a few questions. 
We recommend scheduling at least 4 hours but you can take as long as you want.

Once you have completed the test please upload your application and answers to github.

***

## Coding Test

An application needs to be built that allows an adminsitrator to manage accounts. The application must be able 
to list existing accounts, create new accounts, update accounts and delete accounts. The following information
must be saved for each account.

* First Name
* Last Name
* Email
* Gender
* Date of Birth
* Created Date
* Last Updated Date

### Front End

The front end must allow the administrator to list accounts and perform all CRUD operations. The application must have a menu to be able to navigate between pages.

#### Extra:
1. Search engine where you can search for accounts. When performing a search, it will show a list with the elements that have been found on the same page. These results can be filtered and sorted.
2. Details page: Clicking on an element (or using a control for that purpose), it will open a file with the account's details: First Name, Last Name, Email, Gender.

### Back End

The following API endpoints must be created and hooked up to the front end.


* GET => /accounts
* GET => /accounts/{accountId}
* POST => /accounts
* PUT => /accounts/{accountId}
* DELETE => /accounts/{accountId}


### Technical Requirements

* The backend must be using Flask, FastAPI.
* Front end must run using a JavaScript framework.
* The solution must build and run with one click.

***

### What are we looking for? What does this prove?
* Assumptions you make given limited requirements
* Technology and design choices
* Identify areas of your strengths
* This is not a pass or fail test, this will serve as a common ground that we can deep dive together into specific issues
* Write code as if you are writing code in a team for a production app. Treat it as if you are releasing it to the public.
* Finally, we take pride in the code we write so ensure that your code is well encapsulated and follows a consistent convention. 

***

### Questions

* How long did you spend writing the application?
* What part of the application are you most proud of?
* If you had more time what would you improve in the application?


### How to complete this challenge
* Fork this repo on GitHub
* Complete the design and code as defined to the best of your abilities
* Complete your work in your own github repo and send the results and the Questions to us at people@aitaca.io
