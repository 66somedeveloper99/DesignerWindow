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
- download the asset package.( if you're not familiar with github, just right-click [this](https://github.com/66somedeveloper99/DesignerWindow/blob/main/DesignerWindow.unitypackage "Click To Download Package") link and "save as")
- right click on a folder in the *Assets/* folder and click on "Import Package -> Custom Package" button
<img src="https://user-images.githubusercontent.com/72737724/153041340-c7252a67-c1b9-4b16-b4a2-891eaea97eab.png" width=400>

- locate the downloaded package and double-click it
<img src="https://user-images.githubusercontent.com/72737724/153040138-7b4a4197-e62e-4000-b3ad-23e3416248f2.png" width=400>

- click on he "import" button
<img src="https://user-images.githubusercontent.com/72737724/153041072-b8374647-91cf-4144-9d37-181a67480372.png" width=400>
