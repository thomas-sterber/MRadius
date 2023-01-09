# MRadius-Manager
## What it is
      - Freeradius for Meraki POC environments
      - a CLI menue based tool 

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

## How it works

            **PC/Laptop**         -----ssh----->  **Raspberry Pi**   <----Radius Request------ **Meraki Device** 
       (MRadius Management)
           (install)
           (setup)
           (control)


## Using MRadius

unzip MRadius package
    
      unzip M-Radius-Manager.zip
      

run MRadius-Manager

       cd /M-Radius-Manager
       chmod +x meraki-radius-manager.py
       ./meraki-radius-manager.py


use the M-Radius-Manager

      please see the file 02_M-Radius-Manager_101.pdf

