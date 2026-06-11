Project 1: UNO Master: Strategic Card Battle

Description: 
UNO is a classic multiplayer card game where players try to get rid of all their cards by matching colors or numbers. Special action cards (Skip, Reverse, Draw Two, Wild, Wild Draw Four) add strategy. The Java project implements a console or GUI-based version supporting 2–4 players (human + AI/computer players), card dealing, turn management, rule enforcement, and win condition detection.

Tools & Technologies:
Programming Language: Java (JDK 8 or higher)
IDE: IntelliJ IDEA / Eclipse / NetBeans
Libraries: Java Collections Framework, Java Random API

Development Steps:
•	Define Card class with color, type, and value attributes
•	Build Deck class — generate 108 cards, shuffle using Collections
•	Create Player class with hand (ArrayList) and score tracker
•	Implement GameController — turn rotation, direction, special card effects
•	Add UNO call logic and penalty system (+2 draw if not called)
•	Design AI player with rule-based card selection strategy
•	Build Swing/JavaFX UI — card display, player hands, action buttons
•	Handle win detection, scoring, and multi-round sessions
•	Write JUnit tests for card matching rules and special actions
  
Architecture: 

Presentation Layer
↓
Game Controller
↓
Rule Engine
↓
Deck & Turn Management
↓
Player & Card Classes

 
Expected Outcome:
A fully functional, playable UNO game that can be run on any system with Java installed. Students gain experience in OOP principles (inheritance for special cards, polymorphism), GUI development, game state management, and algorithmic thinking (card matching, AI heuristics). The project is portfolio-worthy and extensible (online multiplayer via sockets, better AI, animations).

