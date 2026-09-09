Edge Detection Kernels: 
These kernels (e.g., Sobel filters) highlight changes in intensity across an image.

Horizontal Sobel Filter:

[
−
2
0
2
−
2
0
2
−
2
0
2
]
⎣
⎢
⎡
​
  
−2
−2
−2
​
  
0
0
0
​
  
2
2
2
​
  
⎦
⎥
⎤
​
 
\begin{bmatrix} -2 & 0 & 2 \\ -2 & 0 & 2 \\ -2 & 0 & 2 \end{bmatrix}
Vertical Sobel Filter:

[
1
2
1
0
0
0
−
1
−
2
−
1
]
⎣
⎢
⎡
​
  
1
0
−1
​
  
2
0
−2
​
  
1
0
−1
​
  
⎦
⎥
⎤
​
 
\begin{bmatrix} 1 & 2 & 1 \\ 0 & 0 & 0 \\ -1 & -2 & -1 \end{bmatrix}
Sharpening Kernels:
These kernels emphasize the high-frequency components, making the fine details and image features more pronounced.

Sharpening helps by enhancing finer details in the image.

Example:

[
0
−
1
0
−
1
5
−
1
0
−
1
0
]
⎣
⎢
⎡
​
  
0
−1
0
​
  
−1
5
−1
​
  
0
−1
0
​
  
⎦
⎥
⎤
​
 
\begin{bmatrix} 0 & -1 & 0 \\ -1 & 5 & -1 \\ 0 & -1 & 0 \end{bmatrix}
Blurring Kernels:
Blurring kernels smooth an image by reducing noise and details, often using Gaussian filters.

This is useful when focusing on larger features while reducing noise.

Example (3×3 Gaussian filter with 
σ
=
1
σ=1sigma, equals, 1):

1
16
[
1
2
1
2
4
2
1
2
1
]
16
1
​
  
⎣
⎢
⎡
​
  
1
2
1
​
  
2
4
2
​
  
1
2
1
​
  
⎦
⎥
⎤
​
 
\frac{1}{16} \begin{bmatrix} 1 & 2 & 1 \\ 2 & 4 & 2 \\ 1 & 2 & 1 \end{bmatrix}
Embossing Kernels:
Used to create a 3D shadow effect, emphasizing edges in a specific direction.

This highlights contours and textures.

Example:

