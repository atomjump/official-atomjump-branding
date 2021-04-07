# Using imagemagick

Useful commands used to generate 

```
convert atomjump-printable-logo.png -threshold 99.9% aj-gray.png
convert alpha.png -colorspace gray alpha-grayscale.png
convert alpha-grayscale.png -negate alpha-inverted.png
convert atomjump-printable-logo.png alpha-inverted.png  -compose copy-opacity -composite rgba.png
```