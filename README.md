# Book Cover Information Extractor using OCR

This project is a MATLAB-based application that automatically extracts relevant information from book covers using **Optical Character Recognition (OCR)**. It identifies and processes elements such as the **book title**, **author name**, and **publisher**.

Developed as part of a Bachelor's thesis at the Technical University of Iași, the application aims to automate the cataloging and metadata extraction process for libraries, online platforms, or archiving systems.

## 🎯 Objectives

- Implement an efficient OCR-based system to read book covers
- Apply **image preprocessing** to enhance OCR performance
- Extract structured text information (title, author, publisher)
- Develop a **user-friendly GUI** for image upload and text display
- Evaluate system accuracy and identify improvement directions

## 🛠 Technologies Used

- **MATLAB** (AppDesigner for GUI, Image Processing Toolbox)
- **Tesseract OCR** (via MATLAB integration)
- Preprocessing: grayscale conversion, noise removal, contrast adjustment, binarization
- Postprocessing: error correction, string cleaning, formatting output

## 💻 Features

- Upload book cover images (various formats)
- Automatically process and extract key metadata
- Display recognized text in a clear and structured format
- High modularity for future improvements or integration

## 📊 Experimental Results

- Tested on a variety of book covers with different text styles and quality
- Achieved an average OCR recognition accuracy of ~85%
- Identified improvements through preprocessing and filtering techniques

## 📷 Example Workflow

1. Load an image of a book cover
2. Apply image preprocessing (binarization, noise reduction)
3. Use OCR to extract text from the image
4. Clean and format the text output
5. Display results in the GUI

## 📌 Use Cases

- **Library automation**: helps with cataloging physical books efficiently
- **Online stores**: extract metadata from photos for listing products
- **Archiving tools**: digitize and label collections automatically

## 🔄 Future Improvements

- Integrate deep learning models for more robust text detection
- Expand to spine/back cover recognition
- Improve accuracy for low-quality or artistic covers

## 📘 License

This project is intended for academic and research purposes only.

## 👤 Authors

- Ștefan Atomulesei  
- Robert-Teodor Aioanei  
- Roxana-Maria Alexa  

**Faculty of Automatic Control and Computer Engineering**  
Technical University of Iași – 2025  

