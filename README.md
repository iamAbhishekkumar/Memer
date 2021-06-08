# Memer

It returns you, a random programming meme that you can show in your readme. You can use this in your github's profile page.[Like....](https://github.com/iamAbhishekkumar)

### How to use

For Mark-Down files:

    ![your-meme](https://memer-github.herokuapp.com/getImage)

To adjust the size of image :

    <img src="https://memer-github.herokuapp.com/getImage" width="300px">

Just Copy and paste the above, where you want to show the meme.

#### Preview

<img src="https://memer-github.herokuapp.com/getImage" width="300px">

### Problem Faced

GitHub doesn't allow javascript in markdown, so i cant' simply sent a request to a url. So, I have to do this using "image" tag provided by markdown.

To host your images, GitHub uses the open-source project Camo. Camo generates an anonymous URL proxy for each file which hides your browser details and related information from other users.

So, the main problem was, it caches the image and even the image changes,it doesn't reflect in readme. So, to fix that problem, I have to set the cache-control to 'no-cache'.

For more info, [About anonymized URLs](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/about-anonymized-urls).

**NOTE : For security purposes, I can't make the src code public as it may lead to submission of inappropriate images.**

If you like it, star this repo.If you find any issues, feel free to raise issues. Enjoy!:upside_down_face:
More programming memes will added soon.....
