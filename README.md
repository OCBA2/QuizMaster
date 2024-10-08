# QuizMaster

This Python code consists of two parts: a Quiz Creator and a Quiz Game. You can launch the Quiz Creator with the Quiz Game but not the other way round. The Quiz Creator tool allows you to add, edit, delete, save, and load quiz questions. Quiz Creator uses PySimpleGUI. The Quiz Game, built with pygame, lets you play the quiz with timed questions.

## How to Use

### Install
#### Option 1 (Easy):
1. Clone this repository `git clone https://github.com/hermonochy/QuizMaster.git`
2. Run the included script `./setup.sh` (Ubuntu/Debian) or `setup.bat` (known issues with msys2 python conflict, only worry about this if you are C++ dev) script for windows. Note: these scripts may take some time to complete.

#### Option 2 (Advanced, Ubuntu/Debian only):
1. Clone this repository `git clone https://github.com/hermonochy/QuizMaster.git`
2. Set up a new virtual environment `python3 -m venv .`(optional, but recommended).
3. Start the environment.`source ./bin/activate`
4. Install tkinter.`sudo apt-get install python3-tk`
5. Install packages in `requirements.txt`.`pip3 install -r requirements.txt`

### Quiz Creator

![](images/QM2.png)

1. Run quizcreator by opening QuizMaster (instructions below) and clicking "Make a quiz".
2. Use it to manage and create quiz questions. The add button can add questions. As it is multiple choice, you need to give a correct answser and wrong answers, seperated with commas. Afterwards, save it in an apropriate folder. Format is json.

### Quiz Game

![](images/QM1.png)

In a command line window, enter `./run.sh` to start the code in linux, or `run.bat` for windows. Press either `Play a Quiz` or `Make a Quiz` in the homepage. `Make a Quiz` will open QuizCreator, `Play a Quiz` will allow you to search a quiz to play! You can either press the number allocated to the answer or, if you don't have a keyboard, click on the awnser. Remember, you have a time limit!

![](images/QM3.png)

 At the end it will tell you your score and either congratulate you or suggest you revise depending on the score.
 
![](images/QM4.png)

There is also a preferences window where you can change the song, volume and colour:

![](images/QM5.png)

## QuizMasterMini
 [QuizMasterMini](https://github.com/hermonochy/QuizMasterMini) is a smaller version of the application, made for smaller devices.


## Features

### Quiz Creator:
- Add, Edit, Delete, Save, Load functions for quiz questions.
- Interactive GUI interface for managing quiz questions.

### Quiz Game:
- Timed quiz questions with countdown.
- Ability to answer questions and receive scores.
- Background music during gameplay.
- Start QuizCreator
- Change settings

Enjoy the combined functionalities of creating quizzes and playing quiz games with the Quiz Creator and Quiz Game applications provided in this code! Please add some extra quizzes for others. This repository is open to pull requests.
Note: Many of the example quizzes are AI written, so may contain incorrect information.

## Future Work

- more methods of answering questions
- adding pictures to questions
- more user friendly method of starting
- multiplayer options
- different game modes


