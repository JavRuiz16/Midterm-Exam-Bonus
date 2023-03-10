# Midterm-Exam-Bonus

CIDM 2315 Midterm Exam Bonus Question (20 points)


Grading Rubric:


The points of this Bonus Question will be added to your Midterm Exam Grade when calculating the final weighted grade at the end of the semester.
Students should complete this Bonus Question individually. You can get help from Google, but the instructor will not help you to do this Bonus Question.
The grader will run the whole program at first. If there are errors, the student will lose 10 points on this question. Then grader will check each C# class in detail.
The minimum point is 0 points
Submit the Github link of your work to the WTClass. Please do not submit code files. 

Rock–paper–scissors is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. 

In this exercise, you need to implement this game in C# by completing following classes:
class HumanPlayer
private int points; // the points that the human player has
public HumanPlayer(int initial){} // constructor used to set human player’s initial points
public int GetPoints(){} // return the points of human player
public void WinRound(){} // human player increase 5 points
public void LoseRound(){}// human player decrease 5 points
public string HumanDecision(){} // human player select a shape from Rock, Paper, or Scissors to compare with computer’s shape (Hint: you can use Console.ReadLine() to input a shape from keyboard).
class ComputerPlayer
public string ComputerDecision(){} // The computer player randomly picks up a shape from Rock, Paper, or Scissors. Hint:

class RockPaperScissors 
Create two player objects in the Main method of class RockPaperScissors: a human player and a computer player. 
In each round of game, the program should print the points of human player, then ask the human player to select his shape (Rock, Paper, or Scissors). The computer player randomly picks up a shape from Rock, Paper, or Scissors. (Hint: using while/for loops to repeat rounds and use break to end loop)
The human player has initial points (e.g. 5 points), if human player:
wins a round, then gets 5 points; 
if there is a tie, then gets 0 points; 
if is defeated, then lose 5 points. 
After each round, the player can select to start a new round or exit the game. 
When the points become zero, the game is over.
Sample Output: 




