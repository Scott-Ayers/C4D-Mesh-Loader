This project loads the first object from a .c4d file. Even if the user doesn't have Cinema4D installed.
NOTE: The object must be a poylgon type object.

If the mesh object has a material assigned to it. And there is a texture image assigned in it's color channel.
openGL will apply that texture to the mesh.
NOTE: The path to the texture must be a full file path like this: C:\Users\user\Desktop\myTexture.bmp
      Only .bmp files are supported in this proof of concept project
      
The project files are set up to be used in VS2013_x64.
Copy the cube.c4d & cubeTexture.bmp files to your computer(the desktop is a common place).

OpenGL requires many 3rd party libraries. This can be very painful to deal with when getting started.
The libs (freeglut, glew, & FreeImage) required for the openGL in the code are included in the project to make it easier for people new to openGL to get started. 
If you plan on doing openGL coding you should install these libs (and others) in your C: drive.
