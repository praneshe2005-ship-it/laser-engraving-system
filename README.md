# laser engraving system
Laser Engraving Systems Using Light Burn
# Laser Engraving System

An image-to-engraving pipeline that converts a user-uploaded image into a grayscale format 
and engraves it onto a wooden surface using a laser module.

## Overview
This system takes any image uploaded by a user, processes it using image processing 
techniques, and generates a laser path to accurately reproduce the image as an engraving on 
wood.

## Features
- Accepts user-uploaded images as input
- Automatic grayscale conversion for engraving-ready output
- Custom laser path generation algorithm for accurate reproduction
- Engraves directly onto wooden surfaces via a laser module

## Tech Stack
- Python (image processing & path generation)
- OpenCV / PIL (grayscale conversion, image handling)
- Embedded systems (laser module driver/control)
- Laser module hardware

## How It Works
1. User uploads an image
2. Image is converted to grayscale to determine engraving intensity/depth
3. A path generation algorithm converts pixel data into laser movement instructions
4. The laser module traces the generated path onto the wooden surface

## Author
Pranesh E — B.E. Robotics and Automation, Sri Ramakrishna Engineering College
