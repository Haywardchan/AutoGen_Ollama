### Using the following commands to run the files
1. make sure the Docker is running and the python version is 3.11
2. pip install litellm && pip install pyautogen && pip install "litellm[proxy]"
3. pull the models using ollama pull <model>
4. run the litellm with your configurated models
5. litellm --model ollama/mistral
6. litellm --model ollama/codellama
7. ollama serve
8. Copy the running ports to the corresponding config_list
9. Change the prompts as you wish to
10. run the program and it should be working
