
# fetchSubImages
To install the package run `pip install fetchSubImages` in your environment.  
The module gives utilities for fetching image posts from any given subreddit.  
```python
import fetchSubImages

# Return the image URLs from the last 50 image posts in r/aww  
imgUrls = fetchSubImages.returnUrls("aww", 50)  
  
# Return the titles from the last 50 image posts in r/aww  
imgTitles = fetchSubImages.returnTitles("aww", 50)  
  
# Return the titles and image URLs from the last 50 image posts in r/aww as objects containing 'title' and 'url'  
imgObjs = fetchSubImages.returnObjs("aww", 50)  
  
# Download all images in the last 50 image posts in r/aww with [title].png as filename to 'posts' folder  
fetchSubImages.downloadImgs("aww", 50, "posts")
```
