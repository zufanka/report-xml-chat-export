# Report.xml chat export

Parse chats extracted from an .ufdr image made by the Cellebrite UFED (Universal Forensic Extraction Device) system.

```bash
unzip image.ufdr
```

After the unzipping, you are left with a couple of folders and a `report.xml`. This file contains data from the mobile device. The biggests parts of this xml are:
* `taggedFiles`: list of all the files in the phone
* `decodedData`: e.g. instant messages, location, calls, contacts, installed applications, notes, passwords, sms, visited pages

This jupyter notebook exports instant messages.
