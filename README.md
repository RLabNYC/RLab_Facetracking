![Image of rlab](https://i.ibb.co/3zsstG6/Group-3.png)

# Welcome to Facetracking with the RLab!

Hello, this is a page that collects all of our repos for facetracking in one location. Now with ARKit and an iPhone with a front-facing True Depth camera, you can track your facial features allowing you animate digital avatars. The avatars first have to be prepared with point-level animation called blendshapes.  ARKit uses 52 of these to animate the avatar faces.  3D modelling is a craft that takes a long time to master and setting up all of these blendshapes can be daunting, so we’ve developed a workflow to ease the barrier to get your character up and running in a matter of minutes by leveraging three free avatar creation tools: Reallusion, Adobe Fuse and MakeHuman. All three programs have more than enough blendshapes to animate a face, they just need to be renamed to the ARKit conventions. We’ve developed a simple script to automate of lot of this process.

## Authors

Todd Bryant, Kat Sullivan, Grant Ng and Jiuxin Zhu

## From the RLab!
Greetings from the RLab! To learn more about us and what we do visit our website [here](https://www.rlab.nyc/)

# Table of Contents
1. Exporting Blendshapes from character creator software and importing into Maya
   - Opening up Character Creator 3 (CC3)
   - Starting with a base model
   - Export as a fbx
   - Import into Maya
   - Fixing blendshapes
2. Python Scripting
   - Knowledge and Filestructuring
   - Renaming the blendshapes
3. Importing in Unreal
   - Importing the FBX
   - Setting up blueprints in Unreal
