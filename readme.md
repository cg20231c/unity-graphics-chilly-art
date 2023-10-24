## Materials in Unity
In Unity, materials define the appearance of an object’s surface in terms of how it interacts with light. They are associated with objects through a material component, which is attached to the object’s mesh. Materials in Unity can be as simple or complex as needed, depending on the requirements of the project. They can define properties such as color, texture, reflectivity, and transparency.

### Get Started with Materials
1. Use Assets->Create->Material from the main menu or the Project View context menu.
2. By default, new materials are assigned the Standard Shader.
3. Once the Material has been created, you can apply it to an object and tweak all of its properties in the Inspector.
4. To apply it to an object, just drag it from the Project View to any object in the Scene or Hierarchy.

### Setting Material Properties:
- You can select which Shader you want any particular Material to use.
- The Shader you choose will dictate the available properties to change.
- The properties can be colors, sliders, textures, numbers or vectors.
- If you have applied the Material to an active object in the Scene, you will see your property changes applied to the object in real-time.

In addition to the Standard Shader, there are a number of other categories of built-in shaders for specialized purposes: FX (Lighting and glass effects), GUI and UI (User Interface), Mobile (Simplified high-performance shader for mobile devices), Nature (For trees and terrain), Particles (Particle system effects).

### Material with Texture
In 3D modeling, both normal maps and diffuse maps are types of texture maps, but they serve different purposes:

- **Diffuse Map**: This is the raw color channel of a 3D object. It defines the base color of a surface or how light is absorbed when it hits the surface1. It shows the color of the object without light effects1. Essentially, it’s a 2D image that is wrapped onto the 3D model to give it color and detail1.

- **Normal Map**: This is a technique used for faking the lighting of bumps and dents. It is used to add details without using more polygons. A normal map uses RGB information that corresponds to the X, Y, and Z coordinates of the surface normals of the object, creating the illusion of depth detail on a 3D model. This can give a low-polygon model the appearance of a higher-resolution mesh.

In summary, while a diffuse map represents color information, a normal map represents surface detail (bumps and dents)
