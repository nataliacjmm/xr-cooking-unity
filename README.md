# XR Cooking Simulator (Unity)

An interactive **Extended Reality (XR / VR)** cooking simulator built in **Unity** using **Universal Render Pipeline (URP)**, **Oculus / Meta Interaction SDK**, and **XR Interaction Toolkit (XRI)**.

## Key Features
- **VR Physics & Interaction:** Integrates Meta/Oculus Interaction SDK (`InteractionSDK`, `Oculus`) and `XRI` for natural grabbing, releasing, and physical manipulation of kitchen utensils and ingredients (`FoodMaterial.physicMaterial`).
- **3D Environment & Custom Shaders:** Full 3D kitchen scene (`Package04_Free_Kitchen`, `Comida`) with custom Shader Graph effects (`Ketchup_Decal_Graph.shadergraph`) and particle systems (`msVFX_Free Smoke Effects Pack`).

## Project Structure
- `Assets/`: Scenes (`Scenes/`), C# scripts (`Scripts/`), prefabs, materials, shaders, and XR assets.
- `Packages/`: Unity package dependencies (`manifest.json`).
- `ProjectSettings/`: Unity project configuration.