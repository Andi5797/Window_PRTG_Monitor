# Window_PRTG_Monitor

**Install Packet:**
https://drive.google.com/file/d/1VAM2NIKQYol2tvPwNVKnJi38ruG4we4E/view?usp=drive_link

`Step 1:` Run setup. it will force you enter an email address. enter anything that looks like an email address, like "abc@abc.com"

`Step 2:` Now it will require license name and key. request one from their webserver. name doesnt matter, "prtgtrial" is fine.
   this will contact their server and activate the (trial) license.

`Step 3:` Choose `Custom` (**NOT Express**); paths are your choice; choose `skip auto-discovery`

`Step4 :` Stop services, eg via powershell: 
```
Get-Service PRTG* | Stop-Service
```

`Step 5:` Copy directory structure from "crack" to your install dir. this will not overwrite files, thats fine.

`Step 6:` run keygen. patch hosts file.

`Step 7:` adjust settings to your liking. most people will want Type "Site License" / "XL5", and exp. date / maintenance both set to 2099

`Step 8:` Choose "save license", overwrite the existing activation.dat. if you have problems with permissions, save it somewhere else and overwrite it manually.

`Step 9:` Start services again, eg 
```
Get-Service PRTG* | Start-Service
```

.. enjoy

***IMPORTANT***: Do not upgrade version application


