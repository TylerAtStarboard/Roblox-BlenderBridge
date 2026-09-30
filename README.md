# Roblox-BlenderBridge

Preview or upload mesh, texture, and armatures to roblox from blender easily(no OpenCloud API key needed!)

https://github.com/user-attachments/assets/0fd9e9b8-c669-4dba-924c-cdd54c3ffda0


Blender Bridge uses websockets and live-syncs meshes, textures, and armatures from your blender scene to roblox. 
You can then upload everything in bulk if you want, which places a clone of the scene and swaps out all the contents with the new assets.


- Roblox-side links objects that have the same mesh geometry or texture etc into one object to upload and share the assetids

- Blender-side saves assetid metadata under object properties, meaning if you update a mesh you can upload in roblox again as a new version via CreateAssetVersionAsync, instead of a new asset

- Should support meshes, texture, armature, and animations


### I used AI to help with some of this(primarily the UI) 

Please report any issues or feedback!


# Install 

1. Grab the latest release from https://github.com/TylerAtStarboard/Roblox-BlenderBridge/releases
2. Extract the folder to your PC, and read the readme
