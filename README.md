# SamilaRT

SamilaRT is a program for generating artistic images using random mathematical functions. The program utilizes the Samila library and provides various options for generating and visualizing art.

## Installation

1. Make sure you have Python 3.6 or a newer version installed on your computer. You'll also need pip to manage Python dependencies.

2. Clone the SamilaRT repository from GitHub:
```
git clone https://github.com/gerryauditya6/SamilaRT.git
```
3. Navigate to the project directory:
```
cd SamilaRT
```
4. Create a virtual environment to isolate the project dependencies:
```
python3 -m venv venv
```
5. Activate the virtual environment:
- Windows:
  ```
  venv\Scripts\activate
  ```
- MacOS/Linux:
  ```
  source venv/bin/activate
  ```
6. Install the required dependencies:
```
pip install -r requirements.txt
```

## Usage

1. Run the program:
```
python samilart.py
```
2. The program will start and display the SamilaRT prompt: `SamilaRT >`
3. Available commands:
- `help`: Show usage information.
- `generate`: Start generating art. You will be prompted to enter a seed (or use a random number) and select a projection type.
- `show`: Display a list of PNG files in the current directory. You can choose a file to open and view.
- `exit`: Stop the program.

4. Follow the prompts and instructions to generate and view art.

## Additional Notes

- The program generates random mathematical functions to create artistic images.
- Each run of the `generate` command uses a seed to ensure reproducibility.
- The generated images are saved as PNG files in the current directory.
- You can view the generated images using the `show` command.

Please make sure you have the necessary permissions and dependencies to run the program. For more information and usage examples, refer to the source code and the comments within.

Enjoy creating art with SamilaRT!
