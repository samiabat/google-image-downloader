
### first clone this repo
```
git clone 
```

### next install dependecies
```
pip install -r requirements.txt
```
### in the example below we will pass on the keyword 'cat' and we will limit the number of images to be downloaded to only 10</br>
```
from pygoogle_image import image as pi

pi.download(keywords='cat', limit=10)
```
### if you don't specify a directory, pygoogle_image will create a folder called image at the root of the project. if you wish you can save it in a specific directory</br>
```
pi.download(keywords='cat', limit=10, directory='c:\image')
```

### if you want to download specific number of images of with some keyboard
just open download_image.py and edit the keyboard and the limit and then

```
python download_image.py
```

# google-image-downloader
