# Pitzulit
Extract tracks from an album hosted on YouTube (or any host supported by [youtube-dl](https://github.com/rg3/youtube-dl))
based on the timestamps in its description.
Expects `ffmpeg` and `youtube-dl` to be in your $PATH.

## Usage
```
./pitzulit URL
```
Provided the video this URL leads into is titles X, running this command will result in a new directory named X under the current working directory. Inside this directory, a couple of fresh tracks will wait for you, named according to the track titles found in the description.
