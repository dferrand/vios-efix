_Last update: 2026/04/016_

# VIOS efix

List of efix to install on VIOS by version.

## 4.1.2.0

| Release | EOS | Next SP |
| ------- | --- | ------- |
| 2025.12.05 | 2028.12.31 | 2026.07.17 |

| efix | download | note |
| ---- | -------- | ---- |
| [libxml2 advisory 10](https://aix.software.ibm.com/aix/efixes/security/libxml2_advisory10.asc) | [download](https://aix.software.ibm.com/aix/efixes/security/libxml2_fix10.tar)||
| [Xorg advisory 5](https://aix.software.ibm.com/aix/efixes/security/xorg_advisory5.asc) | [download](https://aix.software.ibm.com/aix/efixes/security/xorg_fix5.tar)||
| [bind advisory 29](https://aix.software.ibm.com/aix/efixes/security/bind_advisory29.asc)| [download](https://aix.software.ibm.com/aix/efixes/security/bind_fix29.tar)| Only applies if bind.rte is installed (not the case by default) |
| ~~[perl advisory 12](https://aix.software.ibm.com/aix/efixes/security/perl_advisory12.asc)~~ | ~~[download](https://aix.software.ibm.com/aix/efixes/security/perl_fix12.tar)~~| ~~Installs with updateios~~ Superseded by advisory 13 |
| [openssh advisory 20](https://aix.software.ibm.com/aix/efixes/security/openssh_advisory20.asc)| [download](https://aix.software.ibm.com/aix/efixes/security/openssh_fix20.tar)||
| ~~[openssl advisory 45](https://aix.software.ibm.com/aix/efixes/security/openssl_advisory45.asc)~~ | ~~[download](https://aix.software.ibm.com/aix/efixes/security/openssl_fix45.tar)~~| Superseded by advisory 46|
| [openssl advisory 46](https://aix.software.ibm.com/aix/efixes/security/openssl_advisory46.asc) | [download](https://aix.software.ibm.com/aix/efixes/security/openssl_fix46.tar)||
| [perl advisory 13](https://aix.software.ibm.com/aix/efixes/security/perl_advisory13.asc) | [download](https://aix.software.ibm.com/aix/efixes/security/perl_fix13.tar)| Installs with updateios |
| ~~[python advisory 18](https://aix.software.ibm.com/aix/efixes/security/python_advisory18.asc)~~ | ~~[download](https://aix.software.ibm.com/aix/efixes/security/python_fix18.tar)~~| ~~Installs with updateios~~  Superseded by advisory 19|
| [postgres_advisory](https://aix.software.ibm.com/aix/efixes/security/postgres_advisory.asc) | [download](https://aix.software.ibm.com/aix/efixes/security/postgres_fix.tar) | Installs with updateios |
| [IBM.SoftwareRM memory leak](https://www.ibm.com/support/pages/node/7262728) | [download](https://aix.software.ibm.com/aix/ifixes/ij57520/) | Only needed if HMC is connected to a CMC that is part of a PEP 2.0 |
| [python advisory 19](https://www.ibm.com/support/pages/node/7269653?myns=swgother&mynp=OCSWG10&mynp=OCSSPHKW&mync=E&cm_sp=swgother-_-OCSWG10-OCSSPHKW-_-E) | [download](https://aix.software.ibm.com/aix/efixes/security/python_fix19.tar) | Installs with updateios |
