## Glacier Melt Prediction using Spatio-Temporal Graph Neural Networks

This project explores the prediction of glacier melt in the Himalayan region using a hybrid deep learning approach that combines **Convolutional Neural Networks (CNNs)** and **Spatio-Temporal Graph Neural Networks (GNNs)**. 
The model analyzes satellite image sequences (GIFs) to detect and estimate visual melt patterns over time.

## Key Highlights

Estimation based on visual pixel-level changes
**CNN (ResNet50)** for frame-wise spatial feature extraction
**GraphSAGE-based GNN** for capturing temporal and spatial dependencies across frames
Input: Satellite time-lapse GIFs of Himalayan glaciers
Output: Melt prediction graph based on observed visual changes

You can view the full implementation, model architecture, experiments, and results in the report
[`projectgnn.pdf`](projectgnn.pdf)

## Tech Stack

| **Component**      | **Tools & Libraries**                                                                        |
| ------------------ | -------------------------------------------------------------------------------------------- |
| Model              | ResNet50 (CNN) for spatial feature extraction + GraphSAGE (GNN) for spatio-temporal analysis |
| Framework          | PyTorch, PyTorch Geometric, NetworkX                                                         |
| Platform           | Google Colab (Python environment for development and training)                               |
| Image Handling     | OpenCV (for image/frame processing)                                                          |
| Visualization      | Matplotlib (for plotting graphs and visual comparisons)                                      |
| Data Source        | Satellite time-lapse GIFs from publicly available repositories (e.g., NASA Worldview)        |


## Project Status

Completed  
Submitted: June 2025  
Developed as part of an AI/ML research project (2nd year, VIT Chennai)

## Author
Hari Samhita Pasupuleti 
B.Tech Computer Science and Engineering (AI/ML)  
VIT Chennai  
[GitHub Profile](https://github.com/samhita18)  
hari.samhita18@gmail.com


> This repository demonstrates the use of deep learning and graph-based modeling for climate-impact research, making it a great addition to AI-for-Earth or sustainability portfolios.



