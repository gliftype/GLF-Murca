# GLF-Murca

## About

This font blends traditional Gothic typography elements with sleek, modern geometric structures, resulting in a striking yet minimalist and legible medieval aesthetic. The character forms are designed with strong vertical lines, sharp angles, and proportions inspired by classic blackletter styles, making it exceptionally well-suited for fantasy themed designs, metal music posters, premium product branding, or historical book covers.

### Prerequisites
Make sure you have **Python 3.10 or higher** installed on your system.

### Installation
Open your terminal and install the required font engineering tools via pip:
```bash
pip install fontmake glyphsLib fontbakery[googlefonts] gftools
```

### Build Instructions
Run the following command to generate desktop-ready OpenType and TrueType fonts:
```bash
# Create destination directories
mkdir -p fonts/ttf fonts/otf

# Compile the .glyphs source file
fontmake -g Sources/GLF_Murca.glyphs -o ttf --output-dir fonts/ttf/
fontmake -g Sources/GLF_Murca.glyphs -o otf --output-dir fonts/otf/
```
The compiled files will appear inside the newly created `fonts/` directory.

## License
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
https://openfontlicense.org

## Contributors
Sidiq Kamal Nurmawan <sidiq.nurmawan@gmail.com>
Erwin Wirianata <wirianata.erwin@gmail.com>

![Alt Text](GLF-Murca.png)

# Notes
This is a beta font with ongoing improvements and fixes. Every update will be published directly to the repository.
