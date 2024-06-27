# POC classes Dev Container 

This project sets up a development environment using Visual Studio Code's Dev Containers extension with Python 3.12, OpenCV, Matplotlib, NumPy, and Jupyter Notebooks.

## Setup Instructions

### Prerequisites

- **Docker Desktop**: [Download and Install](https://www.docker.com/products/docker-desktop)
- **Visual Studio Code**: [Download and Install](https://code.visualstudio.com/)
- **Dev Containers Extension**: Install from the Extensions view (`Ctrl+Shift+X`) in VS Code
- **Git**: [Download and Install](https://git-scm.com/downloads)

#### Installing Git

- **Windows**: [Download Git for Windows](https://gitforwindows.org/) and follow the installation instructions. This also provides a Git Bash terminal, which can be useful.
- **Mac**: Git can be installed via Homebrew (`brew install git`) or by downloading it from the [official site](https://git-scm.com/download/mac).
- **Linux**: Use your distribution's package manager, e.g., `sudo apt-get install git` for Debian-based distributions.

### Steps

1. **Clone the Repository and Open in Container**:
    - Open Visual Studio Code.
    - Press `F1` to open the Command Palette.
    - Type `Dev Containers: Clone Repository in Container Volume` and select it.
    - Enter the URL of this repository: `https://github.com/bmuczynski/POC_env`.
    - Choose a location for the container volume.

2. **Wait for the Container to Build**:
    - VS Code will clone the repository and build the Docker image as defined in the `Dockerfile`.
    - Once the container is built, VS Code will open the project within the container environment.
