This project displays the first object in a .c4d file using openGL. Even if the user doesn't have Cinema4D installed.<br />
NOTE: The object must be a polygon type object.

If the mesh object has a material assigned to it. And there is a texture image assigned in it's color channel. OpenGL will apply that texture to the mesh.<br />
NOTE: The path to the texture in the material's "Texture" field must be a full file path like this: <br />
C:\Users\user\Desktop\myTexture.bmp.<br />
**Only .bmp files are supported in this proof of concept project.
      
The project files are set up to be used in VS2013_x64.<br />
Copy the cube.c4d & cubeTexture.bmp files to your computer(the desktop is a common place).

OpenGL requires many 3rd party libraries. This can be very painful to deal with when getting started.
The libs (freeglut, glew, & FreeImage) required for the openGL in the code are included in the project to make it easier for people new to openGL to get started.<br />
If you plan on doing openGL coding you should install these libs (and others) in your C: drive.

-ScottAyers(ScottA)
