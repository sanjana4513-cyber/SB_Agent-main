📘 Study Buddy (SB Agent)

Study Buddy (SB Agent) is an AI-powered academic assistant designed to support structured learning, enhance productivity, and provide intelligent academic guidance through a web-based interface. The system is built using a modular agent-based architecture that ensures scalability, maintainability, and extensibility.

Overview

Study Buddy enables students to submit academic queries through a web interface and receive structured, well-organized responses. The backend agent processes inputs using defined workflows and logical reasoning mechanisms to generate academically formatted outputs.

Key Features

Web-based interactive interface

Intelligent academic query processing

Structured and step-by-step explanations

Modular and extensible architecture

Configurable workflow logic

Scalable backend design

System Architecture

The system follows a layered architecture:

Frontend Layer – Handles user interaction via the web interface

Agent Core – Processes inputs and applies decision logic

Utility Layer – Supports helper functions and processing tools

Response Layer – Generates structured academic outputs

This separation of concerns ensures clean design and ease of future enhancements.

Project Structure
SB_Agent-main/
│
├── agent/              # Core Study Buddy logic and workflow engine
├── utils/              # Helper functions
├── config/             # Configuration settings
├── templates/          # HTML templates (if applicable)
├── static/             # CSS/JS assets (if applicable)
├── main.py             # Application entry point
├── requirements.txt    # Project dependencies
└── README.md           # Documentation
Installation
Clone the Repository
git clone https://github.com/your-username/SB_Agent-main.git
cd SB_Agent-main
Create a Virtual Environment
python -m venv venv

Activate the environment:

Windows

venv\Scripts\activate

macOS/Linux

source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
Running the Application

Start the application:

python main.py

After launching the server, open your browser and navigate to:

http://localhost:5000

(Adjust the port if configured differently.)

How It Works

The user submits an academic query via the web interface.

The backend agent interprets and processes the request.

Workflow logic determines the response structure.

A formatted academic output is generated and displayed in the browser.

Technical Requirements

Python 3.8 or higher

All dependencies listed in requirements.txt
