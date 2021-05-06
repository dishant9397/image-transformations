# Image Transformations
This MVC application allows the user to apply different transformation techniques on a given picture and then save the resultant image. This program runs with two possible ways mainly script mode and interactive mode and both of these modes are self explanatory.

# Features
The features of this application are as follows:
1. User is been given option to select the number of colours per channel for reducing the density and number of seeds for mosaicing or pixelating the image.
2. Also, it provides functionality for generating the pattern and saving the generated pattern which can be used to stitch that pattern on any other image and can also select a list of colors from which user wants to generate the pattern. All the patterns will be generated each correscponding a unique unicode character.
3. In interactive mode, effect applied will be instantly shown to the user and the image would be updated stat.
4. After generating pattern, user can either exchange a particular pixel with another or can remove it completely from the pattern.
5. User can also write command line arguments in area provided and can execute it.
 
# How to run the program?
Rrun **java -jar program.jar** command in CLI and will give the output of the program accordingly. There are two types of arguments that are accepted by this jar and upon which execution will depend:
1. **-script filepath:** filepath has to be a complete path which will execute the commands from the file passed. Only txt files are supported for this argument type.
2. **-interactive:** opens the UI interface for the user

# How to use the program
This program can be run in two ways:
1. **Script Mode:** This will take the file path as an argument and then depending on each input execution process will be carried. The meaning of what each commands mean in this mode is listed below and this commands are case sensitive:  
a. load: Loads the file from the next available path  
b. blur: Blurs the image  
c. sharp: Sharpens the image  
d. greyScale: GreyScales the image  
e. sepiaTone: SepiaTones the image  
f. dither: Dithers the image from the next available possible value per channel passed. 
g. mosaic: Mosaics the image from the next number of seeds per image passed  
h. pixelate: Pixelated the image to mentioned number of squares across  
i. generatePattern: generates the pattern based on the number of squares passed  
j. save: saves the current image at mentioned location with the given file name  
k. savePattern: saves the current generated pattern if any  

2. **Interactive Mode:** This option will facilitate the users by providing them a UI to interact with and this will have couple of options as follows:  
a. Load: Allows the user to load the image  
b. Save: Allows the user to save the image   
c. Script: This will allow user to execute the commands as mentioned in Script Mode  
d. Blur: Blurs the image  
e. Sharp: Sharps the image  
f. GreyScale: GreyScales the image  
g. SepiaTone: SepiaTones the image  
h. Dither: Dithers the image  
i. Mosaic: Mosaics the image  
j. Pixelate: Pixelates the image  
k. Generate Pattern: Generates the pattern on the image  
l. Save Pattern: Saves the current generated pattern  
m. Click on pixel after pattern is generated will allow user to either exchange or remove that pixel from the pattern   

# Screenshots:
1. **Loading an Image**
<img src="https://github.com/dishant9397/image-transformations/blob/master/Original%20Image.png" height="50%" width="50%"/> 

2. **Applied Effect (GreyScale)**
<img src="https://github.com/dishant9397/image-transformations/blob/master/Grey%20Scale%20Effect.png" height="50%" width="50%"/> 

3. **Pattern Generation**
<img src="https://github.com/dishant9397/image-transformations/blob/master/Pattern.png" height="50%" width="50%"/> 

4. **Script Window**
<img src="https://github.com/dishant9397/image-transformations/blob/master/Script%20Dialog.png" height="50%" width="50%"/>

# UML
Click [here](https://github.com/dishant9397/image-transformations/blob/master/UML%20Diagram.pdf) if you want to view the UML of this project.

# Code of Conduct
Code for this project is not attached because of Code of Conduct of Northeastern Univeristy. Still, if you want to view the code then please send me an email on [dishantpatel256@yahoo.in](dishantpatel256@yahoo.in) with your github username, email or full name with the reason so that I can provide you the access.
