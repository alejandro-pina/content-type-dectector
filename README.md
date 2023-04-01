# File Content Type Detector

The File Content Type Detector is a powerful tool that helps you detect the content type of a file based on its extension. It is a useful utility that can be integrated into your projects to automatically determine the appropriate content type for a file, which is essential for web applications that serve files to clients.

With a simple function call, you can easily get the content type of any file based on its extension. The tool includes a comprehensive list of file extensions and their associated content types, which is regularly updated to ensure accuracy and reliability.

## How to use
To use the File Content Type Detector, simply call the get_content_type function and pass in the file extension as an argument. The function will return the corresponding content type for that extension. If the extension is not found in the list, the function will return application/octet-stream as the default content type.

Here's an example usage:
```python
from file_content_type_detector import get_content_type

content_type = get_content_type('.pdf')
print(content_type) # Output: application/pdf
```
.aac
.abw
.arc
.avif
.avi
.azw
.bin
.bmp
.bz
.bz2
.cda
.csh
.css
.csv
.doc
.docx
.eot
.epub
.gz
.gif
.htm
.html
.ico
.ics
.jar
.jpeg
.jpg
.js
.json
.jsonld
.mid
.midi
.mjs
.mp3
.mp4
.mpkg
.odp
.ods
.odt
.oga
.ogv
.ogx
.opus
.otf
.png
.pdf
.php
.ppt
.pptx
.rar
.rtf
.sh
.svg
.tar
.tif
.tiff
.ts
.ttf
.txt
.vsd
.wav
.weba
.webm
.webp
.woff
.woff2
.xhtml
.xls
.xlsx
.xml
.xul
.zip
.3gp
.3g2
.7z

## License

[MIT](https://choosealicense.com/licenses/mit/)
