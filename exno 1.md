# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date:05-03-2025
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
Step 1: Create a New Material
In the Content Browser, right-click and select Material.
Name the material, e.g., M_CustomSurface.
Double-click to open in the Material Editor.
Step 2: Set the Material Domain
Set the Material Domain to Surface.
Set Shading Model to Default Lit.
Step 3: Add Base Color
Add a Texture Sample (e.g., Albedo texture).
Connect it to the Base Color input.
Step 4: Add Roughness
Option A: Use a Constant (e.g., value 0.5) for uniform roughness.
Option B: Use a Texture Sample for roughness map.
Connect to the Roughness input.
Step 5: Add Metallic
Option A: Use a Constant (e.g., 1.0 for full metallic).
Option B: Use a Texture Sample for a metallic map.
Connect to the Metallic input.
Step 6: Add Emissive Color
Use a Constant3Vector or Texture Sample as the base color.
Multiply it with a Scalar Parameter to control brightness.
Connect the result to the Emissive Color input.
Step 7: Compile and Apply
Click Apply and Save the material.
Assign it to a mesh in the level to test.
Step 8: Create a Material Instance (Optional)
Right-click the material, select Create Material Instance.
Adjust scalar/vector parameters in real-time through the instance.

## Output:
![image](https://github.com/user-attachments/assets/ffa20437-5662-437f-b1e7-52ce39f6f41b)
![image](https://github.com/user-attachments/assets/d7d36ad1-3ea9-4a5c-80a6-666014aeda19)
![image](https://github.com/user-attachments/assets/3ba769f7-1e3e-4845-8054-c7df7dfba8a1)




## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
