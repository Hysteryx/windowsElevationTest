# windowsElevationTest

- Start in admin > create a admin user : User = Test1 Pass = Attacktest1%
- Lancez le .exe en admin > créer un utilisateur admin : User = Test1 Pass = Attacktest1%

Pour le lancer en admin sans les perms, essayez de trouver un service windows qui se lance au démarage, rendez vous dans son chemin d'accès 
exemple : c:\Program Files\Logiciel\bin.exe
Remplacez bin.exe par ce .exe (que vous rennomez bin.exe)
Si vous ne pouvez pas, faites un fichier dans dans programs\[nomservice]\bin.exe car windows cherche dans programs avant program Files 
