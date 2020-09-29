# HarryPotter-InvisibilityCloak
### Creating an invisibility cloak using OpenCV
<br>
<img src ="https://user-images.githubusercontent.com/53532851/94545152-ce3f2b00-0269-11eb-8d8d-efd0fa0bbdf4.gif">
<br>

### WORKING
 
 (background.py)
- First a background image will be clicked which will be used for masking and saved
 
 (cloak.py)
 
- HSV upper limit and lower limit is set for the colour to be masked(eg: (0,100,100) - (10,255,255) for red)
- part-1 is for replacing red colour pixels with background image pixels
- part-2 is for rest non-red pixels to show 
