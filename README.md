# Chain of Custody

The inspection workflow uses an AWS entry role. Its OIDC namespace hint is `chain-goaton-ctf`. A clue is available at SSM parameter `/ctf/q3/hint`. The flag is in Secrets Manager at `ctf/q3/flag`.

Trace the role chain and policy versions. Keep flag values out of public Actions logs.
