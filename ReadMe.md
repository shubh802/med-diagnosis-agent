
# AI-Powered Healthcare Assistant

Welcome to the **AI Healthcare Assistant**, a Streamlit-based application leveraging advanced AI models to provide preliminary medical diagnoses and personalized treatment plans.

## Features

- **User-Friendly Interface**: Input patient information, including symptoms and medical history.
- **AI Diagnosis**: Utilize state-of-the-art AI agents for symptom analysis.
- **Treatment Recommendations**: Receive personalized treatment plans based on the diagnosis.
- **Downloadable Reports**: Export diagnosis and treatment plans as a Word document.

## Installation and Setup

Follow these steps to set up the project in your local environment using Conda:

### Prerequisites

Ensure you have the following installed:
- [Conda](https://docs.conda.io/en/latest/miniconda.html)
- [Python 3.10+](https://www.python.org/)

### Step 1: Clone the Repository

```bash
$ git clone https://github.com/your-repo/ai-healthcare-assistant.git
$ cd ai-healthcare-assistant
```

### Step 2: Create and Activate Conda Environment

```bash
$ conda create -n healthcare_env python=3.10 -y
$ conda activate healthcare_env
```

### Step 3: Install Dependencies

Install the required Python libraries:

```bash
$ pip install -r requirements.txt
```

### Step 4: Set Up Environment Variables

Create a `.env` file in the project root and add your API keys:

```
OPENAI_API_KEY=your_openai_api_key
SERPER_API_KEY=your_serper_api_key
```

### Step 5: Run the Application

Start the Streamlit app:

```bash
$ streamlit run app.py
```

The application will be accessible at `http://localhost:8501`.

## Usage

1. Open the app in your browser.
2. Enter patient information, including gender, age, symptoms, and medical history.
3. Click on the **"Get Diagnosis and Treatment Plan"** button.
4. View the diagnosis and treatment plan in the app.
5. Download the plan as a Word document if needed.

## Project Structure

```
ai-healthcare-assistant/
├── app.py                  # Main Streamlit application file
├── requirements.txt        # Python dependencies
├── .env.example            # Example environment variables file
├── README.md               # Project documentation
```

## Dependencies

The project uses the following key libraries:

- `streamlit`: For creating the web interface.
- `crewai`: For managing AI agents and tasks.
- `crewai_tools`: For search and web scraping tools.
- `langchain_openai`: For interacting with OpenAI models.
- `python-dotenv`: For loading environment variables.
- `python-docx`: For generating Word documents.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Happy diagnosing with the **AI-Powered Healthcare Assistant**! 🚑
