* To run the project on the web please visit https:// (I hae deployed the application on Hroku)

* To run the app locally:(Follow each step only after the previous step is completed)
   1. Install nodeJS.
   2. Install Git CLI.
   3. Create a new project folder wherever you wish.
   4. Right click and select 'Git Bash here' option.
   5. Paste this in the command line and press enter =>
   6. Change Directory or move into the project folder.
   7. Type 'npm install' and press enter. 
   8. Type 'npm start' and press enter.(The app will automatically start on port 3000).


* Choices made:
   1. Deciding the component structure based on the idea of seperation of concerns. 
   2. Created a component ToDoTask so that only the task of concern is re-rendered if change occurs.
   3. Created a component ToDoList to nest all the tasks in a list fashion.
   4. Used map function to map each task and its index.
   5. Created InputBar component to retrieve the value from the input.
   6. created App component which houses all the components.
   7. Had to set the state of each component and create functions in the App component since react only supports parent to child communication.
   8. Passed the data from parent to child through props.
   9. Made all the cosmetic changes through App.css