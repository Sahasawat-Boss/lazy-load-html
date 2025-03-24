## Create Blurry Low-Res Images Yourself

You can use Squoosh or any image editing tool to create small, blurred versions of each image:

1.Go to https://squoosh.app/

2.Drop in img1.jpeg, reduce the width to something like 20–50px

3.Download it as img1-small.jpeg

4.Repeat for img2.jpeg → img2-small.jpeg, and so on.

5.Put them all into your /image folder alongside the original images.

##  Pure CSS + JS Blur Load (No Low-Res Image Needed)
1.We apply filter: blur(20px) and scale(1.1) to make the image appear blurry and slightly zoomed while loading.

2.When the image is fully loaded, we remove the blur and zoom using a smooth transition.

3.No small image needed – it all works using the full-size image.