# AnimeGrabber
This script allows the user to download posts from the imageboards "danbooru" and "gelbooru".
Posts are in general .png and .jpeg images, but there may be also videos and zip files between them. 
Be aware that the script also downloads R-rated images.
It is not yet implemented to allow downloads from sankaku channel.

Usage: 
'''
python grabber.py -t "tags" out_folder n_pages source
'''

-tags: Check danbooru's and gelbooru's website for more information about how to use tags.
-out_folder: The folder where the images are going to be downloaded to.
-n_pages: The number of pages to be downloaded. There are roughly 100 posts per page.
-source: 1 for danbooru, 2 for gelbooru. 
