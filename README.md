This small project displays the first object in a .c4d file using openGL. Even if the user doesn't have Cinema4D installed.<br />
NOTE: The object must be a polygon type object.<br />
The code is very short, and has no bells & whistles. But it's a great jumping off point to learn how to display Cinema 4D objects in openGL, directly from a .c4d file. And not needing to export to .obj or .fbx files.

If the mesh object has a material assigned to it. And there is a .bmp texture image assigned in it's color channel. OpenGL will apply that texture to the mesh.<br />
NOTE: The path to the texture in the material's "Texture" field must be a full file path like this: <br />
C:\Users\user\Desktop\myTexture.bmp.<br />
**Only .bmp files are supported in this little proof of concept project.
      
The project files are set up to be used in VS2013_x64.<br />
Copy the cube.c4d & cubeTexture.bmp files to your computer(the desktop is a common place).<br />
Make sure you have the Melange sdk on your computer.<br />
Open the project in VS and change the file path in the code to point at the cube.c4d file on your computer. Change the linker options to Melange if needed. Then compile and run it.

OpenGL requires many 3rd party libraries. This can be very painful to deal with when getting started.
The libs (freeglut, glew, & FreeImage) required for the openGL in the code are included in the project to make it easier for people new to openGL to get started. And the project's linker properties are set up to use them.<br />
If you plan on doing openGL coding you should install these libs (and others) in your C: drive and link to them instead.

-ScottAyers(ScottA)
