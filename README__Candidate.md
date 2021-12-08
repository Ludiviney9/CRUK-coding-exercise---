Here is my coding exercise, please keep in mind it is my first time building an application using React.js :)

# Bugs

There are still some bugs that I am aware of, but I wasn't able to find the solution by myself despite my researches on the internet / onlineCourses / documentations / youtubeTutorials and would require guidance to fix them :

- In Cypress the Nasa API requests are aborted and return a 499 status eventhough they are sucessful in local environnement. Therefore many of the tests fails unexpectedly. I still have implemented all of them but couldn't run them correctly due to this issue.
- In components files there are parsing errors related to Babel and eslint. If you disable "parser": "@babel/eslint-parser" in ".eslintrc.json file", you will be able to build your application but you will get parsing error and if you enable it you won't be able to build your application but you won't get the parsing errors either.

# Settings

- If you experience some blinking with the videos under Chrome, please disable "use hardware acceleration when available" in the settings

# Improvements sugestions

- The current website only displays the most revealing information, in a further version it would be nice to display more information about the contents (date, format, download button ...). It would also be beneficial to implement dedicated web pages for each item, to add more search filters and to change the items list layout into a grid layout. Something closer to the official website of this API.
- Currently the assets are retrieved in their smallest version but maybe the choice should belong to the user.
- To improve user experience it would be nice : to have keywords auto-completion, to be able to select several keywords, to print more than 10 items (with a page system maybe) and to use a select instead of a text area for the year.
