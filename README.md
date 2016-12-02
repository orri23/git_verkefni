#Hópverkefni

Þetta er hópverkefnið sem Kjartan og Kristófer unnu fyrir haustönn 2016

##Inngangur

Við notuðum Oracle VM VirtualBox til að setja upp tölvunar. Við notuðum Windows Server 2012, Windows 8.1 og Ubuntu server 16.10. Við 
settum upp DHCP, NAT og DNS. Við settum Serverinn upp sem Router og settum upp RIP. Tengdum 8 vélina við serverinn og Ubuntu.
Settum upp usera í active directory og settum upp group policy. 

###Það sem var notað

```
Oracle VM VirtualBox
Microsoft Windows Server 2012 R2
Microsoft Windows 8.1
Ubuntu 16.10
```

##Um verkefnið

Við vildum setja upp Windows server og tengja Windows 8 vél við hana, síðan myndum við tengja Ubuntu vél við Serverinn. Við settum upp LAN,
subnettuðum 172.31.0.0 Network þannig að subnet maskinn væri /26 og Windows 8 fengi frá .0 til 63 og Linux fengi .64 til .127. 
Við settum upp DHCP þannig að DHCP sér um að dreyfa út tölum. Settum upp DNS. Settum upp RIP svo að tölvunar tengdar við serverinn geta 
tengt við internetið.
Fyrir Windows 8 þá settum við upp Group Policy svo að við getum sett upp reglur á notendur.
Á Ubuntu eigum við að tengjast við Active Directory á Windows Serverinum

###Stillingar

Serverinn hefur þrjár netsnúrur, ein sem fer á netið í gegnum bridged connection, annar fyrir Windows vélina og hina fyrir Linux. 
Linux og WIndows vélin báðar hafa eina snúru sem tengist á serverinn.

##Credits

###Höfundar

Kjartan Már Andersen                    
Kristófer Orri Guðmundsson






