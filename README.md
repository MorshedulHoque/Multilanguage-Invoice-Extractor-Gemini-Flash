# Multilanguage Invoice Extractor

## Project Overview
This application leverages Google's Gemini 1.5 Flash model to extract and interpret data from invoice images. It supports multiple languages and integrates environmental variables and a Streamlit interface to interact with users, providing real-time invoice analysis.

## Features

| Feature               | Description                                                               |
|-----------------------|---------------------------------------------------------------------------|
| Environment Variables | Manages sensitive data securely with Python's `dotenv` package.           |
| Streamlit Interface   | Provides a user-friendly, web-based interface for uploading and analyzing invoices. |
| Image Processing      | Uses the PIL library to handle image uploads and processing.               |
| Multilanguage Support | Can extract and interpret invoice information in multiple languages.       |
| Gemini 1.5 Flash Model| Utilizes the advanced AI capabilities of the Gemini 1.5 Flash model for accurate content generation based on the image and text inputs. |

## How It Works
1. **Setup Environment**: Handles API keys and sensitive information securely.
2. **User Interface**: Streamlit is used to create an interactive web application for users to upload invoice images.
3. **Image Analysis**: Processes uploaded invoice images and uses the Gemini 1.5 Flash model to extract and interpret data.

## Getting Started
Follow these instructions to set up and run the application.

### Prerequisites
- Python 3.8+
- Streamlit
- dotenv Python package
- PIL (Pillow for image processing)

### Installation
1. Clone the repository:
```bash
https://github.com/MorshedulHoque/Multilanguage-Invoice-Extractor-Gemini-Flash.git
```
2. Install dependencies:
```bash
pip install -r requirement.txt
```
3. Obtain a Google API key for the Gemini Pro model and add it to the .env file:
```bash
echo GOOGLE_API_KEY=your_api_key_here > .env
```
4. Run the Streamlit application:
```bash
streamlit run app.py
```

## Usage
-Open the application and navigate to the Streamlit-provided local URL.
![benchmark](https://github.com/MorshedulHoque/Multilanguage-Invoice-Extractor-Gemini-Flash/blob/main/images/Screenshot_1.png)
-Upload an invoice image using the file uploader.
![benchmark](https://github.com/MorshedulHoque/Multilanguage-Invoice-Extractor-Gemini-Flash/blob/main/images/Screenshot_2.png)
-Use the text input box to input any specific queries related to the invoice.
![benchmark](https://github.com/MorshedulHoque/Multilanguage-Invoice-Extractor-Gemini-Flash/blob/main/images/Screenshot_4.png)
-Click the "Tell me about the invoice" button to process the image and receive detailed information.
![benchmark](https://github.com/MorshedulHoque/Multilanguage-Invoice-Extractor-Gemini-Flash/blob/main/images/Screenshot_3.png)
![benchmark](https://github.com/MorshedulHoque/Multilanguage-Invoice-Extractor-Gemini-Flash/blob/main/images/Screenshot_5.png)

## Live Demo
Access the live demo here: [Live Demo](https://multilanguage-invoice-extractor-gemini.onrender.com/)

Note: The demo might experience latency as it is hosted on a free server.

## Acknowledgments
-Google AI for the Gemini language model.
-Streamlit for providing the framework for the web application.
-Pillow library for handling image data efficiently.

## Contributions
Contributions are encouraged! Please fork the project, make your changes, and submit a pull request for review.

## Contact
For any queries or suggestions, contact youremail@example.com.

## Version
This application is currently at version 1.0.
