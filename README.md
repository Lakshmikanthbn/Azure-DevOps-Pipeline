# Sentiment Analysis Azure DevOps Pipeline

This repository contains a simple Python application for sentiment analysis along with an Azure DevOps pipeline configuration to automate its execution.

## Project Structure

- `src/sentiment_analysis.py`: Python script that performs sentiment analysis using TextBlob.
- `src/requirements.txt`: List of dependencies required for the Python script.
- `.azure-pipelines/azure-pipelines.yml`: Azure DevOps pipeline configuration file.

## Setup

1. **Clone the Repository**:
    ```bash
    git clone <your-repository-url>
    cd sentiment-azure-devops-pipeline
    ```

2. **Configure Azure DevOps Pipeline**:
   - Go to your Azure DevOps project.
   - Navigate to Pipelines and create a new pipeline.
   - Use the `azure-pipelines.yml` file from this repository.

3. **Run the Pipeline**:
   - The pipeline will automatically trigger on changes to the `main` branch.
   - It sets up Python, installs dependencies, and runs the sentiment analysis script.

## Usage

1. **Update the Script**:
   - Modify `sentiment_analysis.py` to analyze different texts or integrate with other data sources.

2. **Push Changes**:
   - Commit and push your changes to trigger the Azure DevOps pipeline.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
