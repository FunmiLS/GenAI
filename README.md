# Generative AI

## Introduction

The code within this repository was created to gain hands-on experience with the OCI Gen AI service, explore and experiment with different chatbot functionalities and build a basic chatbot using Meta's Llama 2 model and Streamlit

## Files
- Oracle OCI Generative AI Professional.ipynb (Experimenting with OCI Generative AI service)
- streamlit_chatbot.py (Streamlit chatbot)

## Python File - Creating a basic Streamlit Chatbot
### Required Packages
- streamlit
- replicate

## Prerequisites
- A replicate API key

## Instructions
1. Create an API key on Replicate (https://replicate.com/account/api-tokens)
2. Save Python file to computer
3. Open terminal and run the command
   
```ruby
streamlit run streamlit_chatbot.py
```

## Jupyter Notebook - Experimenting with OCI Generative AI service
### Prequisities 
Package: OCI
Oracle Cloud: Oracle Cloud Infrastructure tenant and a user account created in that tenant.

### Set up steps

1) Install Homebrew
Required as it will allow you to install OCI CLI.

To install Homebrew, open your terminal and run the following command:

```ruby
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2) Install OCI CLI
For Mac OS run the following command from your terminal:

```ruby
brew update && brew install oci-cli
```

Check the OCI CLI installation by verifying the version, run the following command:


```ruby
oci --version
```
3) OCI CLI configuration

