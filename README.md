# Rotating-the-Gaming-Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step1:
Start
### Start2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Start3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Start4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

### Start5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Start6:
Create a folder name Coding and create a C# file to add the coding in it.

### Start7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Start8:
Stop

## Program:
##### Developed by:Nandhini E
##### Register no:212222100030
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class jm : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.right, Vector3.up, 70 * Time.deltaTime);
    }
}
```
## Output:
![Screenshot 2024-03-06 141145](https://github.com/Yogabharathi3/Rotating-the-Gaming-Object/assets/118899387/b26cc97d-227d-46c0-a1ee-49217be93629)

## Result:
Thus a 3D application for rotating the gaming objects in unity is developed successfully.
