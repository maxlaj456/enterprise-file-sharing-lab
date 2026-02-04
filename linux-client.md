## Linux Client — Remote Access & SMB Integration
### Objective

Mount a Windows SMB share and verify cross-platform file access.

### Mount Windows Share
Created mount directory: sudo mkdir -p /mnt/winshare

Mounted share using CIFS: sudo mount -t cifs //SERVER-IP/linuxshare /mnt/winshare -o username=<user>,vers=3.0

Verified contents: ls -l /mnt/winshare

Read authentication logs: cat /mnt/winshare/output.txt

Confirmed visibility of failed login events generated on the Windows server.

![Log of failed attempts](images/linux-client/log-failed-attempts.png) 
