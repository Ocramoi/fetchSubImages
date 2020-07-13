# fetchSubImages
Module that returns image file URLs for the last media in any given subreddit.  
To use it, import the `fetchSubImages` module to your project and get the array of the images addresses in the `n` [n ∈ (0, 100)] last posts in the sub, returning only the ones containing images, in URL with the function `returnUrls(subReddit, maxNumberImgs)` (*use* `n = 0` *to return all images in the last 100 posts*).
