
standard GPv2 (general prupose)
Premium 
- Block Blob
- Page blob
- Files
Only use for above purpose

redundancy 
- LRS 3 copies in the same building
- ZRS 3 copies over availabily zones (different buildings)
- GRS 3 copies in the primairy location (LRS) and 3 (LRS) in the paired region.
- GZRS 3 copies in the primary location (ZRS) and 3 copies in the secondairy location

[!information]
With premium only LRS and ZRS are available

Services
- BLOB (unstructured data)
    - Block
        - access tiers:
            - Hot
            - Cold
            - Archive (not online)
        - life cycle management can manage data between tiers depanding on usage
    - Page (made op pages)
        - Disk (used in vm's for example)
            - type
            - size
        - each disk has different tiers, size, iops and troughput
    - Append (addid to it)
- BLOB lives in coinaiers
- Files
    - SMB/NFS
        - Contains shares and files
        - Azure filesync
- Queues First in first out
- Table Key value pairs

Unstructured data use BLOB
storage for vms use disk (page)


[!information]
Access tiers are cheaper down the row, but transactions are more expenvice
