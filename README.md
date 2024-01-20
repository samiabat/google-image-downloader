## Google Image Downloader
### Quick Start
1. Clone the Repository
```
git clone https://github.com/samiabat/google-image-downloader
```
2. Install Dependencies
```
pip install -r requirements.txt
```
## Usage
### Download Images Using Code
To download images programmatically, use the provided Python script.
Open the Python script download_image.py.
Edit the keywords and limit parameters based on your preferences.
Run the script:
```
python download_image.py
```
Example
```
from pygoogle_image import image as pi
```


# Download images with specified keyword and limit
```
pi.download(keywords='cat', limit=10)
```

# Specify a custom directory for saving images
```
pi.download(keywords='cat', limit=10, directory='c:\image')
```