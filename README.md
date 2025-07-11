## ✨ Project Highlights: *Image Sharpening Using Knowledge Distillation*

### 🏁 Outcomes: What We Achieved

In this project, we successfully developed a real-time image sharpening system using a teacher–student model framework through Knowledge Distillation. A deep convolutional neural network (the teacher) was trained to restore sharpness to blurry images. Then, a lightweight student model was trained to replicate the teacher’s output while maintaining a drastically reduced computational footprint. Despite being compact, the student model preserved high image quality, achieving average SSIM scores above 0.90 on unseen test images. Additionally, the student model ran at speeds of 30 to 60 frames per second, making it perfectly suited for real-time applications like video conferencing, where bandwidth limitations often lead to degraded image quality. The project achieved its primary objective — balancing visual fidelity and processing efficiency.

### ⚠️ Limitations: Every Hero Has a Weakness

While the student model achieved excellent performance, there were a few challenges and constraints. First, although the student closely mimicked the teacher’s output, it exhibited minor loss of ultra-fine image details in some cases — a typical trade-off when compressing large models. The training process of the teacher model was also resource-intensive due to its deep architecture and large number of parameters. Furthermore, the dataset used was relatively modest in size, with 377 images in total. Although the results were strong, a larger and more diverse dataset would further validate the model’s robustness under various degradation scenarios and lighting conditions.

### 🚀 Future Scope: Where We’re Headed

The promising results open up multiple paths for future enhancement. One immediate direction is expanding the dataset with a wider range of real-world blurred images, including motion blur, low-light conditions, and compression artifacts. Integrating modern techniques like attention mechanisms or multi-scale feature extraction into the student model could further boost the model’s ability to reconstruct fine-grained details. On the loss function side, replacing standard MAE loss with perceptual losses like VGG-based loss or MS-SSIM could lead to even more visually pleasing results. Finally, optimizing the trained student model for deployment on edge devices via TensorFlow Lite or ONNX would enable use in mobile apps, webcams, and IoT systems for live image enhancement — making the system truly production-ready.

---

### 👨‍💻 Authors

**Team Axion**  
- Arya Vinod  
- Ashlin Rose Manoj  
Saintgits Group of Institutions, Kottayam, Kerala

### 👏 Acknowledgments

This project was made possible thanks to the generous support of the **Intel© Unnati Program**. We extend our heartfelt gratitude to our mentors, **Er. Anish M George** and **Mr. Siju Swamy**, for their expert guidance and constant encouragement throughout this journey. Their insights shaped the technical depth and practical focus of this work. We also thank **Saintgits College of Engineering and Technology** for providing the platform, resources, and academic atmosphere essential to our development. Finally, we appreciate the contributions of the wider AI/ML research community whose open-source efforts in image enhancement and model compression inspired and informed our work.

---

🔗 *For more information or collaboration opportunities, feel free to connect with us through the project repository or institutional contact pages.*
