# Predictive Analytics 2025/26

## Setting things up
First, we will install `uv` - a Python package and project manager. To download it run the following commands:
```zsh
curl -LsSf https://astral.sh/uv/install.sh | sh
```
on macOS and Linux, or:
```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```
on Windows.

Now create a directory to host your first project, navigate to it and initialize a `uv` project with:
```zsh
uv init --python=3.14
```

and add your first package, we will need it to work with Python notebooks:
```zsh
uv add ipykernel
```

You are now ready to start with the first notebook - `intro.ipynb`.
