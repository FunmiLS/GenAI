# Generative AI

## Introduction

The code within this repository was created to gain hands-on experience with the OCI Gen AI service, explore and experiment with different chatbot functionalities and build a basic chatbot using Meta's Llama 2 model and Streamlit

## Files
- streamlit_chatbot.py (Streamlit chatbot)
- Oracle OCI Generative AI Professional.ipynb (Experimenting with OCI Generative AI service)

## 1. Create a basic Streamlit chatbot
### Required Packages
- streamlit
- replicate

## Prerequisites
- A replicate API key

## Instructions
1. Create an API key on Replicate (https://replicate.com/account/api-tokens)
2. Save streamlit_chatbot.py to computer
3. Open terminal and run the command
   
```ruby
streamlit run streamlit_chatbot.py
```

## Screenshots
![Screenshot 2024-07-03 161334](https://github.com/FunmiLS/GenAI/assets/111074004/91fc6cad-9286-4d2a-92d2-4720c848e67a)

![Screenshot 2024-07-03 161902](https://github.com/FunmiLS/GenAI/assets/111074004/52175c22-ac6a-4576-b6a0-33ad73eaedc4)




## 2. Jupyter Notebook - Experiment with OCI Generative AI service

### Required Packages
- oci
  
### Prequisities 
- Oracle Cloud Infrastructure tenant and a user account created in that tenant.

### Instructions

#### Set up your OCI config file (if not done so already)

1) Install Homebrew
Required as it will allow you to install OCI CLI.

Open your terminal and run the command:

```ruby
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2) Install OCI CLI
For Mac OS run the following command from your terminal:

```ruby
brew update && brew install oci-cli
```

Check the OCI CLI installation by verifying the version, run the command:


```ruby
oci --version
```
3) OCI CLI configuration
Login to your OCI account and save your OCID for your User and OCID for your Tenancy to a notepad.

```ruby
oci setup config
```
Then following the following steps:
ENTER > paste your OCID (user) > ENTER > paste your OCID (tenancy) > ENTER > type in your region > ENTER > Y > ENTER > ENTER > N/A > N/A

3) Add your OCI API Key

```ruby
cd .oci
```

```ruby
ls
```

Display your public key

```ruby
cat oci_api_key_public.pem
```
Copy your OCI public key.

In OCI, add a new API key.

Select Paste Public Key.

Paste your public key into the window.
