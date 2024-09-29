# News AI Agent Using CrewAI and Google Gemini Pro LLM

## Overview

The News AI Agent is an innovative application designed to explore and report on groundbreaking technologies, particularly in the healthcare sector. This project leverages the capabilities of CrewAI and the Google Gemini Pro Language Model to automate research and writing tasks, producing insightful narratives that simplify complex topics for a wider audience.

## Features

- **Research Agent**: An intelligent agent that uncovers significant trends and technologies in specified domains.
- **Writing Agent**: A creative agent that crafts engaging narratives based on research findings.
- **Modular Design**: Easily customizable agents and tasks, enabling a variety of use cases beyond healthcare.
- **Internet Searching**: Utilizes the Serper API for real-time internet searching capabilities.
- **Sequential Processing**: Tasks can be executed in a defined order to maintain workflow integrity.

## Technologies Used

- **CrewAI**: A framework for building and managing intelligent agents.
- **Google Gemini Pro LLM**: A powerful language model for generating human-like text and understanding context.
- **Serper API**: Enables real-time internet searching to gather the latest information.
- **Python**: The primary programming language for the implementation.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dinesh-gaire/News-AI-agent-using-crewAI-and-Google-Gemini-Pro-LLM.git
   cd News-AI-agent-using-crewAI-and-Google-Gemini-Pro-LLM
    ```

2. **Set up a virtual environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```
4. **Set up environment variables**: Create a .env file in the root directory and add your API keys:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key_here
    SERPER_API_KEY=your_serper_api_key_here
    ```
## Usage
To execute the News AI agent, run the following command:

    python crew.py

You can specify the topic of interest by modifying the inputs parameter in the script. For example, to explore AI in healthcare:

    result = crew.kickoff(inputs={'topic': 'AI in healthcare'})
    
## Writing Task
The writing task is defined in tasks.py and involves composing an insightful article on the specified topic. The expected output is a four-paragraph article formatted as markdown, focusing on the latest trends and their impact on the industry.

## Example Output
The system will generate a comprehensive report detailing the latest trends and technologies in the specified topic area, saved in `new-blog-post.md`.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## Acknowledgments
Thanks to the developers of CrewAI and Google Gemini Pro LLM for their amazing tools and libraries.
Special thanks to the Serper API for enabling real-time information gathering.
Thanks to the open-source community for their invaluable contributions.
