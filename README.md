# 3d
To run the `.ipynb` notebooks in VSCode, try installing [The Jupyter Notebook Extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter). When you try to run a cell in the notebook, you should get prompted to select which Python environment you want to install.

To run `build123d` Python files, whether as a `.ipynb` notebook or a `.py` script, install the VSCode extension [OCP CAD Viewer](https://github.com/bernhard-42/three-cad-viewer), and run the following once in the integrated terminal in VSCode or on the command line:

```console
python -m pip install build123d ocp_vscode
```
And you should get this pane to pop up when you run `build123d` cells or python files that import `build123d` in the integrated terminal:

![image](https://github.com/user-attachments/assets/dfee8f02-8aa1-4ea9-84cf-7f39976b9e41)
