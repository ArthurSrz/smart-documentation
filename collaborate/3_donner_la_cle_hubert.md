# Donner la clé à Hubert, l'agent de Gilles 

On vous avait dit que Gilles était, en plus d'incompréhensible, difficile à joindre ? C'est pour ça qu'il a un agent, Hubert, auquel il faut communiquer la clé. 

Hubert, l'agent de Gilles va s'occuper de faire passer la clé SSH à Gilles.

Pour sonner et activer Hubert, qui ne lésine pas sur les siestes : 

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
