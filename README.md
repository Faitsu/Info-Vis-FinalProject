# Info-Vis-FinalProject

This is my repository that holds my code for my Final Project in CS-GY 6006, Information Visualization.

## Important Plug-ins and Requirements

1. **VR Works Audio (Unreal Engine Plugin 4.15)** (You will need to follow the instructions [here](https://developer.nvidia.com/vrworks/vrworks-audio).

Make sure to click on the **Unreal Engine Plugin version**, and to then follow the Read Me instructions after cloning the aformentioned github. You will want to open the BlackBoxAudioRoom through the Unreal Engine Window that pops up when you complete the VR Works Audio Build. If you downloaded the plugin correctly, you should see options to change VRAudio settings on Static Mesh Actors/Materials (See the screen shot named "VR Works Audio Plugin Success Example")
3. **Unreal Engine v4.15.1**
###If Windows
1. **Visual Studios (2015 edition)** 
###If Mac:
1. The Latest Version of Xcode

##Goal

The primary goal of the project so far is to collect audio data from my Unreal Engine Test Room that was augmented by the VR Works Audio Toolkit and display this data in the time domain and frequency domain. 

This data will eventually be analyzed to try and to find the relationship of audio to parameters such as materials and room geometry through differentiation. 

##Further Work (In terms of Unreal Engine Room)

1.Figure out why changing the material type does not change the output audio (Rooms 1 & 3 give almost the same audio output despite the material change)
2. Figure out how to set up a microphone in Unreal Engine 4.15 that can record audio output
3. Figure out the double sound bug (as seen with the air audio source)
