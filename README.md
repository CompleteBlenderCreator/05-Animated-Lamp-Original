### 1 Section 5 Introduction

+ Mikey and Ben Introduce the Animated Lamp Section.
+ Mikey gives a quick run through of what is coming up in the next section.

### 3 Your Section 5 Assets

+ This is the Lecture where you will find all of the files you will need to complete the Section.
+ Please Download your Asset Pack now.
+ Your files will come in a Zip file ready for extraction to your computer.

### 4 Being Lean

+ We are going to do many iterations though to the end, even though the lamp won't be built fully!
+ Later on rendering times are likely to be longer that the last section.
+ We'll be making and testing the Lamp as we go.

### 5 Cycles VS Blender Render

+ Blender Render is generally quick and you get a reasonable result quickly. - Uses CPU Only.
+ Cycles is a physical based renderer is accurate but takes longer. It is designed for GPUs but runs fine on CPUs.

**Why Use Cycles?**

+ We are going to use Cycles, since we are modelling a lamp!
+ The two are not cross compatible, no switching.
+ You can use other Renderers too, if you have access to them. We won't be covering these.

**Render Time Difference**

+ I will be showing you 3 Clips of a 4 second bowling ball animation.
+ Blender Render - 2 mins
+ Basic Cycles Render - 15 mins
+ Thorough Cycles Render - 4 hours!

**Your Machine Specs : CPU**

+ Lots of different machine specs- vary massively.
+ More Cores and Higher Frequency CPU.
+ You are unlikely to hit memory limits when using CPU Rendering.
+ You cannot use CPU and GPU at the same time.

**Your Machine Specs: Graphics Card**

+ nVidia cards- any that support CUDA.
+ AMD/ATi Cards - Support has started not complete.
+ You may hit memory issues if using a GPU.
+ If in doubt or having trouble switch to CPU rendering.

### 6 Dedicated Graphics Cards

+ Cycles runs with AMD/ATi and nVidia Cards.
+ Install the latest drivers for your GPU.
+ If you do not have a dedicated nVidia graphics card you can skip the next few lectures.

### 7 Installing CUDA On Windows

+ This Lecture is for Windows machines, please skip to the next lecture for a Mac Setup.
+ Show you how to check for your driver version.
+ Make sure you have the latest Version of Nvidia's Drivers for your computer.

### 8 Installing CUDA On A Mac

+ Show you how to download nVidia's CUDA drivers.
+ Check for updates - have to manually check for updates via system preferences once installed.
+ Can install updates from system preferences in future.

### 9 Setup Blender For GPU Rending

+ Optional, if you do not have a **dedicated** GPU, this lecture will not apply to you.
+ You may find that your GPU is **slower** than your CPU at rendering.
+ Your CPU is free to do other things…

### 10 Lowering Your Cycles Render Time

+ How to change your Render settings.
+ You will have to run multiple tests.
+ Different scenes will have different characteristics depending on there complexity, but in general will follow a similar pattern.

### 11 Creating A Backdrop

+ Decide on a scale.
+ Create a basic environment for our lamp.
+ Run through a couple of options.

### 12 Lighting With Cycles

+ Show that lamps sort of work in Blender.
+ How to create a light source as geometry and then apply an emissive material to that object.

### 13 Rendering A Small Area

+ Show you how to render just a part of your scene.
+ Great for those with slower machines.
+ Great for complex Scenes on ANY computer.

### 14 Using Curves To Generate Geometry

+ Using curves makes it infinitely editable.
+ Changing the bézier handle type.
+ Generate a 3D object by defining curves.

### 15 Creating Geometry From A Curve

+ Refresh our knowledge on this.
+ Converting our curve object to a mesh object.
+ We can then perform mesh operations on it.
+ We can choose to delete the original curve data if we want to.

### 16 Altering Curve Resolution

+ Culling Unnecessary Geometry
+ We kept the curve data so have two options:
+ Remake our mesh object, from those curves.
+ Fiddle about with the geometry itself.

**Which path to take?**

+ Both are OK- depends on stage of construction.
+ We'll be altering the curve resolution AND the mesh!
+ Tidy up the rest of our geometry.

### 17 Existing Geometry To Create New

+ Use an existing face to create a new face.
+ Separate immediately creating a new object.
+ This allows us to match up parts of our model, even when they're not exact sizes.

### 18 Design and Considerations

+ Design a rough outline for the lamp.
+ Make it believable as an object.
+ I have chosen a simple and raw design.
+ Remember It can always be beautified later on.

### 19 Introduction to Armatures

+ Learn about the armature object.
+ Add an Armature to your model.

### 20 Revisiting the Mirror Modifier

+ Learn how to use another object as the point of reflection.
+ Understand that it is the origin that acts as the point of reflection.
+ See other objects rotational values change the axes of reflection.

### 21 Adding Bones To Our Armature

+ Learn how to add additional bones to an armature.
+ Understand that a new bone does not have to be connected to the previous one.

### 22 Pose Mode

+ Be introduced to pose mode
+ Understand that we use this mode to test our models movement.
+ Know that this the best mode to be in to parent mesh objects to individual bones, and to make alterations.

### 23 Rest Position and Pose Position

+ Understand the differences between rest position and pose position.
+ You can see the rest position when in edit mode.
+ How to clear the pose back to the rest state.

### 24 Constraining Bones Movement

+ Be able to lock movement to a single axis.
+ Constrain the degree of movement possible.

### 25 The Solidify Modifier

+ Create a 3D object from just curves.
+ Give the new object thickness using the solidify modifier.

### 26 Introduction To The Node Editor

+ Open up the node editor.
+ Create some basic materials.
+ Apply these materials to our model.
+ See how adjustments in the node editor affect our model.

### 27 Lamps vs Emissive Materials In Cycles

+ Learn the differences between the two light sources when using the cycles engine.
+ Understand that there is time and place for both.
+ Use the blackbody node.

### 28 Auto Inverse Kinematics (IK)

+ Learn how to turn on Auto IK.
+ Realise that this is a starting point and not perfect!
+ Understand it applies to the whole rig.
+ See that it allows us to control the connected bones all at once.

### 29 The Timeline

+ Be introduced to the timeline
+ Shown how to adjust the playback and rendering range.
+ How to alter the Frames Per Second (FPS) of your animation.

### 30 Key Frames

+ Understand what they are and how they are used.
+ Be shown how to automatically add them and remove them from the Timeline view.
+ Realise almost everything can be keyframed.
+ Be able to use key frames to animate your lamp.

### 31 Setting Up The Camera

+ Understand that the camera view is for our animation rendering as well as a normal rendering.
+ Setup the camera ready for the Animation.
+ Animate the Camera!

### 32 Rendering An Animation

+ Learn how to render your animation.
+ How to stop the rendering.
+ What settings to use for good results.
+ How to preview an animation once it has finished rendering.

### 33 Rendering Across Multiple Blenders

+ Use multiple computers to render an animation.
+ Learn how to use multiple instances of Blender to utilise the CPU and GPU on your computer.
+ Decide on how many samples for the final animation.

### 34 Creating A Video of Your Animation

+ Be Introduced to the Video Editor.
+ Combine your rendered images in to a final video.
+ Explore various exporting options.
+ Export the images to a movie file.

### 35 Exporting Your Lamp Model

+ Learn how to setup the FBX Export and understand why we use it.
+ Realise that your model is currently only suitable for Blender. The Export doesn’t fully work in the model's current state.

### 36 Vertex Groups

+ Learn what a vertex group is.
+ Assign vertices to a vertex group.
+ See that because we created our model in parts, it is really easy to assign groupings.

### 37 Re-Rigging Our Model

+ Un parent your lamp meshes and join them together ending up with one mesh object.
+ Rename your Vertex Groups and Bones so that they match.
+ Test your new rig.

### 38 Exporting The Final Model

+ Export the model and test it.
+ Just watch if you don’t have Unity or Unreal installed so you can see the process.

### 99 End of Section 5 Wrap Up

Mikey talks through the end of section wrap up.
