# Steganography

## Challenge statement:
A geopolitical activity that is pursued through economic and political actions, propaganda, acts of espionage or proxy wars and without direct military action is known as a Cold War. This type of war does not refer to conflict of seasons, but this challenge might.

## Solution
1. after downloaded the text file, we realized this challenge is **whitespace steganography** .

2. after that i tried using 'zsteg, strings, and exiv2 or exiftool to get the flag, but
    couldn't find it.

3. Later i used 'stegsolve' to find the flag within the picture using image filter in stegsolve

    terminal command: java -jar stegsolve.jar
![Spy result](https://github.com/m0nkeyt3ch/CTFs-Writeups/blob/master/HacktivityCon-CTF-2020/Image/spy-result.png)      

4. we found the flag is 'flag{two_MAD_spies}'