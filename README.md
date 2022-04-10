# Trading_Cards
This project is split into four different tasks which are described below. A separate Jupyter notebook is associated with each task.

### Task 1
Working with images from flatbed scanners that contain multiple (upto 18) trading cards from the 'Doctor Who' universe. Objective is to crop out the individual cards and store them to be used for later tasks.

### Task 2
Using Scale Invariant Feature Transform (SIFT) to perform keypoint matching and identify cards most similar to a given card in the dataset. Ideally the top matching cards will be duplicates of the card in question followed by some cards of other characters that are somewhat similar looking.

### Task 3
The images of cards cropped out in `Task-1` and `Task-2` are used to train a CNN model that tries to identify any card passed to it.
