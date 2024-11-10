# DisplayDialogue

## Overview
This asset is a customizable character dialogue and player response display. Both the text of the dialogue and response can be easily customized within a C# script. The colors of the display can be easily customized as well, giving the user a hands-on design experience!

## Features
-  **Feature 1**: Dialogue Panel- the dialogue from the character is displayed on screen, leaving plenty of room for the character image to be featured as well.
-  **Feature 2**: Response Buttons 1 & 2- the buttons display the potential responses for the player to choose, and within a script these buttons can be used to affect points or other aspects of gameplay.
-  **Feature 3**: Return Home Button- the button here can easily have code attached that allows for an exit of the dialogue and response display.

## Requirements
-  **Unity Version**: Unity 2022.3.42f1 or later
-  **Platform Compatibility**: Compatible with Windows, MacOS, Android, and iOS
-  **Dependencies**: None

## Installation
1. **Download the asset package**: Download the latest release from Github repo or Unity Asset Store
2. **Import the package**:
   - Open Unity, navigate to 'Assets > Import Package > CustomPackage'
   - Selected downloaded '.unitypackage' file and select **Import**.
3. **Add the prefab**: Drag and drop the main prefab ('DialogueDisplay.prefab') from the 'Assets' folder into the selected scene.
   
## Usage

### Basic Setup
1. **Drag the prefab** into your scene from the 'Assets' folder
2. **Position and scale**: Te scene comes in 16:9 aspect ratio, which is the preferred scale for mobile devices and can be easily utilized by PCs as well. The buttons and main dialogue display positions can be changed as well.
3. **Play the demo**: Press 'Play' in the Unity Editor to test funcionality

### Customization
-  **Adjust Colors**: Open the prefab, and within the Hierarchy the Buttons and Dialogue Display can be opened within the Inspector. Inside the Inspector window, the colors of each item (Dialogue Display, Response Button 1, Response Button 2) can be customized.
-  **Script Modification**: The script contains a basic UI guideline for any character. This can be customized to fit the desired character, and the script that contains the character code can be attached to the UI script through dynamic binding.

## FAQ
**Q: Can I add more response options?**
A: Sure! you can duplicate either of the response buttons, rename it, and move it so that it is not covered by the other options. Make sure that new third option is included in  your script!

**Q: Can I remove the UI Script and add my own?**
A: Of course! The UI script provided is a good guideline, but as long as all the buttons are still defined in the new script and it is formatted to call similar functions at the same times then it should work just as well.

**Q: Can I change the size of the buttons/dialogue display to fit my dialogue length?** 
A: All of these will adjust to the size necessarily automatically when the dialogue and responses are loaded, so there's no need for you to change anything. 

**Q: Do these buttons still work on mobile devices (tapping)?**
A: Yes! This prefab is ready to be utilized on any device, mobile or otherwise.
