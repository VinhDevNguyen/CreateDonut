# Level 1: Make 

### 1. First we have to make a torus with this properties
#### Torus properties:
* Major Segments = 26 and Minor Segments = 14 (Don't make too large segments because it will help us modeling more easier)
* Major radius: 0.05m (Radius of donut)
* Minor radius: 0.023 (Radius of height donut, maybe the fat of donut)

### 2. Modeling donut
* In real world we can't create a donut that have exactly torus shape so that we have make the donut look like real (Quote: Imperfection is the virtual perfection)
* Using Edit Mode and Proportional Editing to make the donut look lumpy

### 3. Make the donut look smooth
* Right click on the donut and select Shade Smooth
* In the Modifier Properties and add Subdivision Surface

### 4. Make donut icing
* Go to Edit Mode, turn on Toggle X-Ray and select 1/3 height of the donut and duplicate it, after that hit P button and sellect Sellection to make it's own object
* Go to Modifier Properties and add Solidify to give thickness to the donut icing
#### Solidify Properties:
* Offset: Max 1.00 (This will make the donut icing facing outwards)
* Thickness: 0.0025 m

__Note:__ To avoid the hard edge, we have to move the Solidify to the first. That's mean it will make the icing thick and then make it will smooth the donut icing for us.

### 5. Make donut icing dribbles down
* Go to Edit Mode of Icing, press A to sellect all, after that right click on the mesh and choose Subdivide
#### Subdivide Properties:
* Number of cuts: 1 (Double the amout of detail)
* Smoothness: 1 (Smooth face)

After that we hold Alt and click the edge to choose the whole edge, use Ctrl+I to Inverse, use Ctrl + H to hide.

Then we snap dot to the face and make the donut icing dribbles down.
### 6. Sculpting the donut
### 7. Set up light, and camera
### 8. Change material
### 9. Add color for donut and icing
### 10. Add denoise

# Level 2: Learn how to use Particles, UV unwrapping, texture painting,...
### 1. Use Particles to add sprinkles on top of the donut
### 2. Texture paint
### 3. Create bump to make donut more realistic

# Level 3: Make a cup of coffee
### 1. Model a cup using real image
### 2. Model the plate