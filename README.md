### Dependencies needed

1. Selenium
Install as `pip install selenium`
2. Geckodriver
- Download latest release
`wget https://github.com/mozilla/geckodriver/releases/download/v0.18.0/geckodriver-v0.18.0-linux64.tar.gz`
- Extract the file
`tar -xvzf geckodriver*`
- Make it executable
`chmod +x geckodriver`
- Add the driver to the path for other tools to use it
`export PATH=$PATH:/path-to-extracted-file/geckodriver`







### Download any number of images from Google image search.

- run as (Use 2/3 according to python version)
-**Python 2**
`python image_download_python2.py <query> <number of images>`

-**Python 3**
`python image_download_python3.py <query> <number of images>`

where:

`<query>` is the the query to search for.

`<number of images>` min(`<number of images>`, total google results) will be downloaded.

All the images are downloaded from Google image search. These should be used for educational purposes only. Copyright is owned by the respective websites.
