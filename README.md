# PGM Image Editor

This project implements a PGM (Portable Gray Map) image editor in C++ using 2D arrays. The editor allows users to perform various operations on PGM images, including flipping, brightness adjustment, and finding image negatives.

## Features

- **Load and Save PGM Images**: Load PGM images from files and save the edited images to new files.
- **Flip Images**: Flip images vertically or horizontally.
- **Change Brightness**: Increase or decrease the brightness of images.
- **Negative Images**: Create negative versions of images.
- **Combine Two Images**: Combine two images side by side.
- **Median Filter**: Apply a median filter to remove noise from images.
- **Custom Filter**: Apply a custom filter to images (bonus feature).

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/pgm-image-editor.git
   cd pgm-image-editor
   ```

2. **Compile the Program**:
Compile the source code using a C++ compiler:
```bash
g++ -o pgmEditor main.cpp pgmEditor.cpp
```

3. **Run the program**
```bash
./pgmEditor
```

4. **Follow the On-Screen Instructions**:
The program will prompt you to enter the name of the image file you want to edit. Then, you can choose from various editing options by entering the corresponding number:

 * 1: Combine Two Images Side by Side
 * 2: Change Brightness
 * 3: Find Negative of an Image
 * 4: Flip Image Vertically
 * 5: Flip Image Horizontally
 * 6: Apply Median Filter (Remove Noise)
 * 7: Apply Custom Filter (Bonus)
 * -1: Exit the Program

5. **Requirements**

-C++ Compiler
- Basic knowledge of PGM file format


6. **File Structure**
- main.cpp: Main file containing the program's entry point.
- pgmEditor.h: Header file for the grayImage class.
- pgmEditor.cpp: Implementation of the grayImage class methods.


7. **License**:
This project is licensed under the MIT License - see the LICENSE file for details.


8. **Contributing**:
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


9. **Acknowledgements**;
This project is inspired by basic image processing techniques and serves as an educational tool for learning C++ and image manipulation.


