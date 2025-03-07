## Introduction
This github repository is designed to take iterative screenshots and save them in PDF file format.<br>
To use run `python main.py` , default rate is 10 screenshot per minute, default duration is 1800s, default output directory is myPDFs.
You can set custom number of screeshots per minute (rate), duration, name, output_directory_path.<br>
To use  `python main.py -r rate_of_images_per_minute -d duration in sec -o output_directory_name -n name_of_PDF `.  <br>
For more info you can use `python main.py -h `
To exit the program before set duration use KeyboardExpection using `Ctrl + C`

## To use
1. `pipenv install`  installl virtual environment
2. `pipenv shell`  activate environment
3. `pipenv install -r requirements.txt` install dependencies

## Libraries used
`Numpy` `opencv-python ` `pillow` `pyautogui` `fpdf` 
