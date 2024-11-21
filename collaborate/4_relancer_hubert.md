# Relancez Hubert, l'agent de Gilles

Hubvert, l'agent de Gilles, n'est pas exactement rigoureux. Le bal musette, ça use la mémoire. Rappelez lui de bien donner la clé à Gilles. 

Pour ajouter la clé sur Github : 

1. Sur Github, rendez-vous dans vos paramètres
2. Puis dans vos "SSH keys"

   
<img width="185" alt="Capture d’écran 2024-11-21 162926" src="https://github.com/user-attachments/assets/1b9dc26a-82a8-4eee-ba3e-b4be9442f3e0">


3. Récupérez la clé en exécutant dans votre terminal la commande suivante : 

```powershell
Get-Content ~/.ssh/id_ed25519.pub
```

4. Insérez cette clé dans Github en lui donnant un nom : 

<img width="511" alt="image" src="https://github.com/user-attachments/assets/6da7f402-081d-4126-a8a1-1f7da17f01c1">

C'est bon, Gilles a maintenant bien les clés. 
