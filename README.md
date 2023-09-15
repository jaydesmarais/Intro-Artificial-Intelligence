# CMSC421: Intro to Data Science Fall 22/23

### Course Description:

Introduces a range of ideas and methods in AI, varying semester to semester but chosen largely from: automated heuristic search, planning, games, knowledge representation, logical and statistical inference, learning, natural language processing, vision, robotics, cognitive modeling, and intelligent agents. Programming projects will help students obtain a hands-on feel for various topics.

### Project Notes:

All projects in this repo are the projects I completed as my own submissions for this class. They follow after the coursework for UC Berkeley's Intro to AI course.

### Running the Projects:

Each project has a pdf file of instructions and a corresponding folder, which includes the work I completed.

To run the autograder, simply switch into the folder of the project you would like to run and run `python autograder.py`.

To have some fun with pacman and gridworld, you can inspect the pdf files and run specific commands to see the ai at work. Keep in mind, some examples are meant to fail and simply demonstrate different kinds of search, what they are best for, etc. Here are some fun examples:

1. Project 1:

   - `python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5`
   - `python pacman.py -l trickySearch -p AStarFoodSearchAgent`

2. Project 2:

   - `python autograder.py -q q3`
   - `python autograder.py -q q5`

3. Project 3:

   - `python gridworld.py -a q -k 100 --noise 0.0 -e 0.9`
   - `python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic `

### Project Grades:

Project 1 - Search: 11.96/13
<br/>
Project 2 - Multi-Agent Search: 13/13
<br/>
Project 3 - Reinforced Learning: 14/14
