# Music2TV - A MTV substitute

An MTV Substitute

![MTV-Logo](imgs/mtv.jpg)

To use it, it is necessary to create a [MOISES API](https://moises.ai/) and also an [OpenAI API](https://openai.com/blog/openai-api/).

# Install

Create conda env:

```bash
$ conda create -n stable_diffusion python=3.10 pip
```
```bash
$ conda activate stable_diffusion
```
Install  requirements:

```bash
$pip install -r  requirements.txt
```

# Execute

First, save a audio file at audio folder and execute the script:

```bash
$ python main.py
```

The result will be in "dreams" folder.
