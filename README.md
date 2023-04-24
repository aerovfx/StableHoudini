# StableHoudini
Stable Diffusion Houdini Toolset

Made by Stanislav Demchenko (stassius) for EVR Systems.

https://www.linkedin.com/in/stanislav-demchenko/

https://evr.systems/

https://user-images.githubusercontent.com/35260274/234114613-43e2b2a9-f4ed-4494-a304-6b9cd92c178e.mp4


Professional set of Houdini digital assets for Stable Diffusion image processing.

### Features:
1. Automatic1111 in Houdini
2. All main A1111 features, including TI, Loras, Hypernetworks, Face restoration, tiling, hires fix
4. ControlNet 1.1, whole set of preprocessors and models
5. Animateable Image2Image alternative test
6. Upscale
7. Prompt from file, prompt animation
8. Bulk processing in i2i, mask, i2i alt test, ControlNet
9. Full PDG integration

### Installation
1. Install Automatic1111
2. Add --api command line key to the webui-user.bat
3. Run A1111
4. Install asset libraries from /hda/ and use assets inside Houdini

### Houdini Nodes included:
1. SD Switch Model (PDG) - switch to any A1111 checkpoint
2. SD Dream (PDG) - t2i, i2i, control net, all the A1111 features
3. SD Prompt (PDG) - create and animate prompts
4. SD Upscaler (PDG) - upscale an image with different neural networks
5. Image Preview (PDG) - easily switch and save generation batches
6. Image Process (PDG) - process images in COPs
7. Depth map (Obj) - instant depth-map for ControlNet generation

https://user-images.githubusercontent.com/35260274/234114730-d19e9615-332a-4c5e-89af-30ef44ca3742.mp4




