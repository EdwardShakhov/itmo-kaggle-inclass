# itmo-kaggle-inclass
Competition for course "Event detection"

Init conda environment from .yml file:

`conda env create -f environment.yml`

You need torchaudio for this project. To download additional dependencies follow these instructions: 

https://github.com/pytorch/audio

This notebook requires NVidia GPU with CUDA kernetls. If do not have one, then this .yml file does not suit you and you have to create environment by yourself. It it easy, just do `conda create -n '<new_env>'` and install all required dependencies with `pip`. You can recognize dependancies looking at `import` block. Also, correct the code in notebook, hiding all `.cuda()` in it.
