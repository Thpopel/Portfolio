### Biomedical Image Analysis:

Welcome to my biomedical image analysis topic! This topic will focus on MRI images, and visualizing the different layers of the brain. 

To begin, we'll take a look at one brain image alone. 

**Let's read in the file we would like to look at:**

<img src="1.png" width="600"/>  

**Next, we can call on .meta to get a list of pertinent information regarding the image:**

<img src="1.png" width="600"/>

**Once we have this information, let's visualize it using plt.imshow() and use a gray colour map. Lastly, we'll turn off axis for a better view and use plt.show() to see the image we have created:**

<img src="1.png" width="600"/>

<img src="1.png" width="600"/>

Perfect! This code has done exactly what we needed it to do. How about instead of a 2D slice, we now want to look at a 3D volume of multiple slices of the brain. 
This can be done using the following code segment: 

**Read in the volume file:**

<img src="1.png" width="600"/>

**Look at a single slice within the collection. The 80th slice to be exact using the same code as above:**

<img src="1.png" width="600"/>

<img src="1.png" width="600"/>

**That worked great as well, but in order to get the big picture, we'll need to incoorporate another topic from my portfolio; For Loops. In the code below, we'll use a For Loop to itterate through mutliple slices, and add them to a subplot:**

<img src="1.png" width="600"/>

<img src="1.png" width="600"/>

The code above include a subplot counter to signify where to add the next image to in our subplot. Our 4 x 4 subplot displays 16 images from our volume collection. 1 slice for every 10 images within the collection. 
plt.tight_layout allows for our 16 image subplot to be small and to remove excess space around each image. 
