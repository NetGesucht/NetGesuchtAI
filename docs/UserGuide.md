
# NetGesucht AI - User Guide

## Chat (Conversations)

![image](images/chat.png)

### Selecting Model to Download and Activate

Press to show the menu

![image](images/select_model_popup.png)

A list with the available models will show up.

Depending on the amount of memory available it will enable selecting and downloading the model that will fit in the available memory, the others will be grayed out.

The actually selected model have a checkmark.

Downloaded models are marked with an arrow pointing down.

![image](images/select_model.png)

When selected a model that has not been downloaded yet, it will prompt the user to download the model.

![image](images/select_model_download.png)

### Save Conversation

Conversations are not automatically saved, they need to be explicitely saved and a name has to be assigned.

![image](images/conversation_save.png)

### Clean Conversation

The conversation canvas can be cleaned up.

![image](images/conversation_delete.png)

## Configuration

![image](images/configuration.png)

### Device Information

![image](images/device_information.png)

IP Address: use this address to connect to the device when the API Server has been enabled.

### Settings

![image](images/settings.png)

#### Function Calling

When enabled, use the model Llama 3.2 3B, it is the only model with robust function calling support. 

It is not perfect, it depened on the prompt and the script name, description and arguments description.

#### API Server

When enabled you can connect to the device to the assigned port, by default 11434.

Compatible with Ollama API as documented by Ollama and works with the official python library. 

Endpoints:

 - / (this returns "Ollama is running")
 - /api/generate
 - /api/chat
 - /api/tags

Some apps don't implement their clients following the oficial protocol description, some of them have also been implemented.

It also has a very basic OpenAI API support for the following endpoints:

- /v1/models
- /v1/chat/completions
- /v1/embeddings

#### System Prompts

If enabled it will use the activated System Prompt.

#### Debug Mode

There are two logs, an application debug log, which contains all the application sessions, and the application session log.

When enabled it will keep visible the debug window at Agent Workflow canvas, which will display the application session since the app has been executed.

The applicaiton log can be exported. When deleting both logs will be removed.

![image](images/debug_logs_options.png)

### Downloaded Models

List of the models which have been downloaded.

![image](images/downloaded_models.png)

These models could be deleted by swiping to the left.

![image](images/delete_model.png)

### Saved Conversations

Here are located the conversations saved in the Chat view, which can be removed by sliding to the left and pressing the red trash icon.

![image](images/saved_conversations.png)

### System Prompts

The script name and the function name *must* be the same.

### Scripts - Function Calling Tools

## Agent Workflows

![image](images/agent_workflows.png)

### Start Node

### Agent Node

### Tool Node

### End Node

### Connections

