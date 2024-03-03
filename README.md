# IAAC_2024
<<<<<<< HEAD
## files for IAAC Collapse!
=======
## Files for IAAC workshops
>>>>>>> 0aa67ee (update finals)

### Presentation
- [Download Presentation PDF](./presentation/2024_IAAC_COLLAPSE!.pdf)

### References
- [Reference 1](./references/23_24_MAA01_COLLAPSE!_Seminar_Full_Syllabus.pdf)
- [Reference 2](./references/A_Bestiary_of_the_Anthropocene_EXCERPT.pdf)
- [Reference 3](./references/Benjamin_Labatut_When_we_cease_to_understand_the_world_Prussian_Blue.pdf)
- [Reference 4](./references/Morton_Timothy-Ecology-After-Capitalism.pdf)
- [Reference 5](./references/Young+&+Ayata_The+Estranged+Object_X.pdf)




<details>
  <summary>Session 1: Blender Basics</summary>
  
  ## Shortcuts
  - **Select:** Right or left click
  - **Select all:** A
  - **Multiple objects can be selected with holding Shift**
  - **Move selection:** G
  - **Scale selection:** S
  - **Rotate selection:** R
  - **Move, scale, rotate along axis:** e.g., G X 90, R Y 10, S Z 2
  - **Use middle mouse button to control the axis during transformations**

  ## Edit Mode
  - **Enter edit mode:** Tab
  - **Switch selection mode:** 1 (vertices), 2 (edges), 3 (primitives)
  - **Enable proportional editing for manipulating geometry with a falloff radius**

  ## Adding Elements
  - **Add geometry, lights, cameras, etc.:** Shift + A

  ## Move Selection to Center
  1. **Shift + S -> Cursor to World Origin**
  2. **Shift + S -> Selection to Cursor**

  ## Render Engines
  Blender natively supports two rendering engines: Cycles and EEVEE.
  - **Cycles:** Pathtracer for photorealistic images, slower but with great camera options.
  - **EEVEE:** Game engine for fast results.
</details>

<details>
  <summary>Session 2: Kitbashing and Texture Baking</summary>
  
  The recording can be found: [Session 02 Recording](https://www.youtube.com/watch?v=E3SfIc2mfdo)

  ## Kitbashing
  - Copy a few kitbash pieces found under `./session_2/kitbash_x.blend` and paste them into an empty Blender file. The easiest way is to open two Blender instances and use "Ctrl+C" and "Ctrl+V" to paste into a new scene.
  - Select all objects and place them into the center of the scene with "Shift+S" -> Selection to Cursor.
  - Make a composition with the geometry.
  - Join the objects into one. Select all objects and press "Ctrl+J".

  ## Texture Painting
  - Unwrap the object by going into edit mode ("Tab") and then "U" -> "Smart UV Project".
  - Select the model and delete all corresponding materials. Do this by deleting the materials under "Material Properties".
  - Select the object and make a new diffuse material in the material editor, and add an image texture (with alpha set to 0).
  - Go into "Texture Paint" mode and see if you can paint with a color on the model.
  - When this works, open up a texture (`session_2/graffiti_textures/..`) under texture properties.
  - Under "Active Tool and Workspace Settings," change the tiling method to "Stencil". Now, a texture overlay should appear in the Blender viewport.
  - Using "Ctrl+Right Click," "Right Click," "Shift+Right Click," you can control the texture scale, location, and rotation.

  ## Texture Baking
  - If you are happy with your texture paint, we can now bake this texture. Baking a texture means that all light information is embedded into a texture. This means that the engine does not need to calculate the lights in real-time, which speeds up frames. This is as much a positive as it is a negative in some scenarios.
  - To bake a texture:
    - Select your model, open the material editor.
    - Add a new image texture, set the name and resolution.
    - Make sure to select the texture.
    - Under render properties, make sure you have set a low render sample size and press bake.
  - Export both your baked texture and your 3D model.
  - Now you can load them into the project folder in Unreal Engine.
</details>

<details>
  <summary>Presentation</summary>
  
  ### Presentation Files
  - [Download Presentation PDF](./presentation/2024_IAAC_COLLAPSE!.pdf)
</details>

<details>
  <summary>Finals</summary>
  
  ### PDFs
  - [Echoes of Tomorrow](echoes_of_tomorrow_presentation.pdf)
  - [Frozen Mirage](FROZEN_MIRAGE_Presentation.pdf)
  - [La Bolla](La_Bolla_presentation.pdf)
  - [Nusantara Forever](Nusantara_Forever_presentation.pdf)
  - [Quantum Uncanny](echoes_of_tomorrow_presentation.pdf)

  ### Videos
  - [Echoes of Tomorrow Video](https://www.youtube.com/watch?v=enLK4b4DlBM)
  - [Frozen Mirage Video](https://www.youtube.com/watch?v=dqVMF4jefiM)
  - [La Bolla Video](https://www.youtube.com/watch?v=mHTtsJVZex8)
  - [Nusantara Forever Video](https://www.youtube.com/watch?v=xClTBWFXPEc)
  - Quantum Uncanny Video link not available
</details>
