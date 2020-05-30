# 3D Rotating Cube-like shapes
Refer to class names in index.html and style.css

## Constructing the cube
.side, that is the sides of the cube will be contained within .cube and .cube will be contained within .wrap

* .wrap 
   * Define width and height of the cube
   * The perspective property is used to give a 3D-positioned element some perspective. It defines how far the object is away from the user. So, a lower value will result in a more intensive 3D effect than a higher value.
   
* .cube
   * Give width and height a value of 100% to ensure it spans the .wrap
   * transform-style: preserve-3d; ensures that child elements maintain their position in 3D space.
   * Animation
   
* .side
  * Width and height should be exactly the same as that of .conatiner as stated above
  * position: absolute; so that the sides of the cube are stacked on top of each other
  
* .front-face, .back-face, .top-face, .bottom-face, .left-face, .right-face
  * Each "face" should be given a rotation and translation to appear as a 3D shape. The translation for all sides must be the same an be equal to exactly half of the width and height of the cube. Refer to sources below to get an explanation of rotation values for each side.

## Rotate the cube 
Use @keyframes and transformation properties. Rotate along the X, Y and Z axes.

## More 3D Transforms
You can make a variety of shapes using the code base used by the cube. Then it is just a matter of changing the translation and rotation values.



## Sources:
* [3dtransforms](https://3dtransforms.desandro.com/cube)
* [CodePen](https://codepen.io/mrosati84/pen/AFcpl/?editors=0100)
* [CSS Tricks](https://css-tricks.com/creating-a-3d-cube-image-gallery/)
* [Gradient Generator](http://www.brandgradients.com/black-gradient/)

### [See Live Preview on CodePen](https://codepen.io/zak92/full/VwvoMxE)
