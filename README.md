## ✨ Project Highlights: *Image Sharpening Using Knowledge Distillation*

### 🏁 Outcomes:

In this project, we developed a real-time image sharpening system using the teacher–student model paradigm with knowledge distillation. A deep convolutional neural network (the teacher) was tasked with restoring sharpness to blurry images, then a lightweight student model was trained to reproduce the teacher’s output with significantly lower computational costs. The compacted student model preserved image quality, achieving average SSIM scores exceeding 0.90 on unseen test images. Furthermore, the student model executed at 30 to 60 fps, which made it ideal for real-time scenarios such as video conferencing, where bandwidth constraints worsen image quality. The project met its main goal: achieving the desired balance between visual processing precision and operational efficiency.


### ⚠️ Limitations: 

The student model performed really well, but it faced some hurdles and limits. For starters even though the student copied the teacher's output, it sometimes lost tiny image details — a common issue when you shrink big models. Training the teacher model also took a lot of computing power because of its complex design and many settings. Also, the dataset wasn't that big, with 377 images. The results looked good, but using more varied images would show how well the model handles different image problems and lighting.

### 🚀 Future Scope:

The encouraging outcomes pave several directions for further optimization. One immediate avenue is broadening the dataset with more types of real-world blur, such as motion blur, low-light and compression artifacts. Incorporating recent advances such as attention mechanisms or multi-scale feature extraction into the student model could enhance the model’s capacity to reconstruct details. On the loss function side, swapping in perceptual losses like VGG or MS-SSIM instead of standard MAE loss can produce even more visually pleasing results. Last, fine-tuning the trained student model for edge device deployment using TensorFlow Lite or ONNX would allow use in mobile applications, webcams, and IoT devices for real-time image super-resolution. This renders the system effectively production-ready.

---

### 👨‍💻 Authors

**Team Axion**  
- Arya Vinod  
- Ashlin Rose Manoj  
Saintgits Group of Institutions, Kottayam, Kerala

### 👏 Acknowledgments

This project was made possible thanks to the generous support of the **Intel© Unnati Program**. We extend our heartfelt gratitude to our mentors, **Er. Anish M George** and **Mr. Siju Swamy**, for their expert guidance and constant encouragement throughout this journey. Their insights shaped the technical depth and practical focus of this work. We also thank **Saintgits College of Engineering and Technology** for providing the platform, resources, and academic atmosphere essential to our development. Finally, we appreciate the contributions of the wider AI/ML research community whose open-source efforts in image enhancement and model compression inspired and informed our work.

---
