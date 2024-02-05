## CHALLENGE 3 
### in this challenge i googled the text and understood that the text was encrypted with wingdings 1 method. so i decrypted the text and got the flag.
![](https://github.com/Jaifin-aloor/bios-recruitment-phase-2/blob/main/misc%20challenges/uploads/misc3flag.png)


## CHALLENGE 4
### 
'''py
import base64

pathin='misc4.txt'
pathout='misc444.txt'

with open(pathin , 'r') as nig:
    foo = nig.read()

    


for i in range(35):
    bar=base64.b64decode(foo.encode('utf-8'))
    bas=bar.decode('utf-8')
    foo=bas
    with open(pathout ,'a') as ger:
        ger.write(bas)
        ger.write('\n')

        
'''

