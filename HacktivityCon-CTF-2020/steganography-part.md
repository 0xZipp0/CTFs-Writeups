# H@cktivityCon CTF 2020

## Steganography

### Spy vs. Spy

> Challenge statement:
> Antonio Prohías was a cartoonist known primarily as the creator of the satirical comic strip Spy vs. Spy for Mad magazine. It wasn't until after 1997 when the comics changed from black and white to full color.

Solution:
1. after downloaded the image, i try to translate the morse code in the image,
    but it wasn't the flag.

2. after that i tried using 'zsteg, strings, and exiv2 or exiftool to get the flag, but
    couldn't find it.

3. Later i used 'stegsolve' to find the flag within the picture using image filter in stegsolve

```
terminal command: java -jar stegsolve.jar
```

![Spy result](https://github.com/m0nkeyt3ch/CTFs-Writeups/blob/master/HacktivityCon-CTF-2020/Image/spy-result.png)      

4. we found the flag is 'flag{two_MAD_spies}'

FLAG: **flag{two_MAD_spies}**

### Cold War
> Challenge statement:

> A geopolitical activity that is pursued through economic and political actions, propaganda, acts of espionage or proxy wars and without direct military action is known as a Cold War. This type of war does not refer to conflict of seasons, but this challenge might.

Solution:
1. after downloaded the text file, we realized this challenge is **whitespace steganography**.

2. we can use SNOW program in windows to decrypt it [SNOW Program](http://www.darkside.com.au/snow/) or stegsnow in linux to decrypt it

```
windows command: 
SNOW.EXE -C cold_war.txt

linux: 
stegsnow -C cold_war.txt 

flag{do_not_use_merriam_webster}
```

![cold-war result](https://github.com/m0nkeyt3ch/CTFs-Writeups/blob/master/HacktivityCon-CTF-2020/Image/cold-war.png?raw=true)      

3. we found the flag is 'flag{do_not_use_merriam_webster}'

FLAG: **flag{do_not_use_merriam_webster}**

### 