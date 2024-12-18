# Virtual Painter - Computer Vision ![Project Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FBrunosCodeLab%2FVirtualPainter-ComputerVision&count_bg=%235C9CFF&title_bg=%23008FC9&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)

<div align="center">
    <img src="https://raw.githubusercontent.com/BrunosCodeLab/Images/refs/heads/main/VirtualPainter-CV/VirtualPainter.png" alt="Banner" width="1080" />
</div>

## Description

**Virtual Painter** leverages hand gesture detection to enable users to control various drawing tools in a digital space. This tool allows users to draw with hand gestures using their camera.

Through real-time hand detection, the program tracks the user's hand movements In **Drawing Mode**, the program follows the index finger's movement and converts it into lines on the digital canvas.
Additionally, the program integrates the drawing interface with the main screen, displaying colors and an eraser tool for real-time creation. If the user’s fingers are within a specific area on the screen, and two designated fingers (**Selection Mode**) are raised, the program will select the corresponding color or eraser option. This functionality enables intuitive and easy selection of tools through hand gestures.

## Features

- **Hand Gesture Detection**: Tracks the movements of the user's hand and converts them into drawing actions.
- **Drawing Mode**: Follow the index finger to draw lines on the screen.
- **Color & Eraser Selection**: Simple gestures for selecting different colors or the eraser tool.
- **Smooth Drawing**: Motion smoothing makes the drawing experience smooth and enjoyable.
- **Dynamic Interface**: The program adapts to the user’s hand position, with visual feedback for color and tool selection.

## User Interface

The interface is designed using **Adobe Photoshop** and is intended to manage the gesture drawing tool. It’s organized as a header with layers, allowing for intuitive interaction. The interface consists of four main options: red, green, blue, and eraser. By clicking in a predefined space on the camera feed, users can select one of these options.

- **Color Selection**: Once a color is chosen, its intensity is increased to highlight the selected option.
- **Eraser Tool**: The eraser tool is clearly displayed and becomes more visible when selected, making it easier for users to identify the active tool.

<div align="center">
    <img src="https://raw.githubusercontent.com/BrunosCodeLab/Images/refs/heads/main/VirtualPainter-CV/VirtualPainter_Banner.png" alt="Banner" width="1080" />
</div>
  

## How It Works

1. **Camera Setup**: The program configures the camera parameters based on user preferences.
2. **Hand Tracking**: The camera tracks the user's hand and gestures, detecting finger movements.
3. **Drawing**: The program converts the movement of the index finger into lines on the screen.
4. **Tool Selection**: Using predefined gestures, users can select different colors or the eraser tool by raising specific fingers within a designated space.
5. **Smooth Drawing**: Smoothing algorithms ensure the drawing is fluid and natural.


### A video demonstration of this project in action will be uploaded soon.


****
