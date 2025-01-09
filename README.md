# Tactigon Shapes

Tactigon Shapes is an extension of [Blockly](https://developers.google.com/blockly) which is a proect by Google and it allows you to create visual, drag-and-drop block-based programming interfaces. Instead of typing code, you can create programs by connecting blocks or shapes together. From Tactigon Shapes you can generates code in JavaScript, Python, PHP, or Dart based on the visual blocks. But we recommend to use Python because almost all of our projects speak Python. 

### Key Features of Tactigon Shapes:
- Visual Programming: Drag-and-drop interface that helps users understand programming concepts.
- Code Generation: Automatically generates code in multiple programming languages.
- Customizable: You can create your own blocks/shapes and define their behavior.

## Tactigon Ecosystem

Tactigon ecosystem is made of:
 - [Tactigon Gear](https://pypi.org/project/tactigon-gear/) to connect to a Tactigon Skin wearable device and do gesture recognition
 - [Tactigon Speech](https://pypi.org/project/tactigon-speech/) to implement voice recognition on top of Tactigon Gear
 - [Tactigon Arduino Braccio](https://pypi.org/project/tactigon-arduino-braccio/) to connect to the Arduino Braccio device

## Requirements

In order to use the Tactigon SDK the following prerequisites need to be observed:

### Instructions for Mac/Linux:
To setup the required tools on your system, follow the steps below:

- CPU with AVX/FMA support
  - To check if your Mac supports **AVX/FMA** you can go to **About This Mac**. Check the CPU model and verify its features online.
- Git [Download Git](https://git-scm.com/downloads)
- Python 3.8.10 [Download Python 3.8.10](https://www.python.org/downloads/release/python-3810/)

### Instructions for Windows Users:
To set up the required tools on your Windows 10 or Windows 11 operating system, follow the steps below:
- CPU with AVX/FMA support
  - To check if your CPU supports AVX/FMA you can press **Win + R** then type **msinfo32** and press Enter. Check the CPU model and verify its features online.
- Git [Download Git](https://git-scm.com/downloads)
- Python 3.8.10 [Download Python 3.8.10](https://www.python.org/downloads/release/python-3810/)
- Microsoft C++ Build Tools and Windows 10/11 SDK. 

#### Microsoft C++ Build Tools and Windows 10/11 SDK installation
Open the Visual Studio Installer on your system. if you do not have, [Download Visual Studio Installer](https://visualstudio.microsoft.com/downloads/)
- From the Visual Studio Installer, click Modify or select Install for new installation.
- Go to the individual components tab and install the latest version 
  - MSVC v143 - VS 2022 C++ Build Tools x64/x86 (latest version)
  - Windows 10/11 SDK (latest version matching your windows version)

![Screenshot 2024-11-21 162339](https://github.com/user-attachments/assets/5f6332f1-be2b-4fee-ad62-7feb734db710)

## Clone Tactigon Shapes

1. Copy the URL for HTTPS by clicking Code button.

![image](https://github.com/user-attachments/assets/bc9664eb-ba03-4ad4-b11d-9f29fcdd2289)


2. Open the Command Line for Windows or Terminal for Mac/Linux and run the following command.

```
git clone https://github.com/TactigonTeam/Tactigon-Shape.git
```

![image](https://github.com/user-attachments/assets/7027d8b3-9388-4f67-a7f9-fb967fa49b1d)

3. Navigate to the Tactigon SDK folder and open the project with your favorite code editor.

![Code_0JguwTxnH2](https://github.com/user-attachments/assets/18b8e6d9-e264-4730-bd16-f29607859186)

## Create Virtual Environment
It is recommended to create a dedicated python virtual environment and install the packages into the virtual environment:  

To create a virtual environment, run the following code.
```
python -m venv venv
```

If your operating system is MacOS or Linux you can activate the virtual environment by running this command.
```
source venv/bin/activate
```
For Windows users, you can execute this command to activate the Virtual Environment.
```
.\venv\Scripts\activate
```

Depending on your installation (Linux, Raspberry, Mac users) you may need to use `python3` and `pip3` instead of `python` and `pip` respectively

## Install

To install the correct dependecies it is mandatory to follow the following step:
```zsh
pip install flask==3.0.3 flask_socketio==5.3.6 gevent==24.2.1 tactigon_gear==5.2.0 PyAudio==0.2.13 pynput==1.7.7 sympy==1.13.2
pip install deepspeech-tflite==0.9.3 --no-deps
pip install tactigon_speech==5.0.8.post1 --no-deps
```
![image](https://github.com/user-attachments/assets/94d27fbe-58fe-4519-9127-b97bac8677c5)

## Run Tactigon Shapes 
1. Simple execute the main.py by running following command.
```
python .\main.py
```
![Code_ogZWoAEQee](https://github.com/user-attachments/assets/c4bfc927-1a3b-4491-942a-2be86a10a8dd)

2. Open the web browser and type this http://127.0.0.1:5123 on the search bar. You will see a page whre you can connect to TSkin device.

![image](https://github.com/user-attachments/assets/e576893d-e499-4b2f-aeae-d825a4102087)

## How to use Shapes

Using Shapes is like building with LEGO bricks, you drag, drop, and connect pieces to create something functional. Here you will go through step by step how to use shapes. 

Step 1:
