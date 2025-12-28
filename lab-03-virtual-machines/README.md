# LAB 03 – Azure Virtual Machines

## Objective
Deploy and manage an Azure Virtual Machine with basic monitoring and cost control.

## Scope
- Azure Virtual Machines
- VM sizing and regions
- Auto-shutdown
- Azure Monitor (basic metrics)

## Architecture
- Subscription
- Resource Group: rg-lab-03
- Virtual Network
- Subnet
- Virtual Machine (Linux or Windows)

## Steps (High-level)
1. Created a Virtual Network and subnet
2. Deployed a Virtual Machine using a low-cost SKU
3. Enabled auto-shutdown to control costs
4. Reviewed VM metrics in Azure Monitor

## Issues / Observations
- VM size selection directly impacts cost
- Metrics are available shortly after deployment

## Key Takeaways
- Virtual Machines require proper sizing to avoid unnecessary costs
- Auto-shutdown is essential in non-production environments
- Monitoring should be enabled immediately after deployment
