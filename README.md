# Pupy-LRAT-Writeup
Writing up about Pupy LRAT program. Also where I can mess with things in a safe manner. 

## Installation Instructions ##
* Open up terminal 
* cd to directory of choice and type the following:
  - git clone https://github.com/n1nj4sec/pupy; cd pupy
  - git submodule init
  - git submodule update
  - pip install -r pupy/requirements.txt
* **There might be an error for installation of the following command. you will need to do the following:**
  - sudo apt-get install libssl-dev swig python3-dev gcc  
  - pip install M2Crypto
  - pip install -r pupy/requirements.txt

## Gathering Payloads - OUTDATED IT WONT WORK ##
* wget https://github.com/n1nj4sec/pupy/releases/download/latest/payload_templates.txz
* tar xvf payload_templates.txz && mv payload_templates/* pupy/payload_templates/ && rm payload_templates.txz && rm -r payload_templates

## Key Findings ##
* pupy runs on Python 2.7 and that is a pain!
* 
