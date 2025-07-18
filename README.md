# A Python/FastAPI project sample with Redis on a Docker container
This sample contains the completed program from the tutorial: [FastAPI in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-fastapi). Immediate steps are not included. 

## Run the app locally in VS Code
 
There are diffent ways you can run this app locally in VS Code depending on your operating system. To get started, first clone this project on your machine and then open it in VS Code (**File** > **Open Folder...**). 

### Windows
To run this app locally in VS Code on Windows, you can use either [WSL](https://learn.microsoft.com/en-us/windows/wsl/) (Windows Subsystem for Linux) or [Docker](https://www.docker.com/products/docker-desktop). 

#### Docker Containers
1. Make sure you have [Docker installed](https://www.docker.com/products/docker-desktop)
1. Install the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) 
1. Open the Command Palette in VS Code (**View** > **Command Palette...**) and run the "Dev Container: Reopen in Container" command.
1. Press **F5** to debug your application!

#### WSL
1. Make sure you have [WSL installed](https://learn.microsoft.com/en-us/windows/wsl/)
1. Install the [WSL extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl) for VS Code
1. Open the Command Palette in VS Code (**View** > **Command Palette...**) and run the "WSL: Reopen Folder in WSL" command
1. Follow the remaining steps for [macOS/Linux](#macos--linux) below.

### macOS / Linux

1. Install the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) for VS Code 
1. Run the "Python: Create Environment" command in the Command Palette
1. Select `Venv`, the latest available version of Python and then the `requirements.txt` file to install the dependencies.
1. Press **F5** to run your application!
