# Kerberos

## Purpose

Assesses and secures Kerberos use in existing environments.

## Example contents

Checks for SPNs, delegation, and supported encryption types.

## Scope

AD DS installation belongs in `InfraAsCode`. Fixes for individual PingCastle findings belong in `../PingCastle`.

## Dependencies

Requires access to the relevant AD objects and any Kerberos events used by the tool. Changes require delegated permissions.
