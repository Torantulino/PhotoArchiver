# phar Photo Archiving Script

The "phar" script is a Bash script designed to help you organize and archive your photos by finding and copying files that match a specific naming convention. This can be useful if you have a large collection of photos and want to quickly find and organize them.

## Installation

To use the "phar" script, simply download the script file to your computer and make sure it has executable permissions. You can do this by running the following command in your terminal:

```bash
chmod +x phar.sh
```

## Usage

To use the "phar" script, simply run the script in your terminal and provide the source and destination directories as arguments. For example:

```bash
./phar.sh /path/to/source/directory /path/to/destination/directory
```

The script will search for files in the source directory that match the naming convention "IMG_XXXX.JPG", where "XXXX" is a four-digit number. It will then copy these files to the destination directory, renaming them if necessary to avoid duplicates.

## Examples

Here are some examples of how to use the "phar" script:

```bash
./phar.sh ~/Pictures /mnt/external/photos
```

This will search for files in the "~/Pictures" directory that match the naming convention "IMG_XXXX.JPG" and copy them to the "/mnt/external/photos" directory.

## Contributing

If you would like to contribute to the "phar" script, please feel free to submit a pull request or open an issue on GitHub.

## License

The "phar" script is released under the MIT License. See the LICENSE file for more information.

## Credits

The "phar" script was created by [Toran Bruce Richards](https://github.com/Torantulino).
