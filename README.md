# Trading_Cards
This project is split into four different tasks which are described below. A separate Jupyter notebook is associated with each task.

#### Task 1
Working with images from flatbed scanners that contain multiple (upto 18) trading cards from the 'Doctor Who' universe. Objective is to crop out the individual cards and store them to be used for later tasks.

#### Task 2
Using Scale Invariant Feature Transform (SIFT) to perform keypoint matching and identify cards most similar to a given card in the dataset. Ideally the top matching cards will be duplicates of the card in question followed by some cards of other characters that are somewhat similar looking.

#### Task 3
- Smartphone captured images of the cards lying on a table are processed to crop the cards out.
- The images obtained from above step along with those cropped out in `Task-1` are used to train a CNN model that tries to identify any card passed to it.

#### Task 4
- Read videos captured by a smartphone of the trading cards lying on a table and extract certain frames to process.
- Crop out the cards from the frozen frame using techniques described in `Task-3`.
- Run inference using the CNN model trained in `Task-3` to identify the cards present in the video.
