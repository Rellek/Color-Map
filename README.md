# Color-Map
Example of how to implement a transparent color map to make an image interactive.
# What is it?
A color map is a transparent image that lays over top of the interactive image. The colors on the map correspond to different locations of the image, and allows us (the developer) to identify areas that can be interacted with. The color map is 100% transparent and cannot be seen by the user, however the browser can see it which allows us to return the color of the pixel clicked on.  We then use that pixel color to determine what it is the user has clicked on, and allows us to respond appropriately. 
# What does it solve?
Helps to make small or oddly shaped parts of an image interactible and easier to click on. Removes the need to use a basic image map or slices.
# What does the color map look like?
![Color Map](https://github.com/Rellek/Color-Map/blob/master/assets/graphs/full_color_map_v4.png)
# Example of the above color map in action:
![Click here](https://rellek.github.io/Color-Map/) to see the working example.
