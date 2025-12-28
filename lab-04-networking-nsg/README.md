# LAB 04 – Networking and Network Security Groups

## Objective
Secure Virtual Machine network access using Azure networking and NSG rules.

## Scope
- Virtual Networks
- Subnets
- Network Security Groups (NSG)
- Inbound traffic control

## Architecture
- Subscription
- Resource Group: rg-lab-04
- Virtual Network
- Subnet
- Network Security Group
- Virtual Machine

## Steps (High-level)
1. Created a Virtual Network with a dedicated subnet
2. Associated an NSG with the subnet
3. Configured inbound NSG rules (SSH or RDP)
4. Tested connectivity from an external client

## Issues / Observations
- NSG rule priority affects traffic flow
- Incorrect rules can block all inbound access

## Key Takeaways
- NSGs are the first line of defense for network access
- Least privilege should be applied to inbound rules
- Always test access after NSG changes
