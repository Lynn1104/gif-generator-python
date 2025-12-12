# Create a GIF with Python
Simple python project that converts a sequence of iamges into a animated GIF.

## Project Description
This project demonstates how to generate animated GIFs using Python and the `imageio` library.
It reads multiple images, combines them into a single animation, and export the final GIF into the `output/` folder.

## Project Structure
```bash
📦 create-gif-project
│
├── src
│   └── create_gif.py
│
├── images
│   ├── team-pic1.png
│   └── team-pic2.png
│
└── output
    └── .gitkeep
```

## How to run
### 1. Install dependencies
```
pip3 install imageio
```
### 2. Run the script
```
python3 src/create_gif.py
```
### 3. Output
Your generated GIF will be appear in:
```
/output/team.gif
```
