# Decentraland-House
Fully functionable modern house is imported to Decentraland using Decentraland SDK

1. The house setup is done in sketch up and imported as a "collada" file format to blender and then exported as "glb/gltf" format cause decentraland accepts only this format.
2. You can directly use this code to import your model to the decentraland.

How to use:
a. Make sure you first have installed decentraland globally
In cmd prompt -> npm install -g decentraland

b. Now download all the files from this folder and make yourself a folder and then direct to the folder and then open cmd prompt for that directory
In cmd prompt -> dcl init
// this will initiate the setup for you.
// make sure you have a folder named model if not create one.
// Use desired glb or gltf model of your choice and paste the file in the "model" folder
// keep in mind that decentraland specifications for your model, most of the empty land works as parcels in decentraland, what you can make best use of this SDK is that
you can make colliders for the wall and then design flexibility is upto your imagination to play with before you use real mana and buy property and other stuff.

c. Once everything is done
In cmd prompt -> dcl start
// Now this will open default browser where your model will be places in the decentraland, where you can make best use of it with random avatar
// The code is upto you to make best use of the building that you are importing.

Cheers have fun
