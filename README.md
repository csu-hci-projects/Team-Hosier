# VR Typing Tutorial

This project aims to provide users with an interactive virtual keyboard and virtual hands while inside of the head mounted display, Oculus Quest 2. Expirimentally, the goal of this project was to test the effeciency of different keyboard layouts in a virtual environment. This project also aims to provide users with a simple and effective way to solve the problem of text entry in VR settings. Users can interact with the two different keyboards using just their hands, no controllers necessary. This virtual environment also provides an unobstructed view of the keyboard and aims to provide an effecient, utilizable, and fully functional virtual keyboard. 

# Instructions:

1. Install Unity and Unity Hub
2. Install the Oculus Developer Hub Application
3. Download the Button and Oculus OVR Integration Assets
4. Set up the unity environment by creating a simple plane for the ground and brining the OVR Player Controller into the enironment. 
5. Next, create a simple cube object for the normal keyboard, and antother 2 cube objects for the split keyboard.
6. Use the Keyboard Button prefab and drag the prefab onto both of the board objects. 
7. Attach the Keyboard Button Script to the Keyboard Button prefab. 
8. Create a typing area collider that surrounds the keyboard(s) object and attach the Typing Area Script to it. 
9. Create a typing input canvas for users to type into. 
10. Attach the Keyboard Script to the keyboard objects and drag the typing input canvas into the Input Field Game object on the Keyboard Script.
11. Attach the Left and Right hand prefabs accordingly to the Typing Area Script. 
12. Go to the player settings and change the physics so that the typing hands are interacting with the keyboard and the hands are interacting with the interactive layer. 
13. Build the project. 
14. Plug in the headset to a computer and select the built .apk file to upload to the Oculus Developer App. 
15. Lastly, put on the headset, head to apps -> unknown sources and select the game to play on the Oculus Quest and enjoy typing!

# Here are some useful links:

Link to the YouTube Presentation: https://youtu.be/4N3cVN9hKs0

Link to the project website: http://127.0.0.1:5500/Website/index.html



