## Streamlit Apps on Snowflake

Welcome to the repository for Streamlit applications deployed on Snowflake! This README file will guide you through the setup, development, and deployment processes.

**Table of Contents**

- Overview
- Features
- Requirements
- Installation
- Usage
- Deployment
- Contributing
- Acknowledgements
- Overview

This repository contains a collection of Streamlit applications that leverage Snowflake as the backend database. Streamlit is an open-source app framework for Machine Learning and Data Science projects, while Snowflake is a cloud-based data warehousing service. Together, they enable the creation of interactive and data-driven web applications.

**Features**

Interactive web applications built with Streamlit.
Seamless integration with Snowflake for data storage and retrieval.
Easy deployment process to Snowflake.
Modular code structure for easy extension and maintenance.

**Requirements:-**

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher
- Streamlit
- Snowflake Connector for Python
- Snowflake Account
- Git Installation

Clone the repository:
```bash
 git clone https://github.com/Shankar-Reddy-S/Streamlit_snowflake.git
 cd Streamlit_snowflake
```
### Create a virtual environment: 

```bash
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```

### Install the required packages:

```bash
pip install -r requirements.txt
Set up Snowflake credentials:
```
### Create a .env file in the root directory of the repository and add your Snowflake credentials:

```plaintext
SNOWFLAKE_ACCOUNT=<your_account>
SNOWFLAKE_USER=<your_username>
SNOWFLAKE_PASSWORD=<your_password>
SNOWFLAKE_WAREHOUSE=<your_warehouse>
SNOWFLAKE_DATABASE=<your_database>
SNOWFLAKE_SCHEMA=<your_schema>
Usage
```
### Run the Streamlit application:
```bash
streamlit run app.py
```
Open your browser and go to http://localhost:8501 to view the application.

### Deployment

To deploy your Streamlit application to Snowflake, follow these steps:

1. **Prepare your Streamlit application for deployment:**
Ensure your application script (app.py) is ready for deployment, with all necessary configurations and dependencies included.

2. **Upload your Streamlit application to Snowflake:**
Use Snowflake's Snowpark or other deployment methods to upload your Streamlit application code.

3. **Configure Snowflake to run the Streamlit application:**
Set up the necessary Snowflake compute resources (e.g., warehouses) and permissions.

4. **Access your deployed application:**
Access your Streamlit application through the configured Snowflake endpoint or interface.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature-branch).
- Open a pull request.


Acknowledgements

Streamlit
Snowflake
Python
