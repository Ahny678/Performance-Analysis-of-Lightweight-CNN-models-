## Trained Models and Results

**Download trained models and experimental results:**
👉 [https://drive.google.com/drive/folders/1ZzIIbyRSyJqvVQUHS7SePpaWWlB8AP48](https://drive.google.com/drive/folders/1ZzIIbyRSyJqvVQUHS7SePpaWWlB8AP48)

---

## Project Overview

Crop health is a critical determinant of food security, particularly in developing regions where staple crops such as **maize, sorghum, and rice** serve as primary sources of nutrition. Fungal diseases pose a significant threat to these crops, often resulting in substantial yield losses. Conventional disease detection methods are largely manual, time-consuming, and prone to human error, highlighting the need for **automated and scalable diagnostic solutions**.

This study investigates the use of **lightweight Convolutional Neural Networks (CNNs)** for accurate and efficient classification of fungal diseases in crop leaf images. Five pre-trained CNN architectures were evaluated:

* VGG16
* MobileNetV3
* DenseNet121
* NASNetMobile
* EfficientNetB2

The models were trained and tested on a curated dataset containing both healthy and diseased leaf images. Performance was evaluated based on **classification accuracy, computational efficiency, model size, and suitability for deployment in low-resource environments**.

---

## Key Findings

* **EfficientNetB2** achieved the highest classification accuracy across maize, sorghum, and rice datasets.
* **MobileNetV3** emerged as a strong alternative for edge and mobile deployment due to its **low memory footprint and fast inference time**.
* All evaluated models demonstrated the feasibility of using lightweight CNNs for real-time crop disease detection.

---

## Conclusion

The results confirm that lightweight CNN architectures can be effectively deployed for **early fungal disease detection in crops**, making them well-suited for **precision agriculture applications in resource-constrained settings**. This work supports the development of accessible AI-driven tools to improve crop monitoring, reduce yield losses, and enhance food security.

 
