VibeVastra VR Feature
Welcome to VibeVastra VR Feature, a pioneering project that redefines the way you experience fashion! This feature allows users to virtually try on clothes using the latest in VR technology. Utilizing the HR-VITON model, VibeVastra VR Feature offers a realistic and immersive virtual dressing experience. Discover a wide range of outfits, experiment with different styles, and visualize how garments fit and complement your look—all from the comfort of your home. This project aims to elevate the shopping journey by integrating state-of-the-art machine learning and virtual reality innovations.


Process Overview 

Pose Detection: The model detects the user’s pose using DensePose, providing detailed information about body parts and their regions.
Segmentation: It applies segmentation to differentiate clothing sectors, identifying areas where garments will be placed.
Pose Data Generation: PoseNet generates user pose data, including body angles and positions.
Garment Synthesis: By combining pose data, segmented clothing regions, and garment images, the model creates a seamless virtual try-on experience.
HR-VITON Model: This PyTorch-based deep learning model is trained on the VITON-HD dataset, ensuring high-resolution results.
