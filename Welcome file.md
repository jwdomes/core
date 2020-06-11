# BET Documentation

## Docker
* [Docker Desktop Installation Instructions]([http://nsc-ldsk-c1-03.cis1.cisr.uscis.dhs.gov/prefserver/Documentation/Docker%20for%20Desktop%202.2.0.3%20Install.pdf](http://nsc-ldsk-c1-03.cis1.cisr.uscis.dhs.gov/prefserver/Documentation/Docker%20for%20Desktop%202.2.0.3%20Install.pdf))

## Certificates
On AWS-BET-BD02 (10.103.

## Services
### BET.Appointment.Ingest
* Windows Service
* 



To be organized:

Appointment Detail: BET <=> WCF <= DB
BET Config: BET <=> WCF <=> DB
BET Report: BET <=> WCF <= DB

Encounter Processing: BET => WCF => S3 -> CPMS | WCF => DB **uses JSON

BET Verify: BET => WCF => ESB(IDENT) | BET <= WCF <= ESB(IDENT) **uses XML

Appointment Ingest: WinService <= ESB (NASS) | WinService => CPMS Appointment Notice service **uses XML
Encounter Ingest: WinService <= SQS | WinService => DB **uses JSON (receipt from CPMS on Encounter success)

BaaS CA Service: BET => WCF => S3 | WCF => DB
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzNzUwMTIwNjMsLTcxMjU3MTcyMyw4Mj
U0MTA0NTIsMTA1MDk1MTk5MSwxNTMyMzY3ODk0LC0zMzI0NTUz
NjNdfQ==
-->