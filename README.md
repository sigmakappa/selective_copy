# selective_copy

Simple command line application that copies all files with given extension from a directory and its subfolders to another directory showing progress bar and remaining files counter.\
Allows to preserve a source folder structure and to create a log if necessary.\
Opens a filedialog if source and/or destination are not given in the command line.\
Creates folders in a destination path if they don't exist.

Usage:
<pre>
Positional arguments:
ext                         Extension for the files to copy, enter without a dot.

Optional arguments:
-s SOURCE, --source SOURCE  Source path.
-d DEST, --dest DEST        Destination path.
-p, --preserve              Preserve source folder structure.
-l, --log                   Create and save log to the destination folder.
-h, --help                  Show this help message and exit.
</pre>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

Inspired by the task from [Chapter 9 of Automate the Boring Stuff](https://automatetheboringstuff.com/chapter9/).
