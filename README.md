# Info-Vis-FinalProject

This is my repository that holds my code for my Final Project in CS-GY 6006, Information Visualization.

## Important Plug-ins and Requirements

1. **VR Works Audio (Unreal Engine Plugin 4.15)** (You will need to follow the instructions [here](https://developer.nvidia.com/vrworks/vrworks-audio).

Make sure to click on the **Unreal Engine Plugin version**, and to then follow the Read Me instructions after cloning the aformentioned github. You will want to open the BlackBoxAudioRoom through the Unreal Engine Window that pops up when you complete the VR Works Audio Build. If you downloaded the plugin correctly, you should see options to change VRAudio settings on Static Mesh Actors/Materials (See the screen shot named "VR Works Audio Plugin Success Example")
2. **Unreal Engine v4.15.1**
3. Google Drive & Google Colab

### If Windows:
1. Visual Studios (2015 edition)

### If Mac:
1. The Latest Version of Xcode

## Goal:

The primary goal of the project so far is to collect audio data from my Unreal Engine Test Room that was augmented by the VR Works Audio Toolkit and display this data in the time domain and frequency domain. For the Unreal Engine room set up, the level consists of six different audio players, where one plays the raw audio file with no VR Works Audio calculations while the other five players have VRWorks Audio calculations enabled and set up in various and different ways to try and capture different audio signals. These setups can vary by either room geometry or materials, but all six players play the same audio file and are each individually controlled by different keyboard buttons. To keep our wave form simple, a singular drum beat was used as the test audio, but any other audio file can be used in the project. 

Using a third party audio recorder that records stereo system audio, each audio player is played and recorded individually as WAV files. These WAV files are then processed and displayed on the Google Colab notebook. All six audio files are displayed as either an Amplitude vs Time signal or as a Mel Spectrogram graph. This data will eventually be analyzed to try and to find the relationship of audio to parameters such as materials and room geometry through differentiation. 

## Further Work (In terms of Unreal Engine Room)

1.Figure out why changing the material type does not change the output audio (Rooms 1 & 3 give almost the same audio output despite the material change)
2. Figure out how to set up a microphone in Unreal Engine 4.15 that can record audio output
3. Figure out the double sound bug (as seen with the air audio source)
