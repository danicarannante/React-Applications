# React-Applications
This Git repository contains two React applications: "Inventory" and "Tic-Tac-Toe." Both applications are coded in JavaScript and utilize the React programming framework. The "Inventory" application is designed to create a local web page that allows users to manage an inventory of items, enabling them to add, remove, and search for items. The inventory data is stored and retrieved using a JSON server on the backend. On the other hand, the "Tic-Tac-Toe" game is a classic implementation of the popular tic-tac-toe game, allowing users to play against each other.

## Inventory Application
Features
The "Inventory" application offers the following features:

Add items to the inventory with their relevant details such as name, description, quantity, etc.
Remove items from the inventory by selecting them from the list.
Search for items in the inventory based on specific criteria like name, category, etc.
Display a table of the added items, making it easy to review the inventory contents.
Utilizes JSON server for backend functionality, providing a seamless experience for managing inventory data.

### Setup and Installation
To run the "Inventory" application, follow these steps:

1. Clone the repository to your local machine using Git.  <br />
_git clone <repository-url>  <br />_
2. Navigate to the "inventory" directory using the command line.  <br />
_cd inventory  <br />_
3. Install the required dependencies using npm or yarn.  <br />
_npm install or yarn install_  <br />
4. Start the JSON server for backend functionality.  <br />
_json-server --watch db.json --port 8000_
5. Start the React development server.  <br />
_npm start or yarn start_  <br />

Usage  <br />
Once the application is running, you can access it in your web browser at http://localhost:3000. The "Inventory" page will be displayed, and you can start adding, removing, and searching for items using the available forms and buttons.  <br />


## Tic-Tac-Toe Game
Features
The "Tic-Tac-Toe" game offers the following features:  <br />

Classic 3x3 tic-tac-toe board where two players can take turns to play.
Interactive gameplay allowing players to click on the grid cells to make their moves.
Keeps track of the game state, including win, lose, or draw outcomes.
Supports playing against another human player.

### Setup and Installation <br />
To run the "Tic-Tac-Toe" game, follow these steps: <br />

1. Clone the repository to your local machine using Git. <br />
_git clone <repository-url>_ <br />
2. Navigate to the "tic-tac-toe" directory using the command line. <br />
_cd tic-tac-toe_ <br />
3. Install the required dependencies using npm or yarn.  <br />
_npm install or yarn install_  <br />
4. Start the React development server.  <br />
_npm start or yarn start_  <br />

Usage
Once the application is running, you can access the Tic-Tac-Toe game in your web browser at http://localhost:3000. The game board will be displayed, and you can take turns clicking on the cells to make your moves.
