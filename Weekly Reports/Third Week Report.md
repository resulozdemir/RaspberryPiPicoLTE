# Week 3 Report

## Tasks and Progress Status

### 1. Development Environment Setup
- Initiated by reading the Developer Guideline.
- Created a HiveMQ Cloud Broker account.
- Created a new branch from the GitHub repository.
- Installed Black Formatter 
- Set up a virtual environment using venv.

    ```Bash
    python3 -m venv hivemq           //for creating virtual environment
    source hivemq/bin/activate       //for activating virtual environment
    

### 2. Code Examination and Learning
- Reviewed `aws.py`, `azure.py`, `auth.py`, and `ssl.py`.
- Learned about SSL and its importance in secure communications.

### 3. Practical Application and Configuration
- Downloaded the necessary CA certificate for SSL configuration.
- Configuring `config.json` before writing the app for HiveMQ Cloud.

### Project Insights
- It was learned that the HiveMQ Cloud Serverless package does not support user certificates.

![hivemq cloud plans](<Photos/hivemq cloud plans.png>)

### References
- [HiveMQ Cloud - CA Certificate](https://community.hivemq.com/t/frequently-asked-questions/514/1)
- [HiveMQ User Certificate Community Conversation](https://community.hivemq.com/t/need-certificate-to-achieve-ssl-connexion/1387)