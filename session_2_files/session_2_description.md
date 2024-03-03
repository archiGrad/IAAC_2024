# Session 02: Kitbashing and texture baking

The recording can be found: [Session 02 Recording](https://www.youtube.com/watch?v=E3SfIc2mfdo)

## kitbashing

Copy a few kitbash pieces found under `./session_2/kitbash_x.blend` and paste them into an empty Blender file. The easiest way is to open two Blender instances and use "ctrl+c" and "ctrl+v" to paste into a new scene.

Select all objects and place them into the center of the scene with "shift+s" -> selection to cursor.

Make a composition with the geometry.

Join the objects into one. Select all objects and press "ctrl+j".

## texture painting

Unwrap the object by going into edit mode ("tab") and then "u" -> "smart uv project".

Select the model and delete all corresponding materials. Do this by deleting the materials under "material properties".

Select the object and make a new diffuse material in the material editor, and add an image texture (with alpha set to 0).

Go into "texture paint" mode and see if you can paint with a color on the model.

When this works, open up a texture (`session_2/graffiti_textures/..`) under texture properties.

Under "active tool and workspace settings," change the tiling method to "stencil". Now, a texture overlay should appear in the Blender viewport.

Using "ctrl+right click," "right click," "shift+right click," you can control the texture scale, location, and rotation.

## texture baking 

If you are happy with your texture paint, we can now bake this texture. Baking a texture means that all light information is embedded into a texture. This means that the engine does not need to calculate the lights in real-time, which speeds up frames. This is as much a positive as it is a negative in some scenarios.

To bake a texture:
- Select your model, open the material editor.
- Add a new image texture, set the name and resolution.
- Make sure to select the texture.
- Under render properties, make sure you have set a low render sample size and press bake.

Export both your baked texture and your 3D model.

Now you can load them into the project folder in Unreal Engine.

