# BEV-CMHF: A Cross-Modality Hybrid Fusion Framework for BEV 3D Object Detection with Feature Interaction and Temporal Fusion

## Estimate the Model Parameters

The total number of learnable parameters was estimated by iterating over each element in `model.parameters()` and summing their counts using `a.numel()`. The resulting parameter count is approximately **45.72 million**, indicating that the model possesses substantial representational capacity suitable for complex 3D object detection tasks.

## Estimate the Inference Speed

When evaluated on the nuScenes dataset using a single **NVIDIA GeForce RTX 4090**, the model achieves an inference speed of **5.79 images per second**, corresponding to an inference time of **172.64 milliseconds per image**. This demonstrates the model's potential for real-time 3D perception tasks.

## Code Availability

The official code implementation of BEV-CMHF will be released soon.
