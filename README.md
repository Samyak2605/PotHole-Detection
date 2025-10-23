🛣️ Road Damage Detection Application
🚧 Overview
The Road Damage Detection Application is a computer vision-based project designed to automatically identify and classify road surface damages such as potholes and cracks from images and videos. The primary goal is to enhance road safety and assist maintenance authorities by providing quick, automated, and accurate detection of road defects.
🧠 Problem Statement
Road damage such as potholes, longitudinal cracks, and alligator cracks pose serious risks to public safety and increase vehicle maintenance costs. Traditional methods of inspection are manual, time-consuming, and expensive.
To address this, the project leverages deep learning (YOLOv8) to detect and categorize road damage types automatically from visual data (images/videos), helping authorities prioritize repair work effectively.
✨ Key Features
🧩 Real-Time Detection – Perform live damage detection via webcam feed.

🖼️ Image Detection – Upload any road image to identify types of cracks or potholes.

🎥 Video Detection – Analyze recorded road footage and detect damages frame-by-frame.

📊 Visualization Dashboard – View confidence levels, bounding boxes, and detection results visually.

📚 Pretrained Model – Trained using the Crowdsensing-based Road Damage Detection Challenge 2022 dataset.

⚡ Fast and Lightweight – Powered by YOLOv8, optimized for quick inference on local GPU/CPU.

🌐 Interactive Web Interface – Built using Streamlit for an easy-to-use, browser-based interface.
🧰 Tech Stack
Category | Tools/Frameworks Used
Model | YOLOv8 (Ultralytics)
Language | Python 3.8
Web Framework | Streamlit
Deep Learning | PyTorch
Dataset | CRDDC 2022 (Crowdsensing-based Road Damage Detection Challenge)
Environment | Conda, CUDA (optional for GPU acceleration)
🚀 Features in Action
🖼️ Detection Using Image

🎥 Detection Using Video
🧩 Damage Types Detected
The trained YOLOv8 model can detect four major types of road damages:

🟧 Longitudinal Crack
🟦 Transverse Crack
🟥 Alligator Crack
🟨 Potholes
📈 Evaluation Results
The model was trained on the Japan and India subsets of the dataset using an RTX 2060 GPU.
👥 Contributors
• oracl4 (Mahdi Yusuf)
• Samyak2605 (Samyak Mittal)
💻 Languages Used
• Jupyter Notebook: 54.2%
• Python: 45.8%
