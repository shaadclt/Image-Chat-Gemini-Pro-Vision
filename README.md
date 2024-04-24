# Chat with Image using Gemini Pro Vision

![image-chat](https://github.com/shaadclt/Image-Chat-Gemini-Pro-Vision/assets/98437584/eb25de6a-8273-4c50-987a-71c3923a3676)

This Streamlit application allows users to chat with an image using Google's Generative AI, Gemini Pro Vision. Users can upload an image and enter a prompt, and the application will generate a response based on the image and prompt.

## Getting Started
1. Clone this repository:
```Bash
git clone https://github.com/shaadclt/Image-Chat-Gemini-Pro-Vision.git
```
2. Install required dependencies:
```Bash
pip install -r requirements.txt
```
3. Create a file named .env in the root directory of the project. Add your Google Cloud API key to the .env file with the following variable name:
GOOGLE_API_KEY=<YOUR_API_KEY>

4. Run the application:
```Bash
streamlit run app.py
```

## Features
- Upload an image
- Enter a prompt
- Generate a response based on the image and prompt using Gemini Pro Vision

## How it Works
- The application loads the streamlit, dotenv, PIL, and google.generativeai libraries.
- It uses dotenv to load the Google Cloud API key from the .env file.
- It configures the Gemini Pro Vision model using the API key.
- It defines a function gemini_vision_response that takes the model, prompt, and image as input and returns the generated text response.
- The Streamlit app sets the page title, icon, and layout.
- It allows users to upload an image and enter a prompt.
- When the user clicks the "Submit" button, it opens the uploaded image in one column and displays the generated response in the other column.
- It uses a custom function set_bg_from_url to set a background image for the application.

## Customization
- You can change the background image URL in the set_bg_from_url function.

## License
This project is licensed under the MIT License.

## Contact
Feel free to create issues or pull requests on this repository.

