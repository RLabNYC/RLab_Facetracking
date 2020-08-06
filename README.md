![Image of rlab](https://i.ibb.co/3zsstG6/Group-3.png)

# Welcome to Facetracking with the RLab!

Hello, this is a page that collects all of our repos for facetracking in one location. Now with ARKit and an iPhone with a front-facing True Depth camera, you can track your facial features allowing you animate digital avatars. The avatars first have to be prepared with point-level animation called blendshapes.  ARKit uses 52 of these to animate the avatar faces.  3D modelling is a craft that takes a long time to master and setting up all of these blendshapes can be daunting, so we’ve developed a workflow to ease the barrier to get your character up and running in a matter of minutes by leveraging three free avatar creation tools: Reallusion, Adobe Fuse and MakeHuman. All three programs have more than enough blendshapes to animate a face, they just need to be renamed to the ARKit conventions. We’ve developed a simple script to automate of lot of this process.

## Authors

Todd Bryant, Kat Sullivan, Grant Ng and Jiuxin Zhu

## From the RLab!
Greetings from the RLab! To learn more about us and what we do visit our website [here](https://www.rlab.nyc/)
   - These are all free softwares that are available to download.
# Table of Contents
1. Creating 3D characters
   - [Adobe Fuse](https://github.com/RLabNYC/Rlab_FaceTracking_fuse/blob/master/README.md#for-beginners)
   - Make Human
   - Reallusion Character Creator 3 (CC3) 
2. Exporting Model with blendshapes
   - [Adobe Fuse export](https://github.com/RLabNYC/Rlab_FaceTracking_fuse#exporting-the-blendshapes)
   - Make Human export
   - Reallusion export
3. Running our Scripts in Maya
   - [Importing the FBX](https://github.com/RLabNYC/Rlab_FaceTracking_fuse/blob/master/RUNSCRIPT.md#import-the-fbx-from-mixamo)
   - Python scripting (Each are different!)
     - [Fuse](https://github.com/RLabNYC/Rlab_FaceTracking_fuse/blob/master/RUNSCRIPT.md#using-python)
     - Make Human
     - Reallusion
4. Importing into Game Engine
   - Import settings for Unreal
     - [Fuse](https://github.com/RLabNYC/Rlab_FaceTracking_fuse/blob/master/IMPORTING.md#importing-into-unreal)
     - Make Human
     - Reallusion
   - Setting up blueprints in Unreal
     - [Fuse](https://github.com/RLabNYC/Rlab_FaceTracking_fuse/blob/master/IMPORTING.md#blueprints-in-unreal)
     - Make Human
     - Reallusion
   - Import settings for Unity (WIP)
   
