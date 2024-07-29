Video Location Estimator
Overview
This project uses the SatCLIP model to estimate the geographic location of a video based on its visual content. It works by extracting frames from the video, processing each frame through the SatCLIP model, and averaging the estimated locations to produce a final location estimate.
Prerequisites

Python 3.7+
FFmpeg
PyTorch
rasterio
scikit-learn
numpy
matplotlib

You also need to have the SatCLIP model and its associated data (control embeddings, locations) set up.
