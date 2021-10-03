# Safest-Password-Checker

 *** [ INTRODUCTION ] ***

This is one of the first coolest project that I made when I started coding Python. The reason why this is the safest password checker is; It doesn't give the complete hash of your password. It sends the first characters of your hash and compare it with the results. from the https://haveibeenpwned.com API. Because we believe that there is nothing safe in the internet. :) -4stropotato


 *** [ INSTRUCTIONS ] ***

In your terminal,
```BASH
git clone https://github.com/4stropotato/Safest-Password-Checker
cd Safest-Password-Checker
```

And then run the python file.

```BASH
python3 pwcheck.py [your password here]
````

Let's try 4stropotato:
```BASH
python3 pwcheck.py 4stropotato
````

As of October 2021, This was the result:
```BASH
4stropotato Was not found. Carry on!
````

Or try multiple password separated by white spaces:
```BASH
python3 pwcheck.py 4stropotato shinji yuyu
```

And the result was:
```BASH
4stropotato Was not found. Carry on!
shinji was found 5206 times... You should change your password
yuyu was found 1392 times... You should change your password
Done!
```