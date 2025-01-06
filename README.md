# AI Tutor Application
![AI Tutor Banner](assets/The Crest Logo.png)

An interactive learning platform powered by Google's Gemini AI.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Screenshots
![AI Tutor Interface](assets/screenshot.png)

## Features

### Student Information Collection
- Collects student name and grade/year before starting
- Information persists across sessions
- Used in reports and analytics

### Interactive Learning
- Ask questions on any topic
- Get clear explanations with examples
- Powered by Google's Gemini AI

### Quiz System
- Generate quizzes on any topic
- 5 multiple-choice questions per quiz
- Immediate feedback on answers
- Track performance over time

### Progress Dashboard
- View all quiz attempts
- See performance trends
- Expandable quiz details
- Visual progress charts

### Reporting Features
- Download PDF reports of quiz history
- Generate shareable links for progress reports
- Reports include:
  - Student information
  - Quiz topics and scores
  - Detailed question analysis

## Requirements
- Python 3.8+
- Streamlit
- Google Generative AI package
- FPDF for PDF generation

## Setup
1. Install requirements:
```bash
pip install -r requirements.txt
```

2. Get Google API key from [AI Studio](https://aistudio.google.com/)

3. Run the app:
```bash
streamlit run ai_tutor_app.py
```

## Usage
1. Enter your name and grade/year
2. Use the interactive learning section to ask questions
3. Generate quizzes on topics of your choice
4. View your progress and download reports
5. Share your progress with teachers/parents via generated links

## Development
- All changes are tracked in the memlog folder
- Student data is stored temporarily in memlog when generating shareable links
- PDF reports are generated on-demand and not stored permanently
- Follows [Semantic Versioning](https://semver.org/)
- Uses [Conventional Commits](https://www.conventionalcommits.org/) for commit messages
- CI/CD pipeline automatically runs tests and linters on push

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeatureName`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeatureName`)
5. Open a pull request

