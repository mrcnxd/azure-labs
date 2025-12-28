
# LAB 02 – Entra ID Users & RBAC

## Objective
Implement role-based access control using Entra ID users and groups.

## Scope
- Entra ID users
- Entra ID groups
- RBAC role assignments

## Architecture
- Subscription
- Resource Group: rg-lab-02
- Entra ID user
- Entra ID group
- RBAC: Reader role

## Steps (High-level)
1. Created an Entra ID user
2. Created a security group
3. Assigned Reader role at Resource Group scope
4. Tested access with the new user

## Issues / Observations
- Access changes may take a few minutes to propagate

## Key Takeaways
- RBAC should always be assigned to groups, not individual users
- Scope selection is critical for least privilege
