# Object Detection & Segmentation for Room Furniture

## 🎯 Goal
The objective of this project is to implement an object detection model capable of identifying various furniture pieces (e.g., chairs, tables, sofas) in an image of a room. Additionally, the project includes a segmentation task to separate the floor and walls, with an optional feature to allow color customization.

## 🚀 Features
- Detect furniture items in a given room image.
- Display bounding boxes and labels for detected objects.
- (Bonus) Segment the floor and walls separately.
- (Bonus) Provide the ability to change floor and wall colors dynamically.

## 🔗 Repository
Check out the full implementation here:
[GitHub - Furniture Identifier](https://github.com/omsenpaiii/Furniture-Identifier/tree/main)

## 🔗 Colab Notebook
To test the implementation, you can run the following Colab notebook:
[Grounded Segment Anything - Colab Demo](https://colab.research.google.com/drive/1aetDNZIxurcjn5SMbmby0ctPMlNd7Iat?usp=sharing)

## 🔗 Reference: Grounding DINO
This project utilizes Grounding DINO for object detection. Setup instructions:
```bash
%cd /content
!git clone https://github.com/IDEA-Research/Grounded-Segment-Anything
%cd /content/Grounded-Segment-Anything
!pip install -q -r requirements.txt
%cd /content/Grounded-Segment-Anything/GroundingDINO
!pip install -q .
%cd /content/Grounded-Segment-Anything/segment_anything
!pip install -q .
%cd /content/Grounded-Segment-Anything
```

## 🖼️ How It Works
1. Capture or select an image of a living room.
2. Process the image using the object detection model.
3. Display detected objects with bounding boxes and labels.
4. (Bonus) Perform floor and wall segmentation.
5. (Bonus) Change the color of segmented areas.

## 🔧 Setup & Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/omsenpaiii/Furniture-Identifier.git
   cd Furniture-Identifier
   ```
2. Install notebook:
   ```bash
   (https://github.com/omsenpaiii/Furniture-Identifier/blob/main/Furniture_Identifier.ipynb)
   ```
3. Open Google Colab and navigate to the provided Colab notebook link.
4. In Colab, go to **Runtime** > **Run all** to execute the notebook and test the model.

## 📌 Dependencies
- Python 3.x
- OpenCV
- PyTorch / TensorFlow
- Grounding DINO
- Segment Anything Model (SAM)
- Colab (for cloud-based execution)

## 🏆 Bonus Features
- **Advanced Segmentation:** Uses SAM (Segment Anything Model) for precise wall and floor segmentation.
- **Interactive Customization:** Enables changing wall and floor colors dynamically.

## 🔮 Future Scope
- Expand the dataset to test more furniture types and subcategories.
- Integrate Augmented Reality (AR) for real-world furniture visualization.
- Deploy the model as a web app using Flask or FastAPI.
- Can add depth estimation for room space to recommend suitable 3D furniture.

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

## 🤝 Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📬 Contact
For any queries, feel free to reach out:
- 📧 Email: omtomar4882.be22@chitkara.edu.in
- 🐦 Twitter: [@ot_tomar](https://x.com/ot_tomar)

---
🚀 **Happy Coding!**

# Developed for Ikarus 3D
By Om Tomar
