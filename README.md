# Azure_AI_Language_AudioChatApp
Use the Using Phi-4-multimodal-instruct generative AI model to generate responses to prompts that include audio files

1. Set up model in Azure AI Foundry
2. Create client application (use Azure AI Model Inference SDKs)

# From Azure Portal (cloud shell)
1. rm -r mslearn-ai-audio -f
    git clone https://github.com/MicrosoftLearning/mslearn-ai-language

2. cd mslearn-ai-language/Labfiles/09-audio-chat/Python

3. python -m venv labenv
./labenv/bin/Activate.ps1
pip install -r requirements.txt azure-identity azure-ai-projects openai

4. code .env

# Login to Azure 
1. az login 
- Note: This will ask you to log in again at https://microsoft.com/devicelogin if using the Microsoft Azure CLI 
