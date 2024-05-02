 let's add a camera shake effect to the game! This effect will add intensity and immersion to the gameplay, making enemy attacks feel more impactful.

Here's how we can implement the camera shake effect:

Define a Camera class to manage the camera position and shake effect.
Implement a method in the Camera class to shake the camera for a specified duration and intensity.
Apply the camera shake effect when the player is hit by an enemy bullet or when a bullet hits an enemy.
Adjust the rendering position of game entities based on the current camera position.
Here's the revised version of the C++ code with the camera shake effect added:

I added a Camera class to handle the camera position and shake effect.
The Camera class has a method shake() to trigger the camera shake effect.
The camera shake effect is applied when the player is hit by an enemy bullet.
The rendering position of game entities is adjusted based on the current camera position, creating a shaking effect.
