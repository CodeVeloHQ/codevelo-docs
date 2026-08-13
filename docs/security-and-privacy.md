# Security and privacy

CodeVelo treats security and privacy as operating responsibilities across discovery,
delivery, and support.

## Public documentation boundary

Public repositories do not intentionally contain:

- credentials, tokens, certificates, or secret values;
- production network topology or privileged configuration;
- customer source code, files, or identifying project details;
- internal incident, recovery, or access procedures; or
- private operational data and logs.

## Engineering direction

CodeVelo's platform architecture is designed around shared identity and authorization,
centralized secret governance, scoped service access, audit events, and separation of
sensitive values from ordinary application data.

The presence of an architectural capability does not guarantee that every component is
publicly available or appropriate for every engagement. Security controls are selected
and reviewed in the context of the deployed system.

## Vulnerability reporting

Do not open a public issue for a suspected vulnerability. Follow the instructions in
[the repository security policy](https://github.com/CodeVeloHQ/codevelo-docs/security/policy).
