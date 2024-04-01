# Multiband Blending Web Application

## Specifications

![ReactJS](https://github.com/GenuinoVitto/DIGIMAPMultibandBlending/assets/78674453/0b4d4279-f07e-47b0-a12c-9f27c261484e)

This is a website built on React.js that implements Multiband Blending. 

## What is Multiband Blending?
![maxresdefault](https://github.com/GenuinoVitto/DIGIMAPMultibandBlending/assets/78674453/78ece355-621f-436e-8cf1-240712db2345)

Multiband blending, also known as multi-resolution blending or pyramid blending, is a technique used in image processing and computer graphics to seamlessly blend two or more images together. The concept involves decomposing the images into different frequency bands or levels using a pyramid decomposition technique such as Gaussian or Laplacian pyramids. Each level of the pyramid represents a different scale of detail, with lower levels containing larger-scale information and higher levels containing finer-scale information (Smith & Brady, 1997).

Once the images are decomposed into their respective frequency bands, blending is performed independently on each band. This allows for more control over the blending process, as different blending techniques or parameters can be applied to different frequency bands to achieve the desired result (Burt & Adelson, 1983). Finally, the blended frequency bands are combined back together to produce the final blended image.

Multiband blending is commonly used in applications such as image stitching, panorama creation, and seamless image compositing, where it is important to seamlessly blend different images together without visible artifacts (Brown & Lowe, 2007).

---

### References:

- Smith, S. M., & Brady, J. M. (1997). SUSAN - A New Approach to Low-Level Image Processing. International Journal of Computer Vision, 23(1), 45–78.
- Burt, P. J., & Adelson, E. H. (1983). The Laplacian Pyramid as a Compact Image Code. IEEE Transactions on Communications, 31(4), 532–540.
- Brown, M., & Lowe, D. G. (2007). Automatic Panoramic Image Stitching using Invariant Features. International Journal of Computer Vision, 74(1), 59–73.

