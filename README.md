# Background Remover

A simple Python application that removes the background from an image automatically.

This project uses the `rembg` library to process an input image and create a new image with a transparent background.

## Features

- Removes image backgrounds automatically
- Supports common image formats
- Creates an image with a transparent background
- Simple and easy to use

## Technologies

- Python
- rembg

## Installation

Install the required library:

```bash
pip install rembg
```

## Usage

Place the image you want to process inside the project folder.

Run the program:

```bash
python main.py
```

The program reads the input image, removes its background, and saves the result as a new image.

## Example

Original image:

```text
input.png
```

After background removal:

```text
output.png
```

## How It Works

The project uses the `remove()` function from the `rembg` library:

```python
from rembg import remove
```

The image is read, processed to remove the background, and then saved as a new file.

## What I Learned

Through this project, I practiced:

- Using external Python libraries
- Working with image files
- Reading and writing files in Python
- Removing image backgrounds with `rembg`
- Managing Python projects with Git and GitHub

## Author

Created by Bejna
