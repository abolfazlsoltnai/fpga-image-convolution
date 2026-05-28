# 🖼️ FPGA Image Convolution

> **2D image convolution implementation in Verilog using Vivado and testbench-based image processing.**

---

## 📈 Visual Results

Let's look at the processing results first! Here is the original image alongside the convolved output:

<p align="center">
  <img width="1461" height="560" alt="Convolution Result" src="https://github.com/user-attachments/assets/c5e0b1c9-3224-4591-858b-1012c9ac3132" />
</p>

---

## 🛠️ Kernel Configurations

### 🔍 1. Sharpen / Edge Detection Kernel
For the convolution result shown above, the following kernel was used:

<p align="center">
  <img width="220" height="161" alt="Edge Detection Kernel" src="https://github.com/user-attachments/assets/aebb1fcb-857a-4b1d-821e-8c189e0416d7" />
</p>

💡 *Note: You can easily customize or change the kernel coefficients directly inside the `convolution.v` file.*

### 🌫️ 2. Image Blur Kernel
If you want to apply a simple blur effect to your image, you can use this low-pass filter kernel instead:

<p align="center">
  <img width="225" height="159" alt="Blur Kernel" src="https://github.com/user-attachments/assets/9a54dbc2-bd07-4fff-aa03-b59adf2c2f8f" />
</p>

**The Blur Result:** 👇

<p align="center">
  <img width="1370" height="493" alt="Blur Result" src="https://github.com/user-attachments/assets/40ec8444-5126-41e7-b4af-f40f7b7eabf0" />
</p>

---

## 🚀 Key Features
* ⚡ **Hardware Acceleration:** Full 2D convolution pipeline designed in Verilog HDL.
* 🛠️ **Simulation-Ready:** Includes a robust testbench environment to process actual image files using Vivado.
* 🎛️ **Flexible Architecture:** Highly modular design allowing quick runtime or compile-time kernel modifications.

---

## 🤝 Connect with Me

If you have any questions, suggestions, or just want to chat about FPGA and Image Processing, feel free to reach out!

<p align="center">
  <a href="https://www.linkedin.com/in/abolfazl-soltani-50a846231/" target="_blank">
    Linkedin
  </a>
</p>

<p align="center">
  📧 <b>Email:</b> <a href="abbolfazlsoltani9090@gmail.com
">abbolfazlsoltani9090@gmail.com
</a> <br>
</p>
