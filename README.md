# Study Buddy (SB Agent)

Study Buddy (SB Agent) is a web-based AI academic assistant built to provide structured learning support, intelligent query handling, and clearly formatted academic explanations.

The system combines a browser-based interface with a modular backend agent that processes queries using structured reasoning workflows.

---

## About the Project

Study Buddy is designed to assist students by transforming academic questions into well-organized, step-by-step responses.

The application focuses on:

* Clear explanation formatting
* Logical response structuring
* Modular system design
* Web-based accessibility

The architecture separates the interface from processing logic, ensuring clean design and future scalability.

---

## Core Capabilities

* Web-based academic assistant
* Structured reasoning and response formatting
* Step-by-step explanation generation
* Modular backend design
* Extensible workflow logic
* Scalable architecture for future enhancements

---

## Architecture Overview

The system follows a layered architecture:

**Frontend (Web Interface)**
Handles user interaction and displays responses.

**Agent Core**
Processes academic queries and applies reasoning workflows.

**Utility Modules**
Provide supporting functions and configuration management.

**Response Engine**
Formats structured outputs before rendering them in the browser.

This separation ensures maintainability, clarity, and ease of extension.

---

## Project Structure

```
SB_Agent-main/
│
├── agent/              Core reasoning and workflow logic
├── utils/              Supporting helper modules
├── config/             Configuration management
├── templates/          HTML templates (if applicable)
├── static/             CSS / JavaScript assets
├── main.py             Application entry point
├── requirements.txt    Project dependencies
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/SB_Agent-main.git
cd SB_Agent-main
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the application:

```bash
python main.py
```

Open your browser and navigate to:

```
http://localhost:5000
```

(Adjust the port if configured differently.)

---

## How It Works

1. A user submits an academic query via the web interface.
2. The backend agent interprets and processes the input.
3. Structured reasoning logic determines response organization.
4. The formatted academic output is rendered in the browser.

---

## Requirements

* Python 3.8 or higher
* Dependencies listed in `requirements.txt`

