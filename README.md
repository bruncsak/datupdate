get_datupdate -- script to extract virus signature DAT file update script for McAfee VirusScan Command Line from the documentation PDF file

The update script can be found in the vscl612upg.pdf file. This documentation file must be provided as argument to the get_datupdate script to extract it.
After the extraction the get_update script patches the update script for the following two items:

- fix an important race condition (running uvscan process hanging and burning the CPU) 
- replacement of the use of FTP protocol with HTTP protocol, for further detailes please visit: https://kc.mcafee.com/corporate/index?page=content&id=KB91260

It would be great if the update script could use HTTPS as well.
