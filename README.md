# HvA_Immersive_Lab
This repository is intended for the users of the Immersive Lab at the Hogeschool van Amsterdam (HvA). 
The templates and code in this repository are free to use for Students and Staff of the HvA; this includes commercial use. Other users should stick to the Creative Commons Attribution-NonCommercial 4.0 International license.

The template has several blocks with ready to use components. Each component should have a description on what it does.

The SandBox folder contains several examples of interaction  components that can be reused in the main template.

## Projecting content into the Immersive Lab

The template to project content in to the lab can be found into the file "Immersive_room_HvA_template_NO_license.toe"

Open the file and load the content into TouchDesigner; for videos or images you can use the Movie_file_in TOP operator. Connect the output of this operator to the node on the inputs block where you want to project the content.

### Content splitter

In order to split content trough all the four walls use the the "NLsplitter_for_walls" under the Wall-splitter-Experimental block. Content should be in 16:9 ratio

Connect the content as input on the right of the component and link the outputs to the corresponding walls. 
You can see the name of the wall by hoevering on each output.

Use the custom parameters to fine tune the mapping

## Zig Sim App

Zig sim app is a third party app  that can be used to use the sensors of a smartphone as data input to modify content.

The pro version, aka payed version, allows to use Face an body recognition using ArKit; it also provides functionality to use the depth camera of the smart phone.

The app requires to stablish communication using OSC between the mobile device and the computer.

Here is documentation of the app https://1-10.github.io/zigsim/getting-started.html

Here are tutorial on the basic set up using touch designer: 

https://youtu.be/pwwuZj8KK6M?si=1FDtNI06D6hz5EgV

https://youtu.be/dfKfVJfy7SI?si=m3RAjZf14sFxH8wb