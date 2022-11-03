# ClamAV Signatures

## Summary
ClamAV body-based signatures are decoded and commited on a daily basis. By revealing the detection logic, the security concern can be better understood.

## How to use
- The 'signatures' folder contains the decoded signatures from these main and daily databases:
  - Extended (ndb, ndu)
  - Logical (ldb, ldu)
  - Container metadata (cdb)
- The 'firstseen.csv' file tracks the database of each signature.

## Useful links
- https://docs.clamav.net/manual/Signatures.html
- https://docs.clamav.net/manual/Signatures/LogicalSignatures.html
