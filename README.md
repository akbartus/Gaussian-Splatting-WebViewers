# Gaussian-Splatting-WebViewers


https://github.com/akbartus/Gaussian-Splatting-WebViewers/assets/54757270/aa827069-32bb-473b-8982-1aa9fb656d28



### **Description / Rationale**
This is an experimental project demonstrating various implementations of Gaussian Splatting (a real-time renderer for <a href="https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/">3D Gaussian Splatting for Real-Time Radiance Field Rendering</a>) viewers for the web, which are powered by Three.js and A-Frame. First gaussian splatting viewer (Three.js version) was written based on example created by Quadr as <a href="https://github.com/quadjr/aframe-gaussian-splatting/tree/main">A-Frame component</a> (MIT Licence, Copyright (c) 2023 Kevin Kwok, Junya Kuwada). The second web viewer (Three.js and A-Frame versions) is the simplified and adapted version of Mark Kellog's <a href="https://github.com/mkkellogg/GaussianSplats3D">GaussianSplats3D Three.js example</a> (MIT License, Copyright (c) 2023 Mark Kellogg). 

All these repositories, originally, are based on Kevin Kwok's <a href="https://github.com/antimatter15/splat">WebGL implementation of Gaussian Splatting</a>(MIT License, Copyright (c) 2023 Kevin Kwok). For further details, please refer to respective repositories.   

### **Instructions**
To use a web viewer locally copy Three.js or A-Frame version of the web viewer to your local server. For using A-Frame component, copy the following code:


### **Converting .ply to .splat**
In order to convert .ply file, which is created after following 3D Gaussian Splatting for Real-Time Radiance Field Rendering tutorial, you can use the following tool, which is simplified and reduced version of  Kevin Kwok's <a href="https://github.com/antimatter15/splat">WebGL implementation of Gaussian Splatting</a> (MIT License, Copyright (c) 2023 Kevin Kwok).
Open <a href="https://splat-converter.glitch.me/">this link</a> and drag your [name].ply file on window, and wait for it to do the conversion and download the file. This resulting file, then, can be used with first web viewer.

**Please note:** Kevin Kwok's work already contains this converter.

### **Tech Stack**
The project is powered by AFrame and Three.js. Truck.splat file was taken from  Mark Kellog's repository.  

### **Demo**
To see web viewers at work, visit the following pages: 
* Web Viewer 1: <a href="https://gaussian-splatting2.glitch.me/">Three.js</a> and A-Frame.
* Web Viewer 2: <a href="https://gaussian-splatting1.glitch.me/">Three.js</a> and <a href="https://gaussiansplatting2-aframe.glitch.me/">A-Frame</a>. 
