# OaKviz
## Aim 

OaK.viz is a visualization program that allows users to create an environment of their liking with the help of a minimalistic user-interface, thereby providing them with the freedom to explore their creativity to the maximum.

## Libraries Used
Integrating all the libraries below was a nightmare at times, we had to cut out many different libraries during the process but found the right set which would enhance functionality without creating overarching complexity.  

-	Freeglut (For window related activities)
-	GLEW (For querying and loading OpenGL extensions efficiently)
-	ImGui (For all the UI related aspects of the program) *
-	ImGui FileBrowser (For additional File Browsing capabilities)
-	GLM (OpenGL Mathematics Library used extensively to create our own Matrices and perform certain Computations in a more efficient manner)
-	OBJLoader (The Library helps with the reading of the OBJ Files and storing their information neatly within different classes)
-	Stb (The Library used for reading .png and .jpg files to be used within Texture Mapping)

## Disclaimer
Even though we imported a selection of different libraries; the ImGui, ImGui FileBrowser, and OBJLoader Libraries have all been modified extensively by us to include a lot more information. Example: ImGui was overriding the glut Keyboard and Mouse callback functions due to which we had to implement all the functionality such as Camera Movement within their Library. Another Example would be the amount of refactoring performed on the OBJLoader which was not very great originally due to the amount of information which was not being stored and the use of many incompatible and inconvenient data types.

## Features
Since there are too many features to list within this Description, please click the link embeded below in order to Read an entire Comprehensive Feature List.
<object data="https://drive.google.com/file/d/1RPdeW5u4nOG43abFQLYavhoiRw0w5yLk/view?usp=sharing" type="application/pdf" width="700px" height="700px">
    <embed src="https://drive.google.com/file/d/1RPdeW5u4nOG43abFQLYavhoiRw0w5yLk/view?usp=sharing">
    </embed>
</object>
