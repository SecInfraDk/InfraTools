# ActiveDirectory

## Purpose

Provides tools for operating and securing existing Active Directory domains.

## Example contents

Risk reviews in `Assessment`, configuration changes in `Hardening`, cleanup in `Maintenance`, and recurring exports in `Reporting`.

## Scope

Domain controller installation and promotion belong in `InfraAsCode/BuildScripts/Services/ADDS`. PingCastle-specific remediation belongs in `../Security/PingCastle`.

## Dependencies

Requires domain access, applicable AD tooling, and read or change permissions for the operation.
