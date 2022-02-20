# Power Ups

If you want to make your game interesting then add the feature of Power-ups and Collectibles. Power-ups are nothing but collecting items or points which will give the player a special ability. The ability could be anything- double jump, dash, or some attacks. 

Here, you will learn how to implement Power-Ups or Collectibles.

1. Drop a game object in the scene view.
2. Use a collider and in the collider component click ✅ the “Is Trigger” option.
3. Now, while implementing the logic, use compares tag to compare with the game object it collides with and after the collision, destroy the power-up game object.

![powerups](https://user-images.githubusercontent.com/44625252/152814423-612839ee-044f-4050-9c20-e8161c8d5e25.png)

You can add tons of features here like, after collecting the item enabling the double jump ability to the player for some seconds. This way, the player could only double jump if he gets the power up feature and that too for a limited period of time. To do this you can add a timer or use coroutines. 

![Player jump](https://media.giphy.com/media/XbV5doMFmWPOcPhJW5/giphy.gif)





