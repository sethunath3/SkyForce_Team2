# SkyForce_Team2
A top down space shooter game developing as a part of advanced game development course.
Game design inspired by the popular sky force game.
Designed and developed by a team of 2 game engineers in training using Unity3D in 4 weeks.

# Trailer Video
[Trailer video](https://drive.google.com/file/d/1RQOzOdxf_9K8arng1NwDrHb9bq7tKjzb/view?usp=sharing "Trailer Video")

# Design Patterns:
 * MVC design pattern
   -Used MVC for implementing all the indevidual components like FighterJets(Player), Bullets, Enemies etc.
 * Highly de-coupled code through the use of interfaces at different levels of abstraction(all the damageable components of the game are implementations of iDamageable interface).
 * State Machine
   - State Machine architecture is used for implementating the scene management of the game.
 * Object pooling - Creation of bullet instances are optimized using object pooling.

# Principles Used:
Single Responsibility Principle (SRP)

# Tools Used:
Async-await (instead of coroutines)
iTween (for enemy movements)
