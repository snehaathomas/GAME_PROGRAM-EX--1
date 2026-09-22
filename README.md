# GAME_PROGRAM-EX--1

# EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

## NAME: Sneha Sara Thomas
## REG NO: 212225230269

## Aim

To create and demonstrate different material properties in Unreal Engine, including emissive lighting, surface roughness, and metallic effects, using the Material Editor.

## Procedure

### 1. Create a Material

* Launch Unreal Engine.
* In the Content Browser, right-click and choose **Material**.
* Rename the material as **M_EffectsDemo**.

### 2. Set the Base Color

* Open the newly created material.
* Add a **Vector Parameter** or **Constant3Vector** node.
* Connect this node to the **Base Color** input to define the material's main color.

### 3. Add an Emissive Effect

* Insert a **Multiply** node into the graph.
* Connect a **Constant3Vector** node to specify the glow color.
* Add a **Scalar Parameter** node to control the glow intensity.
* Connect the output of the Multiply node to the **Emissive Color** input.

### 4. Adjust Surface Roughness

* Add a **Scalar Parameter** node.
* Connect it to the **Roughness** input.
* Smaller values produce a smoother and shinier surface, while larger values create a rougher appearance.

### 5. Configure Metallic Properties

* Add another **Scalar Parameter** node.
* Connect it to the **Metallic** input.
* A value of **0** represents a non-metallic surface, whereas **1** creates a fully metallic look.

### 6. Save and Test the Material

* Save the material.
* Apply it to a mesh such as a sphere, cube, or any object in the scene to observe the material effects.

## Output

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/49a6f6b4-ef20-4eff-8880-00ef042bb878" />



## Result

The material was successfully created in Unreal Engine with the following features.A glowing emissive effect controlled through color and intensity parameters.Adjustable roughness levels to represent different surface textures.Metallic controls that simulate the reflective characteristics of metal surfaces.
