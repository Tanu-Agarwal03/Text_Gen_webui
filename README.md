# Text_Gen_webui

Text-Gen- WEB UI  

Text Generation Web UI is a Gradio-based interface for running Large Language Models (LLMs) like LLaMA, llama.cpp, GPT-J, Pythia, OPT, and GALACTICA. It provides a user-friendly interface to interact with these models and generate text, with features such as model switching, notebook mode, chat mode, and more. 

Features: 

Multiple model backends: transformers, llama.cpp, ExLlama, AutoGPTQ, GPTQ-for-LLaMa, Vicuna, Alpaca, WizardLM, Koala, Falcon. 

Dropdown menu for quickly switching between different models 

LoRA: load and unload LoRAs on the fly, train a new LoRA using QLoRA 

Precise instruction templates for chat mode, including Llama-2-chat, Alpaca, Vicuna, WizardLM, StableLM, and many others 

4-bit, 8-bit, and CPU inference through the transformers library. 

It supports a variety of LLMs, including LLaMA, llama.cpp, GPT-J, Pythia, OPT, and GALACTICA. 

It provides a user-friendly interface to interact with these models, making it easy to generate text. 

It has features such as model switching, notebook mode, and chat mode, which make it more versatile. 

It is open source and can be customized to meet your needs. 

 

Steps for installation: 
git clone https://github.com/oobabooga/text-generation-webui.git 

conda create –n textgen python=3.10.10 

conda activate textgen 

python –m pip install –r requirements.txt 

python server.py --threads 8 

 

Following this you will be able to run it on your local machine. 
 

 

To run it follow the below given steps: 

Open collab 

Write the code to load the model 

Go to runtym->Change runtym type->T4 GPU 

Run the model 

 

 

NOTE: 

#if falcon model is selected then 

#Set "mode: 'instruct'" >> 

#set "instruction_template: 'Llama-v2'" >> 

 
 

 
#if falcon model is selected then 

#Set "mode: 'instruct'" >> 

#set "instruction_template: 'Wizard-Mega WizardLM'" >> 

 

 

 

 

 

 

 

Comparison of models: 

 

Model Name 

Response Time 

Accuracy 

Alpaca-13b 

Fast 

40% 

LLama2-Tb-Chat-GPTQ 

Fast 

90% 

Koala-13b-GPTQ 

Fast 

Inaccurate 

Vicuna-13b-GPTQ 

Fast and Detailed 

90% 

 

 
Conclusion: 
Text Generation Web UI is a powerful tool that can be used to generate text in a variety of ways. It is easy to use and can be customized to meet your needs. If you are interested in generating text using LLMs, then Text Generation Web UI is a great option. 

 
 

 
