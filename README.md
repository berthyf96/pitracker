# pitracker
Model training and testing information for COS 429 project PiTracker
## Credits
All models and prototxt files relied on the GazeCapture dataset and iTracker model information:
https://github.com/CSAILVision/GazeCapture
## Models
### PiTracker A
25% fewer filters than iTracker, trained with loss weights (1, 1, 1)
### PiTracker A2
25% fewer filters than iTracker, trained with loss weights (1, 0.5, 0.5)
### PiTracker B
25% fewer filters than iTracker, trained with loss weights (1, 0.5, 0.5), no face input
