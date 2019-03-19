# Test Approach

- [Test Movement](#Test-Movement)
- [Test Jumping](#Test-Jumping)
- [Test Mouse Movement](#Test-Mouse-Movement)
- [Test Picking up Items](#Test-Picking-Up-Items)




## Test Movement

This test is for checking to see if the player model moves correctly on the
X-axis and Z-axis.

| Action |Observations|
|--------|------------|
| Double click on the Unity icon | Should open a window that has the list of projects available to open |
| Click on the project that says "Valyrian Game" | Unity should begin to load all the assets that is associated with that project |
| Under the Project tab click the folder named "Scenes" | You should see the different scenes that the project has access to |
| Double-click on the scene named "Walk Test" | In the Hierarchy tab on the top right, you should see a light, a cube, and the player model |
| Click on the player model | You should see in the inspector tab all the properties that is associated with the player model. Such things like position, rotation, scripts, etc. |
| At the top click the play button | This should begin the game and you will have control of the player model |
| Check the current position of the player model in the Inspector tab | The position will be in (x,y,z) form, so the start position of the player model should be near (0, 1.48, -12.5) |
| Press and hold W to move the player forward | When moving forward the x and z position should change and you should hear a sound as the player is moving forward. The Y position value should remain constant |
| Press and hold A to move the player to the left | When moving to the left the x and the z position will change and you should hear a sound as the player is moving to the left. The Y position value should remain constant |
| Press and hold S to move the player backwards | When moving forward the x and z position should change and you should hear a sound as the player is moving backwards. The Y position value should remain constant |
| Press and hold A to move the player to the right | When moving to the left the x and the z position will change and you should hear a sound as the player is moving to the right. The Y position value should remain constant |
| Press 'esc' key in order to make the mouse appear | You should see the cursor reappear on your screen |
| Press the play button at the top again to stop the game | Unity will then stop the game and put the player model back to the original position |


## Test Jumping

This test is for checking to see if the player model is able to jump properly. By checking if its Y position changes when he jumps.

| Action |Observations|
|--------|------------|
| Double click on the Unity icon | Should open a window that has the list of projects available to open |
| Click on the project that says "Valyrian Game" | Unity should begin to load all the assets that is associated with that project |
| Under the Project tab click the folder named "Scenes" | You should see the different scenes that the project has access to |
| Double-click on the scene named "Walk Test" | In the Hierarchy tab on the top right, you should see a light, a cube, and the player model |
| Click on the player model | You should see in the inspector tab all the properties that is associated with the player model. Such things like position, rotation, scripts, etc. |
| At the top click the play button | This should begin the game and you will have control of the player model |
| Check the current position of the player model in the Inspector tab | The position will be in (x,y,z) form, so the start position of the player model should be near (0, 1.48, -12.5) |
| Press 'space' to make the player model jump | You should see in the inspector tab that when you jump the only position that changes is the Y value |
| Begin to move forward by pressing 'W' and then jump as you are walking | You should see in the inspector tab that all the position value of the player model should change |
| Press 'esc' key in order to make the mouse appear | You should see the cursor reappear on your screen |
| Press the play button at the top again to stop the game | Unity will then stop the game and put the player model back to the original position |


## Test Mouse Movement

This test is for checking to see if the mouse movement is correct. The mouse should be only moving on the y-axis of rotation.

| Action |Observations|
|--------|------------|
| Double click on the Unity icon | Should open a window that has the list of projects available to open |
| Click on the project that says "Valyrian Game" | Unity should begin to load all the assets that is associated with that project |
| Under the Project tab click the folder named "Scenes" | You should see the different scenes that the project has access to |
| Double-click on the scene named "Walk Test" | In the Hierarchy tab on the top right, you should see a light, a cube, and the player model |
| Click on the player model | You should see in the inspector tab all the properties that is associated with the player model. Such things like position, rotation, scripts, etc. |
| At the top click the play button | This should begin the game and you will have control of the player model |
| Check the current rotation of the player model in the Inspector tab | The rotation will be in (x,y,z) form, so the start rotation of the player model should be near (0, 0, 0) |
| Begin to move your mouse in any direction | You should see the in the Inspector tab that the angle of rotation on the y-axis is constantly changing with your mouse |
| Begin to move the player model by using 'WASD' and move your mouse as well | You should still see that the y-axis of rotation is still the only value changing when changing the position of the player model |
| Press 'esc' key in order to make the mouse appear | You should see the cursor reappear on your screen |
| Press the play button at the top again to stop the game | Unity will then stop the game and put the player model back to the original position |

## Test Picking Up Items

This test is for checking to see if the player is able to pick up the ammo and shield packs. These items will be located around in the area of the level for players to pick up. It should also
update the text of the amount of ammo/shield the player carrying on the screen.

| Action |Observations|
|--------|------------|
| Double click on the Unity icon | Should open a window that has the list of projects available to open |
| Click on the project that says "Valyrian Game" | Unity should begin to load all the assets that is associated with that project |
| Under the Project tab click the folder named "Scenes" | You should see the different scenes that the project has access to |
| Double-click on the scene named "Arena" | On your screen you should see many objects in the scene and a big building in the model |
| At the top click the play button | This should begin the game and you will have control of the player model |
| At the bottom center you should see a black text with the value '0' | This shows the amount of shield that you have access to |
| At the bottom left corner you should see a black text with the value '0' | This shows the amount of ammo you have available to use |
| Begin to search for a shield or ammo pack | Shield packs is a cylindrical object and the ammo pack is a rectangular object. Both of them are floating for ease of searching |
| When you find a shield pack/ammo pack walk over it to collect it | When you walk over a shield pack you should see the shield value increase by 25; When you walk over a ammo pack you should see the amount of ammo increase by 20 |
| Press 'esc' key in order to make the mouse appear | You should see the cursor reappear on your screen |
| Press the play button at the top again to stop the game | Unity will then stop the game and put the player model back to the original position |
