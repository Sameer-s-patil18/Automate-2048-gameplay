# Automate-2048-gameplay
2048 is a simple game where you combine tiles by sliding them up, down,  left, or right with the arrow keys. You can actually get a fairly high score  by repeatedly sliding in an up, right, down, and left pattern over and over  again

Make sure you have the following prerequisites installed:
1) Python 
2) Selenium: to install selenium use ' pip install selenium'(in terminal) or !pip install selenium if doing in jupyter notebook
3) chromedriver: to install this go to https://googlechromelabs.github.io/chrome-for-testing/ , version used here is 116.0.5845.96

Summary of how the program works:

1)Import Necessary Libraries: The program uses a library called Selenium, which allows us to control a web browser (like Chrome) using Python. It also imports some specific functionality from Selenium for interacting with web pages.

2)Set Up the Web Browser: The program sets up a web browser (in this case, Google Chrome) to be controlled by Python. You need to have Chrome and a special tool called a WebDriver installed for this to work.

3)Open the 2048 Game: The program opens the 2048 game by navigating to the game's website in the web browser.

4)Define a Function to Play the Game: A function called play_2048() is defined. This function will be responsible for automating the game. It repeatedly sends commands to the game to make moves (up, right, down, left) to try to win.

5)Automate Key Presses: Inside the play_2048() function, there's a loop that keeps sending arrow key presses (like pressing the up, right, down, left keys on your keyboard) to the game one after the other. It waits for a short time (0.5 seconds) between each move to give the game a chance to respond.

6)Stop the Program: The program runs the game indefinitely until you decide to stop it manually. You can stop it by pressing Ctrl+C in your terminal or command prompt.

7)Close the Browser: After you stop the program, it closes the web browser.
