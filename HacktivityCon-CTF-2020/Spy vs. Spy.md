# Steganography

## Challenge statement:
Antonio Prohías was a cartoonist known primarily as the creator of the satirical comic strip Spy vs. Spy for Mad magazine. It wasn't until after 1997 when the comics changed from black and white to full color.

## Solution:
1. after downloaded the image, i try to translate the morse code in the image,
  but it wasn't the flag.

2. after that i tried using 'zsteg, strings, and exiv2 or exiftool to get the flag, but
  couldn't find it.

3. Later i used 'stegsolve' to find the flag within the picture using image filter in stegsolve

    terminal command: java -jar stegsolve.jar
        

4. we found the flag is 'flag{two_MAD_spies}'

