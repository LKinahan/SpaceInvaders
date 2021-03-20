# SpaceInvaders
inheritance used to implement a simplified version of the game Space Invader

Space Invaders will have a number of game elements including the player ship, the invaders and missiles fired by the ships. All objects will inherit from the same game object and share many of the same characteristics. The player ship position will be controlled by the joystick similar to the Pong game. An array of invaders is drawn at the top of the screen moving back and forth, randomly firing missiles. By pushing (and/or holding) a button on the controller, the ship can fire missiles upwards towards the invaders.  The player begins the game with 3 lives. If an enemy missile collides with the ship a life is lost (life = life – 1). If a player missile collides with an enemy both the missile and the enemy are destroyed (i.e. life = 0). If a missile reaches the edge of the screen it is destroyed. T he player score increases by 10 points for each enemy hit. If the player loses, halt the game and print YOU LOSE on the screen.The CSpaceInvaderGame class will inherit from CBase4618 for the update/draw/run methods and the canvas image. The class should contain a vector for enemies and a vector for missiles as well as the other game related member variables. In update, loop over the vector of enemies and missiles to detect collisions and determine remaining lives, then loop over again and remove any objects with lives <= 0. Finally, loop over the remaining objects to draw
