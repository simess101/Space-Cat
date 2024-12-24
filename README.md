🐱🚀 SpaceCat WebGL Game
Welcome to SpaceCat, a fun and exciting WebGL game built using Unity! In this game, you'll guide a clever spacefaring cat through various challenges, and using portals to navigate space!

🚀 How to Play
Controls
Move Left/Right: Use the A and D keys  to move.
Shoot Portals: Use the Left Mouse Button to shoot portals. Aim with the mouse, and shoot your purple portals to navigate the level and flip gravity when going through the green portal
Restart the Game: Press Space after getting to SpaceCat to restart the game.
Goal
Save the SpaceCat.
💻 Running the Game
Running Locally
If you want to download and run the game locally on your machine:

Download the Build:

Clone this repository or download the ZIP file containing the WebGL build files.
Run a Local Server: Since browsers restrict running WebGL content from the file system, you'll need to run a local server to play the game locally. Here are a couple of ways to do this:

Option 1: Using Python (for Windows/Mac/Linux):

Open a terminal/command prompt.
Navigate to the folder where you extracted the game files.
Run the following command:
```bash
python -m http.server
```
Open your browser and go to http://localhost:8000 to play the game.
Option 2: Using Node.js and HTTP-Server:

Install Node.js from here.
Open a terminal/command prompt and install the http-server package:
```bash
npm install -g http-server
```
Navigate to your game folder and run the following command:

```bash
http-server
```
Open your browser and go to http://localhost:8080.

🌐 Publishing the Game
To host the game online, ensure your repository is set up for GitHub Pages:

Go to your repository settings.
Scroll down to the GitHub Pages section.
Set the source to the main branch (or gh-pages if you created a separate branch).
Share the link to your GitHub Pages so others can play it!
