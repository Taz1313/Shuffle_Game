A small random word search game developed with the aura components.

Before deploy, you have to create a customised object with 2 fields :

> Custom object informations 
 - Label : Word Shuffle
 - Plural Label : Word Shuffle
 - Object Name : Word_Shuffle
 - Record Name : Game Number
 - Data Type : Auto Number
 - Display Format : Game-{0000}
 - Starting Number : 1
 - Save

> Field Mode informations 
 - Type : Text
 - Field label : Mode
 - Length : 10
 - Field Name : Mode
 - Save

> Field Result informations 
 - Type : Text
 - Field label : Result
 - Length : 10
 - Field Name : Result
 - Save

Feel free to customize authorizations.

To deploy this game in your org using VS Code :

- Create a new project using the command ">SFDX: Authorize an org"
- Copy/Past this repository on your current project
- Right click on main file and select "SFDX: Deploy Source to Org"

Now, you have to edit the page where you want to display the game :

- On custom components, make sure that you drag and drop "BoardPanel" and "GameResult" components.

That's all. Have fun!