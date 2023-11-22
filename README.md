
# Paint

A simple, text-based version of the Paint app.

## Getting Started

Follow these instructions to get Paint running on your computer.

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/dihan922/paint
    cd paint
    ```

2. **Build executable:**
    ```bash
    make
    ```

## Usage

1. **Start Program:**
    ```bash
    ./paint.out [row count] [column count]
    ```

2. **Use the commands to interact with the program:**

### Commands
- `h`: Display a help screen with all commands.
- `q`: Quit the program.
- `w <row_start> <col_start> <row_end> <col_end>`: Draw line between 2 points.
    - Lines must be vertical, horizontal, or perfectly diagonal.
- `r <num_rows> <num_cols>`: Resize canvas to specified size.
- `a <r | c> pos`: Add a row or column to a specified position.
- `d <r | c> pos`: Delete a row or column at a specified position.
- `e <row> <col>`: Delete a specific point.
- `s <file_name>`: Save canvas to a file.
- `l <file_name>`: Load canvas from a save file.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit).
