# Coin-classifier
The Coin-classifier detects different US coins (pennies, dimes, quarters, nickels) and identifies them. This is used for children just learning about coins, but it can also be used for other purposes.

![Nickel](https://github.com/user-attachments/assets/8ef47430-a788-43a7-830e-5b4c9f74d8ef)

## The Algorithm

This is a retrained version of ResNet-18 that helps classify coins. It uses an edited version of the Jetson Inference ImageNet to identify the coins. 

## Running this project

1. Make sure that you have the Jestson inference and the Jestson Utils downloaded.
2. Include any required libraries that need to be installed for your project to run.
3. Go into the project directory and run this line of code:
  python3 coin.py --network=model/coin/resnet18.onnx --labels=model/coin/labels.txt /dev/video0 webrtc://@:8554/my_output

[View a video explanation here](video link)
