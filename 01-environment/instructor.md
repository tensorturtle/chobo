# 01-environment for Instructor

## How to set up a simple JupyterHub server

Scenario: I have a GPU workstation, and I want to let a student run GPU-accelerated jupyter notebooks on it.

I will use [The Littlest JupyterHub](https://tljh.jupyter.org/en/latest/install/custom-server.html)

To pre-install pip packages like PyTorch, start a new Terminal (from admin account), Create a `requirements.txt` file like this:

```
torch==1.10.0+cu113
torchvision==0.11.1+cu113
torchaudio==0.10.0+cu113
```

Then run `sudo -E pip3 install -r requirement.txt` to install for all users.

