Completely Automated Public Turing test to tell Computers and Humans Apart Written by: Devji Chhanga
- writeImage would be called by the callee php file.
- Captcha text would be stored in session as it's MD5 value and image would be returned as MIME.
- Font file is to be put in the same directory with this php file.
- Example Call: writeImage(127, 12, 4, 40, 45, "ITCKRIST.TTF", "255, 255, 255", "255, 100, 25");
- See: example.php


Arguments to writeImage function :
1. Width: Width of the image
2. Height: Height of the image
3. strLen: Length of CAPTCHA string
4. fontSize: Font size of letters
5. angMax: Maximum positive or negative angle for letters
6. font: Font to be used to write letters
7. penColorRGB: RGB color value for letters
8. backColorRGB: RGB color value for background of image
