# ML Lab Exam Project

## Description
This repository contains the **ML Lab Exam Project** developed by **Shivangi Aggarwal**. The project showcases a machine learning solution that has been implemented using Python and related libraries. The repository includes Docker and Jenkins pipeline integration to ensure seamless deployment and CI/CD processes.

## Repository Structure

```
ML_Lab
|
|-- Dockerfile                  # Dockerfile for containerizing the application
|-- Jenkinsfile                 # Jenkins pipeline configuration
|-- ML_Lab_Exam_(Shivangi_Aggarwal).ipynb # Jupyter Notebook implementation of the ML project
|-- ml_lab_exam_(shivangi_aggarwal).py    # Python script implementation of the ML project
|-- requirements.txt            # List of dependencies required for the project
|-- README.md                   # Documentation of the repository
```

## Features
- Implementation of a machine learning model to solve a specific problem.
- Modular and structured code written in Python.
- Integration with **Docker** for containerization and deployment.
- CI/CD pipeline integration using **Jenkins**.

## Getting Started

### Prerequisites
Ensure you have the following installed on your system:
- Python 3.9 or later
- Docker
- Pip (Python package manager)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ShivangiAggarwal07/Ml_Lab.git
   cd Ml_Lab
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
#### Running Locally
1. Run the Python script directly:
   ```bash
   python ml_lab_exam_(shivangi_aggarwal).py
   ```
2. Alternatively, open the Jupyter Notebook file:
   ```bash
   jupyter notebook ML_Lab_Exam_(Shivangi_Aggarwal).ipynb
   ```

#### Running with Docker
1. Build the Docker image:
   ```bash
   docker build -t ml_lab_project .
   ```
2. Run the Docker container:
   ```bash
   docker run -p 5000:5000 ml_lab_project
   ```

#### Jenkins Integration
The repository contains a `Jenkinsfile` to automate the build and deployment process. Ensure you have a Jenkins instance set up and configured for pipeline execution.

## Dependencies
The project relies on the following Python libraries:
- `kagglehub`
- Other dependencies are listed in the `requirements.txt` file.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Submit a pull request.


## Contact
For any inquiries or issues, please contact **Shivangi Aggarwal** at [shivangiagg07@gmail.com].

