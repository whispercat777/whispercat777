- In this project, chatgpt dialogue robot in rasa is used to achieve the task we want to complete by designing a reasonable prompt and then get a logical and perfect answer we want.
  
- first type "rasa train" in your terminal（you need to activate your virtual environment first）
  During the training process, Rasa will process training data, configuration files, and NLU models, and train a model that can be used for dialogue management and natural language understanding. After training is complete, you will receive a model folder containing all the training results in the working directory.

- "rasa run actions" (run in the same terminal)
  Until the terminal shows the figure
   ![image](https://github.com/whispercat777/whispercat777/assets/142243122/7ae07e92-51b5-4587-97af-1b11926aa62f)
  This command is used to run the Rasa action server in a terminal. The Rasa action server is responsible for executing actions within the Rasa dialogue flow. These actions can include sending requests to external APIs, executing custom code, or interacting with databases, among other tasks.
  (you can end this by Pressing ctrl+c twice in a row)

- "rasa shell --endpoints endpoints.yml" (run in another terminal)
  By specifying the endpoints.yml file, you can configure the endpoints used by Rasa, such as setting the address and port of the action server. Once the chat terminal is launched, you can interact with the trained Rasa model, asking it questions and viewing its responses.

- then you are able to talk to your robot,you can input your intent to get its answer.
- you can also stop by typing"/stop"

- （We can use vscode/pycharm or cmd's terminal）
