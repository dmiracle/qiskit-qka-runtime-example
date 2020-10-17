# Jupyter Notebook Starter

A starter project for running jupyter notebooks in a container with vscode. Modified from https://github.com/Microsoft/vscode-remote-try-python.

## Serve a Jupyter Notebook
```
jupyter notebook --ip=0.0.0.0 --port=9099 --no-browser
```

## Start a New Project
```
git clone https://github.com/dmiracle/jupyter-starter.git <project-name>
git remote rm origin
git remote add origin <project-url>
git push -u origin main
```

