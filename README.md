# latex-flatten

A simple Python script for flattening LaTeX files by inlining included files.

  - Supports `\include` and `\input` commands.
  - Automatically adds extension `.tex` if the file does not have an extension.
  - Handles multiple include commands per line, comments.
  - Does not flatten recursively.


## Installation and usage

1. Get a Python interpreter...

2. Make sure that `latex-flatten.py` is in your `$PATH` or create a
   symbolic link using

   ```bash
   ln -s /path/to/latex-flatten.py /bin/dir
   ```

3. Run

    ```bash
    latex-flatten.py main.tex output.tex
    ```

## License

See UNLICENSE file.
