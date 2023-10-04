# Gaussian-Splatting-WebViewers
<img alt="Screenshot" src="img/screenshot.jpg" width="600">

### **Description / Rationale**
This is an experimental project demonstrating various implementations of Gaussian Splatting (a real-time renderer for <a href="https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/">3D Gaussian Splatting for Real-Time Radiance Field Rendering</a>) viewers for the web, which are powered by Three.js. In particular, first gaussian splatting viewer for Three.js was written based on example created by Quadr as <a href="https://github.com/quadjr/aframe-gaussian-splatting/tree/main">A-Frame as component</a> (MIT Licence, Copyright (c) 2023 Kevin Kwok, Junya Kuwada). The second viewer is the simplified and adapted minimal version of Mark Kellog's <a href="https://github.com/mkkellogg/GaussianSplats3D">GaussianSplats3D Three.js example</a> (MIT License, Copyright (c) 2023 Mark Kellogg). Both repositories, in turn, were based on Kevin Kwok's <a href="https://github.com/antimatter15/splat">WebGL implementation of Gaussian Splatting</a>(MIT License, Copyright (c) 2023 Kevin Kwok). For further details, please refer to respective repositories.   

### **Instructions**
To use the viewer locally copy either "gaussian_splatting_1" or "gaussian_splatting_2" folder to your local server. 

### **Tests**
While A-Frame component based example of Three.js viewer is capable of loading any .splat file, the time for loading and speed are two issues, which still need to be resolved. Although, even in this state, the viewer works well. The second viewer, which is a simplified version of Mark Kellog's work, while works really smoothly and fast, it does not support any .splat file and needs additional preparing and editing. 

### **Tech Stack**
The project is powered by AFrame and Three.js. Truck.splat file was taken from  Mark Kellog's repository.  

### **Demo**
To see the application at work: <a href="https://gaussian-splatting2.glitch.me/>">Web Viewer 1</a>, <a href="https://gaussian-splatting1.glitch.me/">Web Viewer 2</a>
