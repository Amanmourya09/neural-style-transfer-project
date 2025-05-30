# Neural Style Transfer Project

This is a simple implementation of **Neural Style Transfer** using **TensorFlow Hub** and **Google Colab**.

## 🎯 Objective
The goal of this project is to apply the artistic style of one image onto another while preserving the content of the original image. This demonstrates how deep learning can be used for creative applications like digital art generation.

## 🔧 Technologies Used
- Python
- TensorFlow / TensorFlow Hub
- Google Colab
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

## 🖼️ What Does It Do?
- Takes a **content image** (e.g., a photo of a landscape)
- Applies the **style of another image** (e.g., Van Gogh's *Starry Night*)
- Outputs a new image that combines both:
  - **Content preserved**
  - **Style applied**

## 📁 Contents
- `Neural_Style_Transfer.ipynb`: Google Colab notebook with full code
- `content_mountain_lake.jpg`: The original image whose content is preserved
- `style_starry_night.jpg`: The painting used for style transfer
- `stylized_output.jpg`: Final stylized output image
- `README.md`: This file (project description)

## 🚀 How to Run
1. Open the [Colab Notebook](https://colab.research.google.com/drive/1PPunTx2QHPe6Jlm7VhX1oL8pKRb5NVl0) 
2. Runtime > Run All
3. See the final stylized image displayed at the end

> Note: The notebook uses predefined images for automatic execution.  
> Optional: You can uncomment the upload section to use your own images.

## 🧠 Approach
- Uses the Magenta model from TensorFlow Hub
- Images are resized to 256x256 pixels
- Style transfer is applied using deep learning techniques

## 🌐 Links
- **GitHub Repo:** https://github.com/Amanmourya09/neural-style-transfer-project   
- **Live Demo (Colab):** https://colab.research.google.com/drive/1PPunTx2QHPe6Jlm7VhX1oL8pKRb5NVl0   
- **Presentation:** [Aman_Mourya_Neural_Style_Transfer_Project.pptx](Aman_Mourya_Neural_Style_Transfer_Project.pptx)

## 🙌 Acknowledgment
Model source: [TensorFlow Hub - Magenta Model](https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2) 

---
Made with 😠 by **Aman Mourya**
