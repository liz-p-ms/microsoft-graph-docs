---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Mail

# A UPN can also be used as -UserId.
Get-MgUserMailFolderChildFolder -UserId $userId -MailFolderId $mailFolderId -Includehiddenfolders true  -OutFile $outFileId

```