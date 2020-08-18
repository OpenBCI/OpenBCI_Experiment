# OpenBCI_Experiment

Welcome to the OpenBCI Puppies and Kittens Experiment designed by Fan Li.

During this experiment, you will watch a video containing images of puppies and kittens, and press a button every time you see a puppy in the image.

Below are the instructions on how to do it. The full information on this experiment can be found on [Fan Li's Repository](https://github.com/Fan1117/Puppies_and_Kittens/)

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

Connect the breadboard containing the external button to the Cyton board as shown in the picture below. Place the breadboard beside your computer such that the photocell points to the lower left corner of your screen, which is where the video trigger will be located.

![](connect.jpg)

## Step 4: Run Experiment

Download [this video](video.mp4). Once you're ready to start, press ```Start Data Stream``` in the GUI,open the video, and make it Full-Screen. Every time a puppy appears in the video, press the button. The video is around 3 minutes long. You're now ready to press play!

## Step 5: Retrieve and Send Data

Once you've finished watching the video, press ```Stop Data Stream```. In your /Documents/OpenBCI_GUI/Recordings folder you should find the recorded data for that session. Send us that file via Slack or email along with any feedback you may have. Thank you for taking part this experiment!


