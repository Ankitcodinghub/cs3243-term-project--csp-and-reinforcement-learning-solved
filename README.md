# cs3243-term-project--csp-and-reinforcement-learning-solved
**TO GET THIS SOLUTION VISIT:** [CS3243 Term Project- CSP and Reinforcement Learning Solved](https://www.ankitcodinghub.com/product/cs3243-introduction-to-ai-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114605&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3243 Term Project- CSP and Reinforcement Learning Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
&nbsp;

1 Overview

Project 2 is divided into 2 parts:

1. Solving Sudoku Puzzles as Constraint Satisfaction Problems (CSPs)

2. Solving the Pacman Game via Reinforcement Learning

1.1 General Project Requirements (Both Parts)

The general project requirements are as follows:

• Group size: 3-4 students

• Submission Platform: LumiNUS → CS3243 Module → Project 2 Submission

Folder

• Submission Format: One standard (non-encrypted) zip file containing all necessary project files. In particular, it should contain exactly two files and one folder containing another two files.

As to the specific project requirements, you must complete and submit the following.

• Part 1 (CSPs):

1. A file containing an implementation of the Backtracking Search algorithm to solve Sudoku puzzles as CSPs.

2. A two to four page report that describes the following:

(a) Problem specification

(b) Algorithm variations considered

(c) An experimental setup to evaluate 2 or more different implementations

(d) Results and Discussion

• Part 2 (Reinforcement Learning): You will implement a Q-learning algorithm who will learn how to play Pacman. In particular, you will provide implementations of the:

1. Q-learning algorithm.

2. Approximate Q-learning algorithm.

3. Customised feature extractor.

You do not need to write a report for Part 2.

2 Solving Sudoku Puzzles using CSPs

The objectives of this part of the project are to:

1. Gain experience with the definition of a constraint satisfaction problem.

2. Become familiar with the implementation of the backtracking search algorithm.

3. Learn to recognize the effect that the different methods of selecting variables and values, and for performing inference, have on backtracking.

2.1 Background: The Sudoku Puzzle

Soduko is a logic-based, combinatorial number-placement puzzle. The objective is to fill a 9 × 9 grid with digits so that each column, each row, and each of the nine 3 × 3 subgrids that compose the grid contain all digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle, has a single solution. Figure 1 shows a sample Sudoku puzzle.

Your task is to implement the backtracking search algorithm to solve Sudoku puzzles as CSPs. In order to do this, you should:

1. Model Sudoku puzzles as CSPs.

2 5 3 9 1

1 4

4 7 2 8

5 2

9 8 1

4 3

3 6 7 2

7 3

9 3 6 4

Figure 1: A simple Sudoku Puzzle

2 5 8 7 3 6 9 4 1

6 1 9 8 2 4 3 5 7

4 3 7 9 1 5 2 6 8

3 9 5 2 7 1 4 8 6

7 6 2 4 9 8 1 3 5

8 4 1 6 5 3 7 2 9

1 8 4 3 6 9 5 7 2

5 7 6 1 4 2 8 9 3

9 2 3 5 8 7 6 1 4

Figure 2: Solution to the Sudoku puzzle in Figure 1.

2. Implement variants of the backtracking search algorithm, where variants include:

(a) variable ordering mechanisms/heuristics

(b) value ordering heuristics

(c) inference mechanisms

3. Evaluate and select one variant to submit

4. Report on the experiments conducted to make your selection

2.2 Submission Specifications

You need to submit two files on LumiNUS, your python code file and the report PDF. Make only one submission (i.e., one set of two files) per group. File names:

• The code filename should be CS3243P2SudokuXX.py

• The report filename should be CS3243P2SudokuXX.pdf where XX is your group number.

For example, Group 3 should submit two files: CS3243P2Sudoku03.py, and CS3243P2Sudoku03.pdf (note that it is 03 and not 3). Points will be deducted for not following the naming convention; please follow it closely.

Input: The Sudoku puzzle input is a text file containing 9 lines (1 line per row). Each line contains 9 digits, with 0-values representing an empty cell.

Each given Sudoku puzzle will be:

• A 9 × 9 puzzle

• Valid: i.e., each row, column and subgrid will not contain any duplicate non-zero digits

• Well-formed: has a unique solution (and is thus, in particular, solvable) For example, the puzzle from Figure 1 would be encoded as:

2 5 0 0 3 0 9 0 1

0 1 0 0 0 4 0 0 0

4 0 7 0 0 0 2 0 8

0 0 5 2 0 0 0 0 0

0 0 0 0 9 8 1 0 0

0 4 0 0 0 3 0 0 0

0 0 0 3 6 0 0 7 2

0 7 0 0 0 0 0 0 3

0 0 3 0 0 0 6 0 4

Output: The expected output should have the same format as the input. Your input should be valid, and only contain the digits 1-9. Thus, the solution for the puzzle given in Figure 1 should be:

2 5 8 7 3 6 9 4 1

6 1 9 8 2 4 3 5 7

4 3 7 9 1 5 2 6 8

3 9 5 2 7 1 4 8 6

7 6 2 4 9 8 1 3 5

8 4 1 6 5 3 7 2 9

1 8 4 3 6 9 5 7 2

5 7 6 1 4 2 8 9 3

9 2 3 5 8 7 6 1 4

• The solution to the given Sudoku puzzle should be returned by the solve() function.

• You SHOULD NOT modify the main function.

• Your submission must be executable. If your program cannot be executed, you will get 0 for the code components.

2.3 Report

Your report should at least be 2 pages long, and no longer than 4 pages. It must include the following sections:

1. Problem definition – Sudoku as a CSP. How did you set up your problem?

2. Algorithm variants – what did you try? What were the considerations and thought process behind it?

3. Experimental setup – how do you know that the solution you picked is the best? How did you design experiments that prove it to us?

4. Results and Discussion – how well is your solution doing? Were you able to complete all possible puzzles? Where did it do well? Where did it fail?

You must submit the report in PDF format.

2.4 Marking Rubrics

1. Report on Evaluated CSP-based Sudoku Solutions (total of 6 points)

(a) Problem Definition (1 point)

(b) CSP Algorithms/Heuristics Description and Analysis (1 point). We expect to see a discussion of at least two variants you explored and what were the tradeoffs/considerations that led you to your final choice.

2. Experiment Setup (1 point). We expect you to experiment with different CSP implementations, in order to determine the best solver you can come up with. You will submit one solver, best on your own analysis (as show in the Description/Analysis section as well as the Experimental Evaluation).

3. Results, Analysis and Rationale for Selection (3 points): convince us why your solution is great. This could be done analytically (we prove that the following evaluation function/heuristic/variable selection/value selection method does well), or experimentally (running over x iterations of increasingly difficult puzzles, our method outperforms alternatives A, B and C).

4. Code for Sudoku Solutions (total of 4 points)

Basic Puzzle Set: Not working/impractical to run 0 points

Working but below benchmark 1 point

Achieves/outperforms benchmark 2 points

Advanced Puzzle Set: Not working/impractical to run 0 points

Working but below benchmark 1 point

Achieves/outperforms benchmark 2 points

Code for alternative solvers and their evaluation can be submitted, but will not be graded.

3 Part 2 – Solving Pacman via Reinforcement Learning

The objectives of this part of the project are to:

1. Gain experience with reinforcement learning.

2. Become familiar with the implementation of the Q-learning and approximate Q-learning algorithms.

3. Gain experience with feature extraction in a complex environment.

3.1 The Pacman Game

In this project , you will implement a Q-learning agent as well as an approximate Qlearning agent and train them to play the game of Pacman . This project includes an autograder for the first two subtasks. You can run the following command to grade yourself:

python autograder.py

It can also be run for one particular task, such as task 2, by:

python autograder.py -q q2

The code for this project contains the following files:

featureExtractors.py Classes for extracting features on hstate, actioni pairs. Used for the approx. Q-learning agent in qlearningAgents.py.

Defines methods for general MDPs.

learningAgents.py Defines the base class QLearningAgent, which you will extend in your implementation.

util.py Utilities, including util.Counter, which

is particularly useful for designing Q-learning agents.

The remaining files are not as important and need not be reviewed.

3.2 Submission Specifications

For this part of the project, you will need to submit two files: qlearningAgents.py and featureExtractors.py.

Make only one submission (i.e., one set of two files) per group.

Do not modify the file name.

Place your two files in a folder named CS3243P2PacmanXX, where XX is your group number. For example, the folder CS3243P2Pacman03/ should contain the qlearningAgents.py and featureExtractors.py files for Group 3.

Points will be deducted for not following the naming convention, please follow it closely.

3.3 Task 1

First, you will implement a Q-learning agent by completing the QLearningAgent class in qlearningAgents.py. In particular, you need to implement the update, computeValueFromQValues, getQValue, computeActionFromQValues and getAction methods.

Important: Ensure that you only access Q values by calling getQValue, especially within the computeValueFromQValues and computeActionFromQValues functions. This abstraction will be useful for Task 2, where you will have to override getQValue to use features of state-action pairs rather than the state-action pairs directly.

Testing: Time to play some Pacman! Pacman will play games in two phases. In the first phase, training, Pacman learns about the values of positions and actions. Because it takes a very long time to learn accurate Q-values even for tiny grids, Pacman’s training games run in quiet mode by default, with no GUI (or console) display. Once Pacman’s training is complete, it will enter testing mode. When testing, Pacman’s self.epsilon and self.alpha will be set to 0.0, effectively stopping Q-learning and disabling exploration, in order to allow Pacman to exploit its learned policy. Test games are shown in the GUI by default. Without any code changes you should be able to run Q-learning Pacman for very tiny grids as follows:

python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid

Note that PacmanQAgent is defined based on the QLearningAgent you have written. PacmanQAgent is only different in that it has default learning parameters that are more effective for the Pacman problem (ε = 0.05,α = 0.2,γ = 0.8). You will receive full credit for this question if the command above works without exceptions and your agent wins at least 80% of the time. The autograder will run 100 test games after the 2000 training games. To use the autograder to test your answer, run:

python autograder.py -q q1

If you want to experiment with learning parameters, you can use the option -a, for example

-a epsilon=0.1, alpha=0.3, gamma=0.7

These values are accessible as self.epsilon, self.gamma and self.alpha within the agent. In the example run above, a total of 2010 games will be played, but the first 2000 games will not be displayed because of the option -x 2000, which designates the first 2000 games for training (no output). Thus, you will only see Pacman play the last 10 games. The number of training games is also passed to your agent as the option numTraining. If you want to watch 10 training games to see what’s going on, use the command:

python pacman.py -p PacmanQAgent -n 10 -l smallGrid -a numTraining=10

During training, you will see some statistics about Pacman’s performance every 100 games. Epsilon is positive during training, so Pacman will play poorly even after having learned a good policy: this is because it occasionally makes a random exploratory move into a ghost. As a benchmark, it should take between 1000 and 1400 games before Pacman’s rewards for a 100 episode segment becomes positive, reflecting that it’s started winning more than losing. By the end of training, it should remain positive and be fairly high (between 100 and 350).

Make sure you understand what is happening here: the MDP state is the exact board configuration facing Pacman, with the now complex transitions describing an entire ply of change to that state. The intermediate game configurations in which Pacman has moved but the ghosts have not replied are not MDP states, but are bundled in to the transitions.

Once Pacman is done training, it should win very reliably in test games (at least 90% of the time), since now it is exploiting its learned policy. However, you will find that training the same agent on the seemingly simple mediumGrid does not work well.

In this implementation, Pacman’s average training rewards remain negative throughout training. At test time, it plays badly, probably losing all of its test games. Training will also take a long time, despite its ineffectiveness. Pacman fails to win on larger layouts because each board configuration is a separate state with separate Q-values. It has no way of generalizing that running into a ghost is bad for all positions. Obviously, this approach will not scale.

3.4 Task 2

In this task, you will implement an approximate Q-learning agent by completing the

ApproximateQAgent class in qlearningAgents.py. It should learn weights for features of states, where many states might share the same features. In particular, you need to implement the update and getQValue methods.

Approximate Q-learning assumes the existence of a feature function f(s,a) over state and action pairs, which yields a vector (f1(s,a),…,fi(s,a),…,fn(s,a)) of feature values.

We provide feature functions for you in featureExtractors.py. Feature vectors are util.Counter (like a dictionary) objects containing the non-zero pairs of features and values; all omitted features have value zero.

The approximate Q-function takes the following form:

where each weight wi is associated with a particular feature fi(s,a). In your code, you should implement the weight vector as a dictionary mapping features (which the feature extractors will return) to weight values.

You will update your weight vectors in a manner that is similar to how you updated the Q-values:

difference = (r + γ · maxa0Q(s0,a0)) − Q(s,a) wi ← wi + α · difference · fi(s,a)

Note that the difference term is the same as in normal Q-learning, where r(s,a) is the experienced reward, and where s0 = δ(s,a).

By default, ApproximateQAgent uses the IdentityExtractor, which assigns a single feature to every hstate,actioni pair. With this feature extractor, your approximate Q-learning agent should work identically to PacmanQAgent. You can test this with the following command:

python pacman.py -p ApproximateQAgent -x 2000 -n 2010 -l smallGrid

Important: ApproximateQAgent is a subclass of QLearningAgent, and it therefore shares several methods like getAction. Make sure that your methods in QLearningAgent call getQValue instead of accessing Q-values directly, so that when you override getQValue in your approximate agent, the new approximate q-values are used to compute actions.

Once you’re confident that your approximate learner works correctly with the identity features, run your approximate Q-learning agent with the provided simple feature extractor, which can learn to win with ease:

python pacman.py -p ApproximateQAgent -a

extractor=SimpleExtractor -x 50 -n 60 -l mediumGrid

Even much larger layouts should be no problem for your ApproximateQAgent.

python pacman.py -p ApproximateQAgent -a

extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic

If you have no errors, your approximate Q-learning agent should win almost every time with these simple features, even with only 50 training games.

For grading, your approximate Q-learning agent will be run and checked to determine if it learns the same Q-values and feature weights as our reference implementation (when each is presented with the same set of examples). To test your implementation, run the autograder:

python autograder.py -q q8

3.5 Task 3

This final task requires you to implement your own feature extractor for the Pacman game. In particular, you will need to implement the NewExtractor class in featureExtractor.py.

This task will require you to be innovative. While there is no correct answer to this task, you should try your best to find the most suitable set of features in the Pacman world. We will grade you based on how well your agent performs.

To play around with your implemented feature extractor, use the following command:

python pacman.py -p ApproximateQAgent -a

extractor=NewExtractor -x 50 -n 60 -l mediumClassic

Please feel free to change the parameters when you are experimenting with your implementation.

3.6 Marking Rubrics

• Code for Pacman Solutions (10 points) Q-learning Implementation on standard Pacman problem – based on expected benchmark scores (3 points)

Approximate Q-learning Implementation on Standard Pacman problem based on expected benchmark scores (3 points)

Solution for Mutated Pacman variant (2 points)

Think of this as hidden test cases for task 1 and 2

Requires a universally applicable agent

Solution for the variant with customised Features (2 points)

If not attempted or not working 0 points

Greater than or equal to benchmark 1 point

Greater than or equal to benchmark and Top 50% 2 points
