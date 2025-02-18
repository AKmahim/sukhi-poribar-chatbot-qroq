# Sukhi Poribar Llama 8b

This project, **Sukhi Poribar llama-8b**, aims to develop an AI-powered chatbot designed for the IEM-run Shukhi Poribar national call center under the Directorate General of Family Planning (DGFP), Bangladesh. The chatbot, created under the USAID-funded "Breakthrough ACTION" project, provides guidance on family planning, health services, and social behavior change (SBC) communication. By leveraging NVIDIA's NeMo framework, this chatbot delivers accurate, conversational, and culturally tailored responses in Bangla, enhancing communication efficiency for call center agents.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [License](#license)

## Project Overview

The Sukhi Poribar Mistral-NeMo chatbot assists call center agents in managing public inquiries related to family planning and health services. It aims to:
- Improve the efficiency and accuracy of public health communication in Bangladesh.
- Facilitate timely responses by automating query handling for the call center.
- Provide agents with a reliable, conversational tool to interact with users in Bangla.

## Features

- **Conversational Interface**: AI-based chatbot with natural language processing for Bangla.
- **Family Planning Guidance**: Provides answers and guidelines on family planning and general healthcare.
- **User Authentication**: Login/signup functionality with user verification.
- **Troubleshooting Mechanism**: Built-in diagnostics to help stakeholders monitor and improve bot performance.

## Technologies Used

- **NeMo**: NVIDIA’s NeMo framework for building and training conversational AI models.
- **Mistral Model**: Pre-trained language models fine-tuned for Bangla.
- **Python**: Core programming language for backend development.
- **TensorFlow/Keras**: Used for building and training machine learning models.
- **Flask**: Web framework to handle backend and API integration.
- **React**: Frontend framework for the chatbot’s user interface.

## Setup and Installation

### Prerequisites
- Python 3.8+
- [Git](https://git-scm.com/)
- [NVIDIA NeMo](https://github.com/NVIDIA/NeMo)
- [TensorFlow](https://www.tensorflow.org/)

### Clone the Repository

```bash
git clone 
cd Sukhi-Poriba


### Setup Environment

1. **Create a Virtual Environment**: I am using Python 3.10.12 currently    <br> windows: ```python -m venv env_name``` <br> linux: ```python3 -m venv env_name```
 
2. **Activate virtual environment:** <br> windows:  ```.\env_name\Scripts\activate``` (you need to disable shell script warning first using ```Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass``` ) <br> Linux: ```source env_name/bin/activate```

3. **Upgrade pip**: ```pip install --upgrade pip```

4. **Set Execution policy for windows shell not need for linux** : ```Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass```

5. **Install Requirements**: ```pip install -r requirements.txt``` 

6. **Set Google Gemini API key on env file**

7. **Enter commands in terminal**:  ```python app.py```
8. **Deactivate env :**  ```deactivate```

