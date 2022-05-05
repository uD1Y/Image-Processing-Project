# ImageProcessing
---
### Simple Cryptograpghy
#### Encryption
 - It is nothing but a simple process in which we convert our image or information into an encrypted or unreadable mode to prevent it from unauthorized access and keep it private and secure.

#### Decryption 
 - It is nothing but a process of converting our encrypted image or information into a viewable form.

### Chaos Maps
#### Arnold Cat Map
 - Arnold's Cat Map is a chaotic map often used for pixel manipulation. It randomizes the pixel positions in an image by stretching and folding the image. When an optimal number of iterations of the transformation is applied on the image, the resulting image becomes incomprehensible and hence encrypted.

- For this implementation the transform applied on the image is:
      
      R( [x,y] ) = [ (x + y) mod n, (x + 2y) mod n ] 
- Here n is the dimensions of the image. When the transformation is repeated enough times, the original image will reappear.

#### Henon Map
- The Hénon map, is a discrete-time dynamical system. It is one of the most studied examples of dynamical systems that exhibit chaotic behavior. The Hénon map takes a point (xn, yn) in the plane and maps it to a new point.
- Given initial conditions (x0,y0), a henon map is given by the following equations:
  
      (Xn+1) = (Yn) + 1 − a.(Xn)
      (Yn+1) = b * (Xn)
- The map depends on two parameters, a and b, which for the classical Hénon map have values of a = 1.4 and b = 0.3. For the classical values the Hénon map is chaotic. For other values of a and b the map may be chaotic, intermittent, or converge to a periodic orbit.

---
#### Base Reference Paper
 - A Survey on Image Encryption using Chaos-based Techniques |(IJACSA) International Journal of Advanced Computer Science and Applications 
                                          
       https://www.proquest.com/openview/9152c699e21701ef526aafa2470a9431/1?pq-origsite=gscholar&cbl=5444811
