# Blur Faces

This is a simple model that applies a blur filter to input image.

This is the simplest implementation. I'll be updating it to use a pretrained model and OpenCV to detect faces and blur them.

## Usage

Make sure you have [Cog](https://github.com/replicate/cog#install) installed.

Build the model:

```bash
  cog build
```

You can run predictions on the model using the following command: (I've included a sample image in the repo)

```bash
  cog predict -i image=@samples/house.png -i blur=4
```
