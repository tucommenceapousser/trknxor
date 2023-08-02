# xorshell



Reject all things fancy, Only encoder PHP webshell to bypass WAF using XOR operations.



## Usage

```
Usage：python3 -m/--method [GET\POST] -p/--password [password] -o/--ouput [output filename]
```



## Example

Generate a shell with default parameters

```
./xor.py
```
## launch web interface
```
./xor
```
if flask isnt installed launch:
```
pip install -r req.txt --force
```
![Example](/image/example1.jpg)



Generate a shell ,  use POST as method and  "c1" as password , Output to file with name "xor_shell_eval.php"

```
./xor.py -m post -p c1 -o xor_shell_eval.php
```

![example2](/image/example2.jpg)



## Show

A simple show

![example3](/image/example3.png)



VirusTotal result

![VT](/image/VT.png)


## Refer

XORpass - https://github.com/devploit/XORpass  
