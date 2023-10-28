

# Unsplash Image Downloader
## Overview
This project revolves around a web scraping endeavor where images from Unsplash are scraped using their API endpoint. The goal of the project is to download a collection of images from Unsplash and store them locally for various purposes such as personal use, creative projects, or as data for machine learning training data.

## Project Workflow
* [Notebook](https://github.com/Bytecode-Magnum/Unsplash_Image_Scrapper/blob/main/unsplash_stock_images.ipynb)

HTTP Request and JSON Parsing: The requests module is employed to initiate an HTTP request to the Unsplash API endpoint. The JSON response is received, which contains metadata about images, including URLs.

* Image URL Extraction: The JSON response is parsed to extract the URLs of the images. These URLs are stored in a list for subsequent processing.

* Image Download: Each URL in the list is visited using the requests module to initiate an HTTP request to the image source. The image is downloaded and stored at a specified location on the local system.

## Dependencies
* Python 3.x
* requests
* json
* imghdr

## Conclusion
This project showcases the process of accessing an API endpoint, parsing JSON responses, and utilizing the requests module to download and save images from the Unsplash platform. 
