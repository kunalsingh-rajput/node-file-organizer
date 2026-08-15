# Node File Organizer

A simple Node.js application that automatically organizes files into folders based on their file extensions.

## Features

* Automatically reads files from a directory
* Detects file extensions
* Creates folders based on file types
* Moves files into their respective folders
* Prevents duplicate folder creation
* Built using Node.js built-in modules

## Technologies Used

* Node.js
* JavaScript
* File System (fs)
* Path (path)

## Project Structure

```text
node-file-organizer/
|
├── script.js
├── package.json
└── README.md
```

## How It Works

The application:

1. Reads all files from the specified directory.
2. Checks the extension of each file.
3. Creates a folder using that extension if it doesn't already exist.
4. Moves the file into the corresponding folder.

For example:

Before:

```text
file-organizer/
├── photo.jpg
├── document.pdf
├── image.png
└── data.json
```

After running the program:

```text
file-organizer/
├── jpg/
│   └── photo.jpg
├── pdf/
│   └── document.pdf
├── png/
│   └── image.png
└── json/
    └── data.json
```

## How to Run

Make sure Node.js is installed on your computer.

Clone the repository:

```bash
git clone https://github.com/kunalsingh-rajput/node-file-organizer.git
```

Go into the project directory:

```bash
cd node-file-organizer
```

Run the application:

```bash
node script.js
```

## Note

Before running the program, update the `basepath` variable in `script.js` with the directory you want to organize.

## Author

Kunal Singh Rajput

GitHub: https://github.com/kunalsingh-rajput
