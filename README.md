# animatediff sdxl lcm

This is an implementation of the AnimateDiff SDXL LCM as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i prompt="A panda standing on a surfboard in the ocean in sunset, 4k, high resolution. Realistic, Cinematic, high resolution"

## Example:

"A panda standing on a surfboard in the ocean in sunset, 4k, high resolution. Realistic, Cinematic, high resolution"

![alt text](output.gif)
