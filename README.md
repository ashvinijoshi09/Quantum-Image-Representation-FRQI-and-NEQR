# Quantum-Image-Representation-FRQI-and-NEQR
This project provides an efficient and educational implementation of quantum image representations, specifically FRQI and NEQR, which allow classical images to be encoded into quantum states. These representations support various quantum algorithms for image transformation, compression, and analysis — enabling exploration of how quantum computing can impact the future of image processing and computer vision.

# Features
⚛️ FRQI Encoding
Uses angle-based amplitude encoding for grayscale image intensities.

🧮 NEQR Encoding
Stores pixel values directly using computational basis states for higher precision.

🔄 Quantum Circuit Implementation
Circuits built using Qiskit for visualization, manipulation, and measurement.

🖼️ Classical-to-Quantum Conversion
Convert grayscale or binary images into corresponding quantum representations.

📊 Visualization Tools
Simulate and visualize quantum states, probability distributions, and pixel retrieval.



Applications
-------

🧠 Quantum Image Processing (QIP)
Edge detection, filtering, and transformation on quantum states.

🔐 Quantum Steganography and Watermarking
Secure encoding of images using quantum properties.

🧪 Quantum Machine Learning (QML)
Preprocessing step for image-based quantum learning models.

🛰️ Quantum Communication
Efficient transmission of image data over quantum channels.

🛠️ Methodology
-----------------

### 🖼️ Image Preprocessing
- Resize to power-of-2 dimensions  
- Convert to grayscale or binary formats

### ⚛️ Encoding
- **FRQI**: Encode position & intensity using angles  
- **NEQR**: Encode position & pixel value using binary basis states

### 🧱 Quantum Circuit Construction
- Use controlled rotations and multi-qubit gates for encoding  
- Prepare initial state, apply Hadamards and required gates

### 📉 Simulation and Measurement
- Simulate circuits using Qiskit Aer  
- Extract pixel information via state vector or measurement results

🧰 Tools & Libraries
------------------
🧪 Qiskit – Building and simulating quantum circuits

📊 NumPy – Vector and matrix operations

🖼️ OpenCV / PIL – Image preprocessing

📈 Matplotlib – Result visualization

📜 License
--------------
This project is licensed under the MIT License.
You are free to use, modify, and distribute this software in accordance with the terms of the license.
