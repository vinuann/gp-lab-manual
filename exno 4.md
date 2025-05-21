EXP-04: Attach Rifle with character mesh and bullet spawn from Rifle.

.Aim:
To Attach Rifle with character mesh and implementation bullet spawn from Rifle

Date:09-04-2025

Algorithm:
1: Import the character mesh and rifle model into your game engine or development
environment. Ensure that both assets are properly rigged and prepared for animation.

2: Create an attachment point on the character's hand or shoulder where the rifle will be
attached. This can be achieved by adding a socket or bone to the character's skeleton.

3: Attach the rifle model to the character's attachment point using the appropriate parenting or
socketing mechanism provided by your game engine. This will ensure that the rifle follows the
character's movements and animations correctly.

4: Implement the logic for bullet spawning. You'll need to determine the position and
direction from which the bullets should be spawned based on the rifle's barrel. Usually, this
involves creating a spawn point on the rifle model, such as the barrel tip.

5: When the player triggers the shooting action (e.g., pressing a button or clicking the
mouse), instantiate a bullet object at the spawn point you determined in the previous step. The
bullet object should have its own movement and collision logic.

6: Set the initial velocity and direction of the bullet based on the rifle's orientation and any
additional factors you want to consider, such as recoil or spread.

7: Continue updating the bullet's position and check for collisions or other interactions until it
reaches its target or goes out of bounds. Handle any necessary effects or damage
calculations upon collision.

8: Repeat the bullet spawning process as needed whenever the player triggers the shooting
action.

To implement the score widget:

1 : Create a score variable: Declare a variable to keep track of the player's score. For
example, you can initialize it to zero at the beginning of the game.

2: Detect bullet-object collision: Implement a collision detection system to detect when a
bullet collides with an object. This can vary depending on the game engine or framework
you are using. Typically, you would check for collisions between the bullet and the object
using

3: Handle collision events: When a collision between a bullet and an object is detected,
trigger a collision event or callback function. This function will be responsible for handling
the specific actions associated with the collision.

4: Increase the score: Inside the collision event function, increment the score variable by a
certain amount. For example, you can add one point to the score every time a bullet hits an
object.

5: Update the score widget: After increasing the score, update the score widget to display the
updated score value. This can be done by accessing the score widget element or object and
setting its text or value to the updated score variable.

6: Display the score widget: Ensure that the score widget is visible to the player during
gameplay. This might involve placing it in a prominent position on the screen or integrating it
into the game's user interface (UI) system.

7: Repeat the process: Repeat steps 2 to 6 for each object that the player can interact with
or shoot at. Whenever a bullet collides with an object, increase the score and update the score
widget accordingly.

8: Optional: Add visual and audio feedback: To enhance the player's experience, you can
consider adding visual and audio feedback when a bullet hits an object. For example, you might
display a particle effect or play a sound effect to signify a successful hit.

Output:

GUN ATTACHED TO PLAYER:

![image](https://github.com/user-attachments/assets/6b0e0c51-a85e-4bde-9585-8394f566165e)

GUN ACTOR SPAWN:

![image](https://github.com/user-attachments/assets/92fca197-22c2-47bc-9259-a50bc768f875)

STATE GRAPH:

![image](https://github.com/user-attachments/assets/c68b3614-ab5c-4fbb-92f5-365b14a77f20)
![image](https://github.com/user-attachments/assets/a60fcf2c-a3e1-45e3-ae04-9189399689a0)







Result:
To Attach Rifle with character mesh and implementation bullet spawn from Rifle is
implemen
