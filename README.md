# Image Color Palette Generator

A Flask-based web application that generates a color palette from an uploaded image. This project uses the **Pillow (PIL)** library to extract the most dominant colors from an image and displays them in a user-friendly interface.

---

## Features

- **Image Upload**: Users can upload an image file (e.g., JPG, PNG).
- **Color Extraction**: Extracts the most dominant colors from the image.
- **Color Palette Display**: Displays the extracted colors in a visually appealing palette.
- **Downloadable Palette**: Allows users to download the color palette as a CSV file.

---

## Technologies Used

- **Flask**: Python web framework for building the application.
- **Pillow (PIL)**: Library for image processing and color extraction.
- **Pandas**: Used to organize and export color data as a CSV file.
- **HTML/CSS**: For the frontend interface.

---

## How to Use

1. Clone the repository:

```bash
   git clone https://github.com/your-username/image-color-palette-generator.git
```

2. Navigate to the project directory:

```bash
cd image-color-palette-generator
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Flask application:

```bash
python main.py
```

5. Open your browser and visit:

```bash
http://127.0.0.1:5000
```
6. Upload an image and view the generated color palette.