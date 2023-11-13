# QRcode
This is a static webpage that generates QR codes

## Generate QRCodes directly from URL variables
The page was originally designed to generate QR codes for websites (or other text) passed as a URL variable.  
To generate a QRCode for a website: https://example.com
* The website should be passed as a URL variable "QRCode": ?QRCode=https://example.com (replacing the website with the text of your choice)
* This should be appended to the end of the URL in the address bar when loading the page
* eg: https://waynekark.github.io/QRcode/?QRCode=https://example.com

## Generate QRCodes from form
The page includes a text box that allows QR codes to be generated from the contents of the text box. The QRCode updates every time a key is pressed inside the box.

## Self referencing QR code
This repository also contains an HTML file "SelfQRCode.html" that creates a QR code to itself. The script can be added to any webpage to create self referencing QR codes. This is useful if you have a webpage that people might wish to be able to access on their own devices.

_This is a static page deployed on GitHub pages, written in HTML with Javascript_
