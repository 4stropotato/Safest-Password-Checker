# Safest-Password-Checker

 *** [ INTRODUCTION ] ***
This is one of the first coolest project that I made when I started coding Python. The reason why this is the safest password checker is; It doesn't give the complete hash of your password. It sends the first characters of your hash and compare it with the results. from the https://haveibeenpwned.com API. Because we believe that there is nothing safe in the internet. :) -4stropotato


 *** [ INSTRUCTIONS ] ***

 On your terminal,
'python3 '.\Safest Password Checker.py' [your password here]'

Let's try 4stropotato:
'python3 '.\Safest Password Checker.py' 4stropotato'


As of October 2021, This was the result:
'4stropotato Was not found. Carry on!'

Or try multiple password separated by white spaces:
'python3 '.\Safest Password Checker.py' 4stropotato shinji yuyu'

'''ps1
4stropotato Was not found. Carry on!
shinji was found 5206 times... You should change your password
yuyu was found 1392 times... You should change your password
Done!
'''