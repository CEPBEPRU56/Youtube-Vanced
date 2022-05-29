Windows Registry Editor Version 5.00
;Отключить Cortana и все дочерние процессы.
;Подробное описание
;Если вы не пользуетесь голосовым помощником Cortana, можете воспользоваться твиком ниже. 
;Под страны СНГ Cortana не адаптирована, но всё равно расходует ресурсы компьютера. 
;Крайне рекомендуется применить твик 11 в 1.
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Speech_OneCore\Preferences]
"ModelDownloadAllowed"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Search]
"AllowCloudSearch"=dword:00000000
"AllowCortana"=dword:00000000
"AllowSearchToUseLocation"=dword:00000000
"ConnectedSearchUseWeb"=dword:00000000
"DisableWebSearch"=dword:00000001

[HKEY_CURRENT_USER\Software\Microsoft\InputPersonalization]
"RestrictImplicitInkCollection"=dword:00000001
"RestrictImplicitTextCollection"=dword:00000001

[HKEY_CURRENT_USER\Software\Microsoft\InputPersonalization\TrainedDataStore]
"HarvestContacts"=dword:00000000

[HKEY_CURRENT_USER\Software\Microsoft\Personalization\Settings]
"AcceptedPrivacyPolicy"=dword:00000000

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Windows Search]
"CortanaConsent"=dword:00000000
