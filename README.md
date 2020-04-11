# Group 27 - ASE Final Project

This project aims to detect the available parking spaces in a parking lot by using a Convolutional Neural Network.
We will be training a model which would have the capability to read video frames one by one and then draw a green boundary around the empty detected parking spaces.
Similarly it would draw a red boundary around the occupied parking spaces.

## How to run : 
```
python main.py --image images/parking_lot_1.png --data data/coordinates_1.yml --video videos/parking_lot_1.mp4 --start-frame 400
```
