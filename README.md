# LipReadingtoText
Developed a data loader for video frames to extract a specific region of interest (ROI) corresponding to the lips, utilizing techniques such as image cropping and resizing to focus on the relevant area.
Implemented a data pipeline for shuffling, mapping, padding, and prefetching video frames, ensuring efficient and optimized input for the lip reading model.
Designed a deep neural network architecture for lip reading, incorporating Conv3D layers to capture spatio-temporal features from the video frames and bidirectional LSTMs to model temporal dependencies and context.
Preprocessed and prepared the training data, including lip region extraction, alignment, and synchronization with the corresponding text labels or captions.
Set up the training process by defining learning schedulers, such as step decay or cyclic learning rates, to optimize the model's performance over time.
Implemented callbacks to monitor the training progress, including early stopping to prevent overfitting and model checkpointing to save the best-performing model weights.
