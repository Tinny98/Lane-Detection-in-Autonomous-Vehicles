# Lane Detection in Autonomous Drivable Vehicles

This project is about detecting the Drivable area and detecting lanes on the road. This project is mainly about using machine learning model to fine-tune the model with the dataset we generated using stable diffusion in addition to the real data.
## Dataset

- The dataset is structured into three distinct partitions: Train, Test, and Validation. The Train split comprises 80% of the dataset, containing both the input images and their corresponding labels. Meanwhile, the Test and Validation splits each contain 10% of the data, with a similar structure, consisting of image data and label information. Within each of these splits, there are three folder


#### Original Image

![image](https://github.com/balnarendrasapa/road-detection/assets/61614290/cda57ce3-14f0-4fec-aa8c-03974c25a753)

#### Annotation for Drivable area segmentation

![image](https://github.com/balnarendrasapa/road-detection/assets/61614290/c34f80fa-07e8-4b82-b767-9da4f8f14071)

#### Annotation for Lane detection

![image](https://github.com/balnarendrasapa/road-detection/assets/61614290/d2ef6899-de98-41ea-a723-4498ae4454e6)




## References

[1] [TwinLiteNet: An Efficient and Lightweight Model for Driveable Area and Lane Segmentation in Self-Driving Cars](https://arxiv.org/abs/2307.10705), **Authors**: Quang Huy Che, Dinh Phuc Nguyen, Minh Quan Pham, Duc Khai Lam, **Year**: 2023. Click [here](https://github.com/chequanghuy/TwinLiteNet) to go the TwinLiteNet Repository

[2] The Stable Diffusion code is referenced from here. click [here](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb)


