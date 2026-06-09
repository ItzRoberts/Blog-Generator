# 📝 AI Blog Post Generator

An AI-powered Blog Post Generator built using Streamlit and Google Gemini API. Users can enter any topic, and the application generates a detailed blog post instantly using Generative AI.

## 🚀 Features

- Simple and user-friendly interface
- Generate blog content from any topic
- Powered by Google Gemini 2.5 Flash model
- Fast and interactive web application using Streamlit

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Generative AI (Gemini API)

## 📂 Project Structure

AI-Blog-Generator/
│
├── blog.py
├── README.md
└── requirements.txt


## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Blog-Generator.git
cd AI-Blog-Generator

2. Install Dependencies

Bash

pip install -r requirements.txt

3. Add Gemini API Key

Open blog.py and replace:

Python
Run

genai.configure(api_key="GIVE YOUR API KEY HERE")

with your Gemini API Key:

Python
Run

genai.configure(api_key="YOUR_API_KEY")

4. Run the Application

Bash

streamlit run blog.py

💡 How It Works

    Enter a topic in the input box.

    Click the Submit button.

    The application sends the topic to the Gemini AI model.

    Gemini generates a blog post based on the given topic.

    The generated content is displayed on the screen.

Example
Input

Artificial Intelligence in Healthcare

Output

A detailed blog discussing the applications, benefits, challenges, and future of Artificial Intelligence in Healthcare.
🔮 Future Enhancements

    Multiple blog writing styles

    Blog length selection

    Export to PDF/Word

    SEO-optimized content generation

    Image generation for blog posts

📜 License

This project is open-source and available under the MIT License.
👨‍💻 Author

Developed by Asir Roberts


### `requirements.txt`

```txt
streamlit
google-generativeai
