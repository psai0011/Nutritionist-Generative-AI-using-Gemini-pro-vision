# Nutritionist-Generative-AI-using-Gemini-pro-vision

## Calories Advisor App
This is a **Streamlit**-based web application that utilizes **Google's Gemini Pro Vision API** to analyze food images and estimate total calorie intake. The app provides detailed nutritional breakdowns and assesses the overall healthiness of the food.

## Features
- Upload an image of food items
- AI analyzes the image and identifies food items
- Calculates total calorie intake per item
- Provides a nutritional breakdown (carbohydrates, fats, fibers, sugar, etc.)
- Determines if the food is healthy

## Tech Stack
- **Python**
- **Streamlit**
- **Google Generative AI (Gemini 1.5 Flash)**
- **PIL (Pillow) for image handling**
- **dotenv for environment variable management**

## Installation
1. Clone the repository:
   ```bash
   git clone (https://github.com/psai0011/Nutritionist-Generative-AI-using-Gemini-pro-vision/tree/main)
   cd Nutritionist-Generative-AI-using-Gemini-pro-vision
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your environment variables:
   - Create a `.env` file in the root directory.
   - Add your Google API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

## Usage
Run the Streamlit app:
```bash
streamlit run app.py
```

## Acknowledgment
Powered by **Google Generative AI (Gemini)** for AI-based food analysis.

