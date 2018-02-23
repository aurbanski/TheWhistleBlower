# TheWhistleBlower
Alex Urbanski  
Jonathan Meade  
Prof. Ben Shapiro  
CSCI-4830

## Goals
Our goal for this project was to design and develop a vehicle (specifically a bike) that used the different tones of
whistling input provided by the driver in order to accelerate, decelerate, and stop. Low tones indicate a deceleration backwards
and higher tones indicate an acceleration forward. A specific middle tone produces an immediate stop. 

## Problem-solving Approach
### Sensors
We used a microphone as a sensor to detect the various audio input we were collecting. While our demo used the microphones 
built into our laptops, stand-alone microphones are both cheap and plentifully available, bringing down the overall cost
of a full-scale prototype.

### Feature Extraction
We extracted the ConstQ data using provided audio analysis software. We chose this extraction method
because it gives us the most detailed data in terms of pitch being produced, which is what we based our 
output on. 

### ML Choices
Our ML algorithim was a Adaboost M1 trainer. We chose to use this model because it uses a series of decision trees 
to define the overall decision boundaries and we believe that with the amount of input we have coming in (104 unique inputs total),
a recursive series of decision trees is best suited to building these boundaries. 

## Improvement Ideas

## Demo Video