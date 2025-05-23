# 🎨 Color Detector Web App

This is a responsive web application built with **Streamlit** that detects colors from any image uploaded by the user. By clicking on any point of the image, the app returns the closest matching color name, its RGB values, and a color preview box.

## 🚀 Features

- 📤 Upload and display an image (JPEG/PNG)
- 👆 Click anywhere on the image to detect a color
- 🔍 Detect and compare RGB values with a color dataset
- 🏷️ Display the closest color name and exact RGB/HEX values
- 🎨 Show a preview box filled with the detected color
- 📱 Responsive layout and interactive interface
- ✅ Error handling for invalid files or missing dataset

## 🧰 Technologies Used

- Python
- Streamlit
- OpenCV (cv2)
- Pandas, NumPy
- streamlit-image-coordinates (for click detection)

## 📂 Dataset

The app uses a `colors.csv` file containing predefined color names with corresponding RGB values. You can extend this dataset with more custom or standard colors.

### Required Columns in `colors.csv`:
- `color_name`
- `R`
- `G`
- `B`

## 📦 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/color-detector-app.git
   cd color-detector-app
