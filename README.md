# Dev Container Project

This project sets up a development environment using Visual Studio Code's Remote - Containers extension with Python 3.12, OpenCV, Matplotlib, NumPy, and Jupyter Notebooks.

## Setup Instructions

### Prerequisites

- Docker Desktop: [Download and Install](https://www.docker.com/products/docker-desktop)
- Visual Studio Code: [Download and Install](https://code.visualstudio.com/)
- Remote - Containers Extension: Install from the Extensions view (`Ctrl+Shift+X`) in VS Code

### Steps

1. **Open Visual Studio Code**.
2. **Clone the Repository and Open in Container**:
    - Press `F1` to open the Command Palette.
    - Type `Remote-Containers: Clone Repository in Container Volume` and select it.
    - Enter the URL of this repository: `https://github.com/yourusername/devcontainer-project`.
    - Choose a location for the container volume.

VS Code will handle the rest by building the Docker image and starting the container. Once the container is running, you can start coding right away.

### Access Jupyter Notebooks

To use Jupyter Notebooks, open a new terminal inside VS Code (`Ctrl+Shift+`), and run:

```bash
jupyter notebook --ip=0.0.0.0 --no-browser --allow-root
