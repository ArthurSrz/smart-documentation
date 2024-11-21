# 3. Donner la clé à Hubert, l'agent du club de Cochinchine

On ne vous l'avait pas encore dit, mais le club de Cochinchine est extrêmement prisé. Avec l'essor des congès payés, tout le monde veut s'y rendre, tant et si bien qu'il faut passer par un agent de réservation, Hubert, qui va s'occuper de transférer la clé généré par Gilles au club. 

Pour sonner et réveiller Hubert, qui ne lésine pas sur les siestes : 

1. Ouvrez le PowerShell en tant qu'administrateur 

![powershell_admin](https://github.com/user-attachments/assets/85b6fcd8-7243-465e-94b6-9d52c24563cf)

2. Démarrez manuellement Hubert  avec les commandes suivante : 

```powershell
Get-Service -Name ssh-agent | Set-Service -StartupType Manual
```

```powershell
Start-Service ssh-agent
```

3. Donnez la clé à Hubert avec la commande suivante : 

```powershell
ssh-add C:\Users\your_pseudonym\.ssh\id_ed25519
```

Hubert a bien la clé en main. 

[La suite -->](4_donner_cle_club.md)
