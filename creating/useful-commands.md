# Using imagemagick

Useful commands used to generate 

```
convert atomjump-printable-logo.png -threshold 99.9% aj-gray.png
convert aj-gray.png -colorspace gray alpha-grayscale.png
convert alpha-grayscale.png -negate -threshold 0 -monochrome alpha-inverted.png
convert atomjump-printable-logo.png alpha-inverted.png  -compose copy-opacity -composite rgba.png
```