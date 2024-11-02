# jpg-png-to-webp
A batch script to convert all images in folders to webp format, this could help you change all of your image formats in your website, after running the scipt, in your site source code find and replace .png or .jpg with .webp
Test on local dev before uploading to live server

This script can be run using linux terminal, first install:
sudo apt install webp -y
and then
sudo apt install webp parallel -y which should improve performance

cd into the folder you want to convert i.e. cd /var/www/website/content/images

copy the file into that directory, and run with:

bash webp-convert-directory.sh

To convert other file types hange the file type from jpg to png 

*** ---- WARNING  ---***
You can delete the original files be uncomenting these lines, please make sure you have a backup!
