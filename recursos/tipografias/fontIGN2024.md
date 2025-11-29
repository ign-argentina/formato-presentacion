
## Download from
-[Lora](https://github.com/cyrealtype/Lora-Cyrillic/tree/main/fonts)
-[Montserrat](https://github.com/JulietaUla/Montserrat/tree/master/fonts/)


## Convert from OTF to Type 1 using FontForge:
`
fontforge -lang=ff -c 'Open($1); Generate($1:r + ".pfb");' Lora-BoldItalic.otf
`

# Generate TFM Metrics
`
fontforge -lang=ff -c 'Open($1); Generate($1:r + ".tfm");' Lora-BoldItalic.otf
`
