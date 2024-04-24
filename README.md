# File Sorter

The File Sorter is a Jupyter Notebook project that automatically sorts files in a folder to their respective subfolders based on file types or extensions.

## Overview

The File Sorter performs the following tasks:

- Scans a specified folder for files.
- Identifies the file types or extensions of each file.
- Moves files to their corresponding subfolders based on their types or extensions.

## Notebook Contents

- **file_sorter.ipynb**: Jupyter Notebook containing the Python code for the file sorting tool.

## Getting Started

To use the File Sorter:

1. Clone or download this repository to your local machine.
2. Open the `file_sorter.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Follow the instructions provided in the notebook to:
   - Specify the directory path of the folder containing the files to be sorted.
   - Define the folder structure and mapping of file types to subfolders.
   - Run the code cells to execute the file sorting process.
4. Once the sorting is complete, the notebook will organize the files into their respective subfolders within the specified directory.

## Dependencies

This project requires the following Python libraries:

- `os`: For interacting with the operating system and file paths.
- `shutil`: For moving files between directories.

These libraries are typically included with Python installations and do not require additional installation.

## Usage

Follow the steps outlined in the notebook to specify the directory path, define the folder structure, and execute the file sorting process. The notebook provides detailed instructions and code comments to guide you through the process.

## Example

Here's an example usage scenario:

1. Open the `file_sorter.ipynb` notebook in Jupyter Notebook.
2. Specify the directory path of a folder containing unsorted files.
3. Define the folder structure and mapping of file types to subfolders (e.g., images in an "Images" folder, documents in a "Documents" folder).
4. Run the code cells to sort the files into their respective subfolders.
5. Navigate to the specified directory to view the organized files in their respective subfolders.

## License

This project is licensed under the [MIT License](LICENSE).
