**🌟 Vistara – Stylize Your Image Perfect**


Vistara is a Python-based desktop application that transforms ordinary images into stylized versions using OpenCV and a clean Tkinter GUI. Whether you're enhancing portraits or experimenting with visual effects, Vistara offers a smooth, elegant experience for image transformation.




**🖼️ Features**

- *📁 Easy Image Upload* – Select any image using a simple file dialog
- *🎨 Cartoonify Effect* – Converts your image into a stylized image using:
    - Grayscale conversion
    - Median blur smoothing
    - Edge detection via adaptive thresholding
    - Bilateral filtering for color smoothing
    - Bitwise masking for final stylization
- *🔍 Side-by-Side Comparison* – View all transformation stages in a 3×2 grid
- *💾 Save Output* – Save the final cartoonified image with a single click
- *🧑‍🎨 Elegant UI* – Minimalist interface with custom fonts and colors




**🔧 Prerequisites**
Make sure you have the following Python libraries installed:
$$
pip install opencv-python easygui imageio matplotlib pillow
$$


▶️ Run the App
$$
python vistara.py
$$

The GUI will launch, allowing you to upload and stylize your image.



**📂 File Structure**
- vistara.py         # Main application script
- README.md          # Project documentation
- LICENSE
- gitattributes
- requirements


**🧠 How It Works**
- Upload Image – Choose an image using easygui.fileopenbox()
- Process Pipeline:
- Convert to RGB
- Resize for display
- Convert to grayscale
- Apply median blur
- Detect edges with adaptive threshold
- Apply bilateral filter for smooth color
- Display Results – Show all stages using matplotlib
- Save Output – Save final image with a custom name in the original directory




