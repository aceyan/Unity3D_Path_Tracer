# Monte Carlo Path Tracer in Unity3D using compute shader

Unity 2018.3.7f1 (win10 64-bit)

![DemoScreenShot](Screenshot/1.png)

## Features:
1. Path Tracing Rendering based on Monte Carlo integration
2. Diffuse, specular, refraction, Fresnel
3. Hemisphere Sampling, importance sampling
4. Fuzzy glassy ball

## Principle:
### BSDF = BRDF + BTDF
![DemoScreenShot](Screenshot/2.png)   
### BRDF and importance sampling
#### Importance-Sampling Lambert
#### Importance-Sampling Phong

### BTDF and importance sampling
#### Importance-Sampling Phong for refraction 


## Reference:
   
https://www.scratchapixel.com/lessons/mathematics-physics-for-computer-graphics/monte-carlo-methods-in-practice/monte-carlo-methods
[Reflection, Refraction (Transmission) and Fresnel](https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-to-shading/reflection-refraction-fresnel)   
[Webgl中采用PBR的实时光线追踪](https://zhuanlan.zhihu.com/p/58692781)
