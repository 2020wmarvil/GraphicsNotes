# GraphicsNotes

Proja->b = a . b / |b|

a x b = -b x a

![Projection Matrices](https://github.com/2020wmarvil/GraphicsNotes/blob/main/images/TransformationMatrices.png)
![Barycentric Coordinates](https://github.com/2020wmarvil/GraphicsNotes/blob/main/images/BarycentricCoordinates.png)


Texture Sampling:
1. Linear Filtering (pick the color of the nearest texel)
2. Bilinear Filtering (binary interpolation between four nearest texels)
3. Bicubic Filtering (similiar to bilinear, but samples in a 4x4)
4. Trilinear Filtering (bilinear filtering on the two nearest mipmap levels, then interpolate between the results)
5. Anisotropic Filtering (multiple trilinear filters to better sample the specific area we are sampling)