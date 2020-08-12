# OpenBCI_Experiment

Welcome to the OpenBCI Puppies and Kittens Experiment! 

During this experiment, you will watch a video containing images of puppies and kittens. You'll have to choose which of the two image classes you want to identify, and press a button everytime you see an image that belongs to that class.

Below are the instructions on how to do it.

## Equipment Required

1. Headwear - need to specify
2. [Cyton Board](https://shop.openbci.com/collections/frontpage/products/cyton-biosensing-board-8-channel?variant=38958638542)
2. [OpenBCI GUI](https://github.com/OpenBCI/OpenBCI_GUI/releases/tag/v5.0.0)
3. External button

## Step 1: Headwear and Board Setup

First, follow <this - insert link> tutorial to connect <insert headwear> to yourself and to the Cyton board.

## Step 2: Software Setup

Follow [this tutorial](https://docs.openbci.com/docs/01GettingStarted/01-Boards/CytonGS) to connect the Cyton board to the GUI, using your headwear instead of the example gold cup electrodes. Turn Data Streaming ON/OFF a couple of times until you make sure the data is being read correctly.

## Step 3: External Button Setup

Connect the breadboard containing the external button to the Cyton board as shown in the picture below. Place the breadboard beside your computer such that the photocell points to the lower right corner of your screen, which is where the video trigger will be located.

![[]connect.jpg

## Step 4: Run Experiment

Download [this video]. Once you're ready to start, press ```Start Data Stream``` in the GUI,open the video, and make it Full-Screen. Decide whether you will be searching for puppies or for kittens and make a note of it. If you choose puppies, every time a puppy appears in the video, you'll press the button. The same applies if you choose kittens. You're now ready to press play!

## Step 5: Retrieve and Send Data

Once you've finished watching the video, press ```Stop Data Stream```. In your /Documents/OpenBCI_GUI/Recordings folder you should find the recorded data for that session. Send it to us, letting us know whether you looked for puppies or for kittens. 


