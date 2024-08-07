# rufrender

A minimalistic game engine, built with OpenGL and GLFW.

# Progress

### 07/12/2024 22:33:17

First commit, created an object structure; representing a drawn element. (objects have attributes such as: position, scale and color)
they also have buffers. Create an object manager, stores objects in an array and each get rendered.

Current features are very barebones and will be improved later on.

![image](https://github.com/user-attachments/assets/e8ce73ea-490c-4ac1-8aba-d24e818e2204)

### 07/15/2024 5:08 PM

Created a State and Camera structure for 3D rendering, added Color4 values which support alpha, added CGLM for help with 3D rendering, added `pre.h` file for pre defined objects such as `createCube` .

![image](https://github.com/user-attachments/assets/2959890d-c8e8-4b16-b170-415a0e54f3c4)

### 07/15/2024 11:04 PM

Added Nuklear.h for OpenGL and GLFW. Added textures, which made me see the error in cube vertices, added debug menu, for now it shows camera properties.

#### Todo:
* Fix cube rendering.
* Fix texture wrapping.
* Add compatability for more complex shapes, getting them ready for rendering.
* Add a .fbx object importer.
* Generate a tree of eahc object with their properties in the debug menu.

#### Notices:
* ~~Typo in window title.~~

![image](https://github.com/user-attachments/assets/6f21d959-b4e4-4132-86d3-760f1f1dfa89)

### 07/16/2024 1:19 PM

Added more debug controls; specifically for the objects in the object manager, displaying their properties and attributes, change their position, rotation and scale etc.

#### TODO:
* Fix cube rendering.
* Fix texture wrapping.
* Add compatability for more complex shapes, getting them ready for rendering.
* Add a .fbx object importer.
* ~~Generate a tree of each object with their properties in the debug menu.~~

#### DONE:
- [x] Generate a tree of each object with their properties in the debug menu.

![image](https://github.com/user-attachments/assets/2c4c52b1-fd10-4f1e-9bd9-954155d69503)

### 07/16/2024 3:38 PM

Fixed the object rendering (Forgot to add GL_DEPTH_TEST)

#### TODO:
* ~~Fix cube rendering.~~
* Fix texture wrapping.
* Add compatability for more complex shapes, getting them ready for rendering.
* Add a .fbx object importer.
* ~~Generate a tree of each object with their properties in the debug menu.~~

#### DONE:
- [x] Generate a tree of each object with their properties in the debug menu.
- [x] Fix cube rendering.

 ![image](https://github.com/user-attachments/assets/70f48358-595d-44cf-a124-c075817df9f8)


