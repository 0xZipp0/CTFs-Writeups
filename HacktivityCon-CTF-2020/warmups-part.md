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

2. They put the clue of the flag in the part of the rules.
    > If you look closely, you can even find a flag on this page!

3. Later i used 'stegsolve' to find the flag within the picture using image filter in stegsolve

```
terminal command: java -jar stegsolve.jar
```

![Spy result](https://github.com/m0nkeyt3ch/CTFs-Writeups/blob/master/HacktivityCon-CTF-2020/Image/spy-result.png?raw=true)      

4. we found the flag is 'flag{two_MAD_spies}'

FLAG: **flag{two_MAD_spies}**