
# Camera Parameter Extractor

## Description

This project extracts camera parameters (metadata) from images and saves the information into a CSV file. It also provides functionality to convert the CSV file into a JSON file. The script processes images in a specified folder, reads their EXIF data, and extracts camera parameters such as camera make, model, and other relevant metadata.

## Features

- Extract camera parameters (metadata) from images.
- Save the extracted metadata to a CSV file.
- Convert the CSV file to a JSON file.

## Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.6+
- pip (Python package installer)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/venkateshkumarraju/camera-parameters-.git
    cd camera-parameter-
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Extract Camera Parameters

To extract camera parameters from images in a folder and save them to a CSV file:

1. Place your images in a folder, e.g., `input_images`.
2. Run the notebook:

    ```sh
    python camera_parameters.py --input_folder path/to/input_images
    ```

3. The extracted parameters will be saved in `camera_parameters.csv`.

### Convert CSV to JSON

To convert the generated CSV file to JSON:

1. Run the notebook:

    ```sh
    python convert_csv_to_json.py --csv_file camera_parameters.csv --json_file camera_parameters.json
    ```

2. The JSON file will be saved as `camera_parameters.json`.

## Example

Place your images in the folder `input_images` and run notebook:

output files are save as camera_parameters.csv ,camera_parameters.json

## Dependencies
Ensure you have the following libraries installed:
Pillow
pandas

## You can install these dependencies using the following command:

```sh
pip install Pillow pandas
```

# Contact
For any questions, suggestions, or feedback, please contact us at raju.venkateshkumar@gmail.com
