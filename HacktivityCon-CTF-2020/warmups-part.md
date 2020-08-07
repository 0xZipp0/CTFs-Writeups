# H@cktivityCon CTF 2020

## Warmups

### Read The Rules

> Challenge statement:
>
> Please follow the rules for this CTF!
>
> Connect here:
> https://ctf.hacktivitycon.com/rules

Solution:
1. just open the link and read the rule.

2. They put the clue of the flag in the part of the rules. This is the clue.
    > If you look closely, you can even find a flag on this page!

3. I tried to 'inspect' or 'View page source' using google chrome, you can use any browsers. After that you will found the flag in the page source code.

    ![read the rules result](https://github.com/m0nkeyt3ch/CTFs-Writeups/blob/master/HacktivityCon-CTF-2020/Image/read-the-rules.png?raw=true)      

4. we found the flag is 'flag{its_time_to_hack}'

FLAG: **flag{its_time_to_hack}**

### Caesar Mirror
> Challenge statement:
>
> Caesar caesar, on the wall, who is the fairest of them all?

Solution:
1. After downloaded the file, this challenge is Caesar Cipher with shift 13 a.k.a ROT13
2. to decrypt the message we can use [this decoder](https://www.dcode.fr/caesar-cipher)
3. after decrypt the message we found the right part is mirrored and need to rearrange
4. we need to rearrange the right part to find the flag, after we rearranged it we found the flag is 'flag{julius_in_a_reflection}'

    ![Caesar Mirror result](https://github.com/m0nkeyt3ch/CTFs-Writeups/blob/master/HacktivityCon-CTF-2020/Image/caesar-mirror.png?raw=true)

FLAG: **flag{julius_in_a_reflection}**

### Internet Cattos
> Challenge statement:
>
> The Internet is full of wonderful kittens and cattos. You can even find one at jh2i.com on port 50003!

Solution:
1. This challenge is not to hard i think, just use net cat to connect to jh2i.com on port 50003
2. After that u will got a message "Oh, we already sent the flag! Did you see it?"
3. To find the flag i use this command
   ```
   nc jh2i.com 50003 > InternetCattos
   ```
4. After that you will need to open the InternetCattos using nano or any editor to see the flag, because the flag is like this
   ![Internet Cattos result](https://github.com/m0nkeyt3ch/CTFs-Writeups/blob/master/HacktivityCon-CTF-2020/Image/InternetCattos.png?raw=true)

5. we need to rearrange the flag, after we rearranged it we found the flag is 'flag{this_netcat_says_meow}'

FLAG: **flag{this_netcat_says_meow}**

### Vencryption
> Challenge statement:
>
> I know the flag is in this file! I just cannot open it for some reason...

Solution:
1. After downloaded the file, we knew that the file was encrypted by vim 
2. To decrypt the message we can use [vim decryptor](https://github.com/nlitsme/vimdecrypt) written by [nlitsme](https://github.com/nlitsme)
3. I used rockyou wordlist and this command to decrypt the text message
    ```
    python vimdecrypt.py --dictionary /usr/share/wordlists/rockyou.txt ~/Desktop/Hacktivity\ CTF/vencrypted.txt 
    ```
4. After run that command we will get the result like this
   
5. we need to rearrange the right part to find the flag, after we rearranged it we found the flag is 'flag{julius_in_a_reflection}'

```
python vimdecrypt.py --dictionary /usr/share/wordlists/rockyou.txt ~/Desktop/Hacktivity\ CTF/vencrypted.txt
```