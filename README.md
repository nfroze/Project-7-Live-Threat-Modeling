# Tombola Winners Page Security Analysis

## Executive Summary

Security analysis of public winner disclosure practices on tombolaarcade.co.uk that could enable targeted social engineering attacks against customers.

## The Issue

Tombola's winners page publishes usernames and photos weekly, providing potential attackers with targeting data for social engineering attacks. Combined with information from public data breaches, this could enable sophisticated attacks that bypass technical controls.

## Key Findings

- **Vulnerability**: Public winner data enables victim identification
- **Attack Vector**: Social engineering targeting identified winners
- **Risk**: Particularly affects elderly/vulnerable customers
- **Mitigation**: Simple privacy controls can significantly reduce risk

## Documents

1. [`attack-scenario.md`](attack-scenario.md) - Demonstration of potential attack methodology
2. [`technical-analysis.md`](technical-analysis.md) - Analysis of vulnerability and attack chain
3. [`mitigations.md`](mitigations.md) - Recommended security improvements

## Purpose

This analysis demonstrates how publicly available information could be weaponised against customers, with practical recommendations for risk reduction.

## Evidence

[Click here](screenshots/tombola-winner-information.png) to see the live example of the exposed user data including usernames, profile photos, and win amounts.

---