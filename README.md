# Predictive Analytics 2025/26

## Setting things up
First, we will install a package manager for Python, in this course we will use `uv`. To download it run the following commands:
```zsh
curl -LsSf https://astral.sh/uv/install.sh | sh
```
on macOS and Linux, or:
```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```
on Windows.

Now create a directory to host your project, navigate to it and initialize a `uv` project with:
```zsh
uv init --python=3.14
```
