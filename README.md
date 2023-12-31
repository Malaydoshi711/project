Problem Statement:
You are tasked with developing a simple casino game in C++. The game called “Number Guessing Game” should allow players to guess a random number between 1 and 10 and place bets using an initial balance in rupees. 

Explanation:
This is a menu-driven code that allows the user to enter their name and amount they want to bet with including their initial amount for the betting , this program contains the following details:
1.Name
2.Initial Balance you want in Casino game
3.Betting number
4.Won or Lost in game
5.Final Balance

Code used for making this game is written with help of Inheritance and polymorphism:
 Polymorphism and Inheritance:
   - Implemented the game using object-oriented programming, making use of base and derived classes.
   - Create a base class, "CasinoGame," which defines a common interface for casino games. This class should have a pure virtual function "play" to be implemented by derived classes.
   - Create a derived class, "NumberGuessingGame," that implements the specific rules and gameplay for the number guessing game. This class should override the "play" function.

Class Diagram link as follows:
https://github.com/Malaydoshi711/project/blob/main/class_diagram.jpg
