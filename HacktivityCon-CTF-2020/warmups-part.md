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

### CaesarMirror
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