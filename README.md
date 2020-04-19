# Level 1: Modeling

## Part 1: Creating a donut using Torus Mesh because donut is look like torus.

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