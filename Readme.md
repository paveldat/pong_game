# Pong Game using Hand Gestures
In this project, I will learn how to create a forever-alone pong game for all the lonely people out there. 
I will first learn how to track hands and then use some images to overlay on our game.

## Features
* Can track your hand in real-time
* Can play alone or with a friend

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/pong_game.git`
2. Install all the requirements
`run libraries.bat` or
`pip install -r requirements.txt`
3. Run the program
`python main.py`

## Help
You might face issue with webcam not showing and you get errors.
To solve it just change the value in this line (for example to `1`).
`cap = cv2.VideoCapture(0)`
Increment this number until you see your webcam.

## Result

![Alt Text](https://github.com/paveldat/pong_game/blob/main/img/Result.gif)
