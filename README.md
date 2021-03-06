# Celectrophy
A Lightweight Linux-based Monkey Electrophysiology Experiment Software for Research Laboratories Written in C.

### Compatible Setup
**Current version of the software is developed to work with the following setup**
- Blackrock Microsystems [CerePlex Direct](https://www.blackrockmicro.com/neuroscience-research-products/neural-data-acquisition-systems/cereplex-direct-daq/) as Data Acquisition System (DAQ)
- SR Research [EyeLink 1000 Plus](https://www.sr-research.com/eyelink-1000-plus/) as Eyetracker
- Arduino Uno Microcontroller Board to Handle Input/Outputs and ADC
- A Phototransostor to Detect Vertical Retrace of Display
- A Reward Dispenser to Provide Positive Feedback to Subject

### Main Capabilities
**This software can perform the following**
- Present Stimuli
- Synchronize Behavioral Experiment Events With Neural Data
- Dynamically Manipulate Experiment Parameters During Experiment Runtime
- Provide Different Views of the Experiment with Different Levels of Information for Subject and Experimenter in Multi-Display Setups

## Installation
The following are the installation steps for ubuntu 18.04.4 LTS (Bionic Beaver)

1) Install the necessary SDL2 libraries 

```bash
sudo apt install libsdl2-dev libsdl2-gfx-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-ttf-dev
```

2) Install the Eyelink Display Software Library for Linux from SR Research Repository

```bash
sudo add-apt-repository "deb http://download.sr-support.com/software SRResearch main"
sudo apt-get update
sudo apt-get install eyelink-display-software
```
