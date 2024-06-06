### Using the following commands to run the files
1. make sure the Docker is running and the python version is 3.11
2. pip install litellm && pip install pyautogen
3. pull the models using ollama pull <model>
4. litellm --model ollama/mistral && litellm --model ollama/codellama
5. ollama serve
6. Copy the running ports to the corresponding config_list
7. Change the prompts as you wish to
8. run the program and it should be working
