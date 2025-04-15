## Lustrous Engine

This is the Lustrous Engine Repository, an application that utilizes the Vulkan API to
render images. The initial development was created using the [Vulkan Tutorial](https://github.com/Overv/VulkanTutorial) by [Overv](https://github.com/Overv).

# 
![vulkan-demo-triangle](https://github.com/user-attachments/assets/e0a07d45-83f2-4ce3-8154-e7d8ec777198)

The program creates a window, renders and presents a triangle with red, green and blue vertices. This is a very rudimentary demonstration
for the Vulkan API. The program currently initializes the API and only implements the required functions to perform the render.

The vertex data and vertex color data is temporarily stored directly in the vertex shader to simplify development during this demo.
Additionally, many features within the API are disabled. such as multisampling.

Further updates to this application includes suppoprt for: 
- Lighting
- Shadows
- Textures
- Mipmaps
- Model Loading
- And more
