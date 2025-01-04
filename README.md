# Setup ComfyUI on Apple Silicon Mac

## Setup

- Install uv: <https://docs.astral.sh/uv/getting-started/installation/>
- Clone repo
    ```bash
    git clone https://github.com/ringsaturn/silicon-comfyiui.git
    ```
- Clone submodule
    ```bash
    git submodule update --init --recursive
    ```
- Install dependencies
    ```bash
    uv sync
    ```
