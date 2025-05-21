EXP-06: Implement the AI random movement.

Aim:
Implement the AI random movement.

Date:24-04-2025

Algorithm:

Step:01 Create a Character Blueprint.

Step:02 Create a Blackboard.

Step:03 Open the Behavior Tree editor.

Step:04 Create Behavior Tree nodes for the following,

 "Selector" node: Controls the execution of child nodes.

 "Service" node: Monitors and updates values in the Blackboard.

 "Sequence" node: Executes child nodes in sequential order.

 "Random" decorator: Randomly selects a child node to execute.

 "Move To" task: Moves the AI character to a specified location.

Step:05 Set up the Blackboard with vector key and bool keys and save it.

Step:06 Set up the AI character Blueprint with the help of AI controller component.

Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AICharacter
Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”

Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to cover the
desired play area.

Output:

![image](https://github.com/user-attachments/assets/9695c21d-dc11-4c4f-b468-35a6a7396dfc)
![image](https://github.com/user-attachments/assets/f9b64487-0dec-4a05-99b5-687b0b081ad8)
![image](https://github.com/user-attachments/assets/00039587-f4fc-4044-a2d8-9514f5c30674)





Result:
Thus, the AI concept to the actor for a random movement is imple
