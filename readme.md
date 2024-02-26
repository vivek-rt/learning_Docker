# Project Setup Guide

This guide will help you set up your environment, download and run the `requirements.txt` file, and execute the necessary commands to get your Rasa project up and running.

## Prerequisites

- Python  3.7 or later
- Pip (Python package installer)

## Step  1: Setting Up Your Environment

1. **Create a Virtual Environment (Optional but Recommended):**

   It's a good practice to create a virtual environment for your project to manage dependencies effectively.


2. **Install Rasa:**

   Before proceeding, ensure you have Rasa installed. If not, you can install it using pip:


## Step  2: Downloading and Installing Dependencies

1. **Clone the Repository:**

   If you haven't already, clone the project repository to your local machine.


2. **Install Requirements:**

   Run the following command to install the dependencies listed in the `requirements.txt` file:


## Step  3: Running the Project

1. **Run the Action Server:**

   Start the Rasa action server, which will handle custom actions.


2. **Run the Rasa Server:**

   Start the Rasa server to serve your model and handle requests.


The `--enable-api` flag enables the Rasa API, and `--cors "*"` allows any origin to access your server, which is useful for development but should be configured more restrictively for production environments.

## Additional Information

- **Documentation:** For more detailed information, refer to the [Rasa documentation](https://rasa.com/docs/).
- **Community:** Join the [Rasa community](https://community.rasa.com/) for support and to connect with other developers.

