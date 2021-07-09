# Hashcat-Writeup
A very rough draft of how to use Hashcat program. Also where I can mess with things in a safe manner. 

## Requirements ##
* Kali Linux VM
* rockyou.txt 

## Things that can make life easier ##
* `hashcat -h | grep '[ANY HASH YOU WANT]`
* There's a lot of things in the man page, this helps find the hash you want to add for your mode

# Basic Structure of Hashcat Command #
* This is for dictionaries
* `hashcat -m [Hash Type] [Path to the Hash File you want to break].txt [Path to your wordlist].txt --show`
* Example
* `hashcat -m 1000 /home/kali/Desktop/Hashes.txt /home/kali/Downloads/rockyou.txt --show`
* -m represents the type of hash

# Common Hashes #
* NTML '-m 1000'
* MD5 '-m 0'
* MD4 '-m 900'
* SHA1 '-m 100'
