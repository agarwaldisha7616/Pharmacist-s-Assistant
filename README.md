# 📋 Medical Prescription Parsing Application

Welcome to the **Medical Prescription Parsing** project! This web application leverages AI to accurately transcribe handwritten medical prescriptions into structured data.

## 🌟 Features

- **Image Upload:** Supports PNG, JPG, and JPEG formats.
- **Data Extraction:** Retrieves patient and doctor details, prescription date, medications, and additional notes.
- **User-Friendly Display:** Presents extracted data in a clear and organized format.

## 🛠️ Technologies Used

- **Python**
- **Streamlit** for the web interface
- **Langchain** for AI model integration
- **OpenAI's GPT-4** for image processing
- **Pydantic** for data validation
- **Pandas** for data manipulation

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- OpenAI API Key

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```
2.  **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set Up Environment Variables:**
   **Create a .env file and add your OpenAI API key:**
   ```bash
   OPENAI_API_KEY=your-api-key
   ```

###Usage

1. **Run The Application:**
   ```bash
   streamlit run main.py
   ```
2. **Upload a Prescription Image:
   **use the web interface to upload an image

3. **View Extracted Information:**
   **The application will display the parsed data.**
   
