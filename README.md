# ENERGO RADAR

Šifrovaný kokpit (dotace · legislativa · leady). Obsah je AES-GCM blob,
klíč se odvozuje z hesla přes PBKDF2 (200 000 iterací). Bez hesla se nedá nic přečíst.

Zdrojový kód a build: lokální repo `energo-radar` (`./deploy.sh`).
