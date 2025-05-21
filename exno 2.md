# EXP-02: Create A Player Movement Using Pawn, Collectable, Player Health And Score.
## Date:
## Aim:
To Create a player movement using pawn, collectible, player health and score.

## Procedure To Create and Destroy the coin:
1. Create a New Unreal Project
Open Unreal Engine and create a Third Person or Top-Down Template project with Blueprint
or C++.
Enable necessary plugins (if any, like UMG for UI).
2. Player Movement Setup
Use the default Character class.
Movement is already implemented in Third Person template using InputAxis MoveForward and
MoveRight.
3. Add Player Health and Score Variables
Open your Player Character Blueprint or C++ class.
Add:
Health (integer, default: 3)
Score (integer, default: 0)
4. Create Collectable Actor
Create a new Actor Blueprint called BP_Collectable.
Add a StaticMeshComponent and a SphereCollision.
In the Event Graph:
blueprint
CopyEdit
OnActorBeginOverlap → Cast to Player → Add Score → DestroyActor
5. Create Enemy Actor
Create a new Actor Blueprint called BP_Enemy.
Add a mesh and a Collision Box.
On Overlap:
blueprint
CopyEdit
OnActorBeginOverlap → Cast to Player → Subtract Health
6. Create UI for Score and Health
Create a Widget Blueprint called WBP_HUD.
Add two Text Boxes: Health and Score.
In Player Blueprint:
On BeginPlay: Create and Add to Viewport.
Bind health/score variables to the UI text.
7. Update Game State
Whenever the player collects an item or hits an enemy:
Update Health or Score.
Update the HUD via Blueprint Bindings or function calls.

## Output:

![image](https://github.com/user-attachments/assets/b5fae8f6-3fc6-4c60-b0ef-07de7f3b5491)
![image](https://github.com/user-attachments/assets/4aaac6d1-4799-4977-9b59-9b3267e334ed)






## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
