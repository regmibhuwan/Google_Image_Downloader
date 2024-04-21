# Google Image Downloader
## Description
This Python script, google_image_downloader, automates the process of downloading images from a specific page on Wikimedia Commons. It saves these images into a folder named "google_images," demonstrating simple web scraping techniques and local file management.

## Features
- Automated Image Downloading: Downloads all available images from the specified Wikimedia Commons page.
- Simple Customization: Easy to modify for other pages or similar websites with open content.
- Efficient Handling: Saves images directly to a designated local directory.
## Prerequisites
To run this script, ensure you have the following installed:

Python
- Libraries: requests, bs4 (BeautifulSoup)
## Installation
### Clone the Repository:

- *git clone*: https://github.com/regmibhuwan/Google_Image_Downloader.git
cd Google_Image_Downloader
- Install Required Python Libraries:

pip install requests beautifulsoup4
## Usage
To use the google_image_downloader, follow these steps:

- Set the URL:
Open google_image_downloader.py and replace the url parameter in the download_images function call with the URL of the page from which you want to download images.
- Run the Script:
Execute the script from your command line. 
*python google_image_downloader.py*
- Check the 'google_images' Folder:
Open the google_images folder in your directory to view the downloaded images.
## Configurations
- URL Configuration: Change the url variable to point to a different webpage as needed, ensuring it is a site that allows scraping.
- Folder Name Configuration: The default folder for downloaded images is "google_images". This can be changed in the script by modifying the folder_name parameter.
## Contributing
Contributions are welcome! If you have improvements or bug fixes, please fork the repository and submit a pull request.

