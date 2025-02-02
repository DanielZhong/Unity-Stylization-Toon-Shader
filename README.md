# Unity URP Sketching Toon Shader

* Ruijun(Daniel) Zhong
## Demo:
![](Demo1.png)
![](Demo2.gif)
|<img src="Reference_Image.png" width="100%">|<img src="MAYA_Demo.png" width="100%">|<img src="Labubu.png" width="100%">|
|:-:|:-:|:-:|
|Reference Image|Created Maya FBX|Toon Shading|

## Inspiration
![](Inspire.jpg)  
Author: Peter Rush   
[Link](https://urbansketchers.org/2017/02/07/sketching-with-colour-pencils/)  
This project inspired from 2D sketch art. I have emulated a hand-drawn, sketch-like aesthetic within my 3D stylized interactive scene to capture the essence of paper-feel artistry.

## Implementation
### 1. Creating basic toon shader color & multiple lights support
![](MultipleLights.png)  
* Creating sketching textures:
![](Texture.jpg)
### 2. Vertex animation
![](Demo3.gif)
### 3. Post Process & Outlines
Outline:
* Sobel Method: The Sobel method is a fundamental edge detection technique in image processing that functions analogously to a high-pass filter, emphasizing areas of rapid intensity change in an image to highlight edges. This method employs convolution, a mathematical operation where a kernel (or filter) is systematically applied to an image to modify pixel values, calculating gradients that signify edge boundaries. In 3D graphics, the Sobel operator often utilizes depth buffers, which provide information about the distance of surfaces from the viewer, allowing for the detection of edges based on depth discontinuities in the scene. By convolving with depth data, the Sobel method effectively enhances the visibility of edges, making it a powerful tool for outlining shapes and features in both 2D and 3D visual contexts, thereby aiding in the interpretation and analysis of images and graphics.

Full-screen post-processing:
* Applied a texture reminiscent of paper to give my image the appearance of being drawn on it.

### 4. Real-time render with interactivity
* Press space to change materials

## Credits:
* [Sketching Textures](https://www.youtube.com/watch?v=FpvJAG6R99k)
* [Applying Texture on toon shader](https://www.youtube.com/watch?v=U51yrbgBmAo)
* [Outlines](https://www.youtube.com/watch?v=LMqio9NsqmM)
* [Paper Textures](https://www.creativefabrica.com/product/crumpled-paper-texture-background-3/)
