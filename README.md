# Ex.No:3  Change the person character
#### Name: Nithishkumar P
#### Register number: 212221230070

## Aim:
To Create a player movement using pawn, collectible, player health, and score.
## Algorithm:
##  To Create and Destroy the coin:
### Step 1:
Create a new project in Unreal Engine and choose a template that suits your needs.
### Step 2:
Add a new actor to the level and call it "Coin".
### Step 3:
Create a new blueprint based on the Coin actor by selecting it in the Content Browser
and choosing "Create Blueprint".
### Step 4:
Open the Coin blueprint and add a static mesh component to represent the coin. You
can import a 3D model or use one of the default shapes provided by Unreal Engine. 
### Step 5: 
Add a collision component to the Coin blueprint so that the player can interact with it. Choose a
simple collision shape like a sphere or a box.
### Step 6:
Add a variable to the Coin blueprint to keep track of whether the coin has been
collected or not. Call it "IsCollected" and set its default value to false.
### Step 7:
Create a new blueprint based on the player character by selecting it in the Content
Browser and choosing "Create Blueprint".
### Step 8:
Open the player blueprint and add a collision component to represent the player's
interaction with the coins.
### Step 9:
Add an event to the player blueprint that gets triggered when the player collides with a coin. Use a collision event and check if the collided actor is a coin.
### Step 10:
If the collided actor is a coin, check if it has already been collected. If not, set its IsCollected variable to true and add its value to a score variable in the player blueprint.
### Step 11:
Remove the coin from the level by calling its Destroy function.
### Step 12:
Add several instances of the Coin actor to the level and adjust their positions so that they are spread out and not too close to each other.

### Output:
![image](https://github.com/NITHISHKUMAR-P/Exp-2-GameProgramming/assets/93427017/c34f9a2e-2a4f-41fb-9757-49f445cc532c)
![image](https://github.com/NITHISHKUMAR-P/Exp-2-GameProgramming/assets/93427017/93a66dd0-19a3-422a-9811-4f5c187fdc82)

##  Redirect to levels:
### Step 1:
Create a new level or open an existing one.
### Step 2:
Add a new widget blueprint by going to the Content Browser and
right-clicking in the desired folder. Select User Interface and then Widget
Blueprint.
### Step 3:
Design your menu by adding buttons and other UI elements to the
widget. You can use images, text, and other widgets to create a visually
appealing menu.
### Step 4:
Add a button to your menu by dragging and dropping a Button
widget from the Palette onto your canvas.
### Step 5: 
In the Button's properties, scroll down to the On Click section and
click the + button next to the On Click event.
### Step 6:
Create a new custom event by clicking the New Binding button and selecting Custom Event.
### Step 7:
Name the custom event "LoadScene" or something similar.
### Step 8:
Open the Level Blueprint by going to the Blueprint menu and
selecting Open Level Blueprint.
### Step 9:
Drag and drop your menu widget from the Content Browser into the Level Blueprint.
### Step 10:
Create a new variable in the Level Blueprint by clicking the Add Variable button in the My Blueprint panel. Name the variable"MenuWidget" or something similar and set its type to the widgetblueprint you created earlier.
### Step 11:
In the Level Blueprint, drag from the MenuWidget variable and
select Set to set the variable's value to the instance of the menu widget
you added to the level.
### Step 12:
Create a new function in the Level Blueprint by clicking the Add
Function button in the My Blueprint panel. Name the function
"LoadScene" or something similar.
### Step 13:
Drag from the MenuWidget variable and select Get to get the
instance of the menu widget.
### Step 14:
Drag from the Get node and select Remove From Parent to
remove the menu widget from the screen.
### Step 15:
Drag from the LoadScene custom event and select Open Level to
open the desired level or scene.
### Step-16: 
Connect the nodes in the LoadScene function as follows:
 LoadScene -> Remove From Parent -> Open Level.
### Step 17:
Go back to your menu widget and select the button you added Earlier.
### Step 18:
In the Button's properties, scroll down to the On Click section and
select the LoadScene custom event you created earlier.
### Step 19:
Save your changes and playtest your game. When the player
clicks on the button in the menu, the menu widget will be removed and
the desired level or scene will be loaded.
### Output:
![image](https://github.com/NITHISHKUMAR-P/Exp-2-GameProgramming/assets/93427017/b9e7041e-2eb5-406d-931e-93ab9e70c388)
![image](https://github.com/NITHISHKUMAR-P/Exp-2-GameProgramming/assets/93427017/f1b06310-bd90-4c9b-9ec7-ac5418d0d5ee)


## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by Unreal Engine.
