# Line Encoding Visualizer
https://medium.com/@nkharshbachhav/understanding-line-encoding-a-visual-guide-to-digital-communication-techniques-bfc89eea6fb4

This Python script visualizes various line encoding techniques used in digital communication systems. It provides a graphical representation of how binary data is encoded into digital signals.

![image](https://github.com/user-attachments/assets/a7b8c00c-abba-48fd-9917-96c3d224003f)


## Features

- Visualizes 6 different line encoding techniques:
  1. Unipolar NRZ (Non-Return to Zero)
  2. Polar NRZ
  3. NRZ Inverted
  4. Bipolar
  5. Manchester
  6. Differential Manchester
- Interactive command-line interface for custom input
- Matplotlib-based visualization

## Requirements

- Python 3.x
- matplotlib
- numpy

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Harsh-1807/line-encoding-visualizer.git
   ```
2. Navigate to the project directory:
   ```
   cd line-encoding-visualizer
   ```
3. Install the required packages:
   ```
   pip install matplotlib numpy
   ```

## Usage

Run the script from the command line:

```
python line_encoding_visualizer.py
```

The script will first display an example encoding for the bit sequence '101011'. Then it will prompt you to enter your own binary sequences. Enter a sequence of 0s and 1s to see its encoding, or 'q' to quit the program.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
