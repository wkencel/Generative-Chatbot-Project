# Generative Chatbot Project

**Course**: Applied Artificial Intelligence Program, AAI-520  
**Institution**: University of San Diego (USD)

## Project Status
Status: **Active**

## Installation
To use this project on your machine, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/Generative-Chatbot-Project.git
    cd Generative-Chatbot-Project
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows, use `env\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the project**:
    ```bash
    jupyter notebook
    ```
    Open the relevant notebook in your browser.

## Project Intro/Objective
The main purpose of this project is to create a chatbot that leverages deep learning models to have coherent and context-aware conversations. This chatbot aims to simulate human-like dialogue and can be used in various applications such as customer service, personal assistants, or education tools, showcasing the relevance and impact of natural language processing in real-world scenarios.

## Partner(s)/Contributor(s)
- Gurleen
- Jay
- Will

## Methods Used
- Natural Language Processing (NLP)
- Machine Learning
- Deep Learning
- Data Visualization
- Cloud Computing

## Technologies
- Python
- TensorFlow / PyTorch
- Jupyter
- HTML / JavaScript (for web interface)
- SQL

## Project Description
### Dataset
We are using the **Cornell Movie Dialogs Corpus**. The dataset includes a rich collection of movie character dialogues, providing a robust basis for training and evaluating our generative chatbot models.

### Data Preprocessing
The preprocessing steps include:
- **Cleaning**: Removing unwanted characters, handling missing data, and normalizing text.
- **Tokenization**: Splitting text into meaningful units (tokens).
- **Handling Different Languages**: Although our dataset is primarily in English, preparation for multi-language support can be included.
- **Context Management**: Structuring dialogues to handle multi-turn conversations effectively.

### Models
We will experiment with different generative-based architectures including:
- Seq2Seq models
- Transformer models
- GPT (Generative Pre-trained Transformer)

### Evaluation
Our evaluation will involve:
- Implementing metrics like BLEU and ROUGE.
- Comparing models based on performance metrics.
- Gathering user feedback to assess response quality.

### Challenges
- Ensuring context-aware conversations.
- Handling ambiguous queries effectively.
- Training models for coherent and contextually relevant responses.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
We would like to thank our professors and teaching assistants for their guidance and support throughout this project.
