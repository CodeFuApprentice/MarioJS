Instructions to follow for running this little demo game.
Inspired by Super Mario Bros. 
Based on a Tutorial found on Webtips.dev -
https://webtips.dev/webtips/phaser/remake-mario-in-phaserjs-part1#prerequisites
Not completely my own creation, and is my 1st attempt at creating a game using HTML, CSS, Javascript, and using the Phaser Framework for Javascript.

Project coded by CodeFuApprentice.

Note: Although functional, this short game isn't complete. I have yet to implement the end of level flag as typically seen in the NES game Super Mario Bros by Nintendo.



Size of Project is around 560KB before installation. 
Please follow these instructions:

** Installation instructions **
Assuming Node.JS is installed on your computer when opening project with VS Code.

Download MarioJS project from github

Create empty MarioJS folder on Desktop

Open MarioJS folder in VS Code

<ctrl + '> to open terminal in VS Code

@ Terminal:
Type 'npm create vite@latest' into terminal
Project Name: './' [Enter]

Package Name: 'mariojs' [Enter]

Select Vanilla Framework [Enter]

Select Javascript [Enter]

@ Terminal:
npm install [Enter]

@ Terminal:
npm install phaser [Enter]

'node_modules' folder will be created as a result of following these steps, folder will be about 178MB

delete all but 'node_modules' folder from MarioJS folder you created on your desktop

extract MarioJS project to the folder opened in VS Code

@ Terminal:
npm run dev [Enter] - To start dev server

Open a browser and navigate to VITE Local host address shown in terminal
(Typically: ' http://localhost:5173/ ')

**Included package.json file has additional '--host' parameter to display your IP address in the VS Code Terminal when you start VITE server.

Controls: Just 3 keys, as you'd expect Left and Right to move, and Space bar to Jump.


