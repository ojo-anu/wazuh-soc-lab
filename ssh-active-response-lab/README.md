# SSH Brute Force Detection & Active Response

## Project Overview
This lab demonstrates how Wazuh detects SSH brute-force attempts and automatically blocks the attacker IP.

## What I Did
- Installed Wazuh agent
- Enabled SSH logging
- Triggered failed login attempts
- Configured Active Response
- Blocked attacker IP automatically

## Result
After 5 failed login attempts, the attacker IP was blocked and could no longer access the server.
