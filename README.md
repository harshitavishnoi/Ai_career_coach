# Ai_career_coach
# A Career Recommender Chatbot

## Overview

This project is a Career Recommender Chatbot that uses the GradientAI platform for fine-tuning  LLaMA 2(a language model) using Gradient to suggest career paths based on user input.

## Requirements

- Python 3.6 or higher
- GradientAI library (`gradientai`) version 1.7.0
- python pandas
- google colab
- google drive
- gradient.ai

## Setup

1. Install the required packages:

    ```bash
    pip install gradientai --upgrade
    ```

2. Set up Google Colab and mount your Google Drive.

3. Set the Gradient environment variables:

    ```python
    import os

    os.environ['GRADIENT_ACCESS_TOKEN'] = 'your-gradient-access-token'
    os.environ['GRADIENT_WORKSPACE_ID'] = 'your-gradient-workspace-id'
    ```

4. Define the path to your dataset:

    ```python
    data_path = '/content/drive/MyDrive/my_projects/datasets/truncated_career_recommender_dataset.csv'
    ```

## Usage

1. Load and format the dataset:

    ```python
    # Load and format the data
    ```

2. Initialize and fine-tune the model:

    ```python
    # Initialize the gradient
    # Fine-tune the model
    ```

3. Make predictions with the trained model:

    ```python
    # User query example
    user_query = "Interests: designing, Skills: java, Degre: B.Sc in Computer Science, Working: No"
    formatted_query = f"### User Data: \n{user_query}\n\n### Suggested Career Path"
    response = new_model_adapter.complete(query=formatted_query, max_generated_token_count=100)
    print(f"> {user_query}\n> {response.generated_output}")
    ```

Feel free to customize this template based on your project's specific details and add sections as needed.
