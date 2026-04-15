# Screen Printer Tool Proposal

## Repository
https://github.com/Samaya-V/Final-Project-Proposal.git

## Description
This code can take images, modify them, and work with them in many ways useful for screenprinting and CMYK work.

## Features
- CMYK Separations
	- Gives the user the Magenta, Cyan, Yellow, and Key (Black) channels for their image so that they can screenprint the design on paper with inks. I will do this using Pillow, which has demonstrated its ability to work with color channels in previous assignments.
- Halftone Generator
	- Halftones are fun to do with screenprinting, especially when they're more visible than need be. Using Pillow and maybe Numpy or OpenCV, I will make a halftoned image creator. 
- Registration marks
	- The program will be able to also add registration marks to the images so that they can be lined up perfectly during screenprinting. I will do this with Pillow's ImageDraw functions that have been previously explored.

## Challenges
- Learning how to edit an image to be halftoned in Python using libraries and such
- Maybe making a ui that allows you to type in what exactly you want the program to do (color separations WITHOUT registration marks, etc).
- Avoiding Moire patterns in the color separations and having to work around that.

## Outcomes
Ideal Outcome:
- I have accomplished all 3 functions and they have a simple working UI, or even an interactive click-based one if things go well.

Minimal Viable Outcome:
- Just CMYK separation and registration marks, because the halftones are the part that's hardest and most new.

## Milestones

- Week 1
  1. Image Upload + CMYK Output nput
  2. CMYK Conversion, the program takes an image, splits it up, and spits it out.

- Week 2
  1. Halftones can be created with whatever size the user inputs.
  2. Can output an image with halftones.

- Week N (Final)
  1. Implement the registration marks (easy)
  2. Make the halftone function able to be used on the CMYK split paths as intended.
