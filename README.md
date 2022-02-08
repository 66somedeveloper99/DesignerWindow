# DesignerWindow
A Designer window inside Scene view in Unity game engine.

# Usage
[1] add the attribute `[HasWindow]` to the class you want to have the window.

![image](https://user-images.githubusercontent.com/72737724/153036859-6f75211d-f9f7-4c07-80e2-95af6db38a1e.png)

[2] add the attribute `[OnWindow]` to the variables that you want to have in the designer window.

![image](https://user-images.githubusercontent.com/72737724/153037044-1b047ef9-4c7d-4d21-98c8-87ccfd63b3aa.png)

Done; now you'll see the variables edittable inside the Scene view, just like you see in the inspector

![image](https://user-images.githubusercontent.com/72737724/153037398-1322a67f-3133-471e-b384-bf31748735eb.png)

if you have multiple classes with `[HasWindow]` attribute for one game object, all of them will be visible on the designer window

![image](https://user-images.githubusercontent.com/72737724/153037771-0bfe886e-2024-4c8c-a9a6-d862b56c03f2.png)

# Installation
**! tested only in Unity 2020.3.25f1 (LTS)**
- download the asset package.( if you're not familiar with github, just click this link )
