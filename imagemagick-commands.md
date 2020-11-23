# ImageMagick Commands

## Resize Images

Adds white boarders to make image square.

```bash
# all images
convert -background white -gravity center *.* -resize 400x400 -extent 400x400 result.png
# all .jpg
convert -background white -gravity center *.jpg -resize 400x400 -extent 400x400 result.png
# all .png
convert -background white -gravity center *.png -resize 400x400 -extent 400x400 result.png
```

## Threshold Images

```bash
convert *.png -threshold 50% threshold.png
```
