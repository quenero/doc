---
description: >-
  Setup Quenero Masternode
---


To setup a masternode in he quenero network is very easy

- Download the Quenero wallet and get a VPS with a public IP and run the wallet daemon with the below command

```text
./quenerod --masternode --storage-server-port 23231 --masternode-public-ip 123.432.4.12
```

Then enter the below code once you have a full synec with the quenero nework

```text
masternode_registration
```

```text
Current supernode requirement: 24935.158006499262 quenero
Will the operator contribute the entire supernode? (Y/Yes/N/No/C/Cancel): yes
```

```text
Enter the quenero address for the solo supernoder (B/Back/C/Cancel): 4ATDk..............ZdBmUc9qhMuSfVoUut7oXR
```

```text

Summary:
Operating costs as % of reward: 100%
Contributor     Address  Contribution       Contribution(%)
___________     _______  ____________       _______________
Operator        4ATDkM   24935.158006499262 100.000000000

Because the actual requirement will depend on the time that you register, the
amounts shown here are used as a guide only, and the percentages will remain
the same.

Do you confirm the information above is correct? (Y/Yes/N/No/B/Back/C/Cancel): yes
```

```text
register_masternode 18446744073709551612 4ATD8ckmAb99m6essae1K2jd3hwi4e5ro6ks7hfkloravfdSMSsjaJnAZdBmUc9qhMuSfVoUut7oJH 18446744073709551612 170105960 b739950aad754824f442258360ad5d941f33ccb528b0541d0b23 942932d811b9a7222f37324ca9f514c60067688d7b8e8a35ace03c1f1d6d7c1a49db6f563241d6875b848c997d79d75899f2885970402178d4fd20b

This registration expires at 2021-08-26 07:26:00 PM.
This should be in about 2 weeks, if it isn't, check this computer's clock.
Please submit your registration into the blockchain before this time or it will be invalid.

```

