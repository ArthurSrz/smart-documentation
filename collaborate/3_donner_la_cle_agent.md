# Donner la clé à l'agent de Gilles 

On vous avait dit que Gilles était, en plus d'incompréhensible, difficile à joindre ? C'est pour ça qu'il a un agent, auquel il faut communiquer la clé. 


L'agent de Gilles va s'occuper de faire passer la clé SSH à Gilles.

Pour activer l'agent de Gilles : 

1. Ouvrez le PowerShell en tant qu'administrateur 

![powershell_admin](https://github.com/user-attachments/assets/85b6fcd8-7243-465e-94b6-9d52c24563cf)

2. Démarrez manuellement le SSH agent avec les commandes suivante : 

```powershell
Get-Service -Name ssh-agent | Set-Service -StartupType Manual
```

```powershell
Start-Service ssh-agent
```

3. Donnez la clé à l'agent de Gilles avec la commande suivante : 

```powershell
ssh-add C:\Users\your_pseudonym\.ssh\id_ed25519
```
