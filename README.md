##  Ajay's DEFI Kingdom

This is my first module of Avalanche Advance project submission where I have created a local subnet using WSL - Ubuntu and then I have deployed the code provided on the Metacrafter's project page to this local subnet.

## Description

The code provided by Metacrafters contains two contracts - ERC20 and Vault and one interface - IERC20. In the ERC20 contract we are able to do basic ERC20 functions like mint, burn , approve, transfer, transferFrom . In the Vault contract we are able to deposit and withdraw the specified number of shares.

## Token Details
- Name: Ajay's DEFI Kingdom
- Symbol: ADK

## Subnet Details
- Name - mySubnet
- Chain ID - 9900
- Symbol - AMG

## Getting Started
 
### Creating Subnet
 
* In your Ubuntu terminal , firstly install the avalanche CLI
* export the path
* create a subnet :

```shell
avalanche subnet create mySubnet
```
* deploy the subnet :
```shell
avalanche subnet deploy mySubnet
```

## Executing Code

- Copy and paste the code in remix IDE
- Change the environment to injected provider and connect your metamask account
- deploy each contract by confirming transaction.

## Authors
 
Ajay SS
 
[0j0y1512@gmail.com]
 
## License
 
This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
