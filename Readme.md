# MRadius-Manager

MRadius helps you quickly setting up an Radius Service 
for Meraki POC environments as well as
getting an cli based menue to manage it.


(written by thomas.sterber@meraki.net January 2023)

## What it is
      - Freeradius for Meraki POC environments
      - a CLI menue based tool 

## How it works

           ---------------                       ----------------     <----Radius Request------      -----------------
          |   PC/Laptop   |     -----ssh----->  |  Raspberry Pi  |                                  |  Meraki Device  |
           –––––––––––––––                       ––––––––––––––––     -----Radius Reply  ----->      –––––––––––––––––
        (MRadius Management)                      MRadius
           (install)
           (setup)
           (control)



## What is supported

      Auth Technologies
      - MAC Authentication
      - 802.1X
      - iPSK
      
      dynamic assignments
      - vlan id
      - vlan name
      - Group Policy
      - Group Policy ACL
      - Adaptive Polcy / SGT's
      
## Requirements
      - PC / Laptop with Python 3
      - Raspberry Pi

## Setup Raspberry Pi

      please have a look at the file "01_Raspberry_Setup.pdf"
      this will go step by step through the Raspi setup 
      you will need to run the MRadius-Tool


## Using MRadius

unzip MRadius package
    
      unzip M-Radius-Manager.zip
      

run MRadius-Manager

       cd /M-Radius-Manager
       chmod +x meraki-radius-manager.py
       ./meraki-radius-manager.py


use the M-Radius-Manager

      please see the file 02_M-Radius-Manager_101.pdf

