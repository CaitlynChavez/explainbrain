# Toward the Trusted Medical Imaging AI: An Explainable Machine Learning Model for Schizophrenia Brain MRIs
Official repository for ExplainBrainROI Paper
##  📰 News

 - **[2024.12.10]** :tada: Initial release of the App and Complete Model!



ExplainBrainROI - Streamlit Application
This project provides a Streamlit application for brain region analysis with FSL support, packaged in a Docker environment. Follow the instructions below to set up and run the application.

### System Requirements

- Docker: Install Docker from Docker's official website.
- 
```bash
git clone <repository_url>
cd <repository_directory>
```
Build the Docker Image

To build the Docker image, run the following command in the root directory of the cloned repository:
```bash
docker build -t explainbrainroi .
```
This command will:

Download and install FSL.
Set up Python 3.9 with necessary libraries.
Configure the environment for running the Streamlit application.
Run the Docker Container

Start the Docker container with the following command:

```bash
docker run -p 8501:8501 explainbrainroi
```


## Model

| Model         | Model Name            | Inference | Model Size (MB)  | 
|---------------|-----------------------|----------------------------------|:-------------------------:|
| RandomForest  | `SPR_model`      | ✅        | 4.8MB      |           









