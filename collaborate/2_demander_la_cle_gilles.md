# Récupérer la clé pour communiquer avec Gilles. 

On vous disait que personne ne comprenait Gilles. Tant et si bien qu'il faut une clé pour le comprendre. 

1. Pour voir si vous disposez déjà d'une clé pour parler avec Gilles, insérez la commande suivante dans votre terminal :

```bash
ls ~/.ssh/id_*.pub
```

2. Si elle n'existe pas, vous pouvez la créer avec la commande suivante : 

```bash
ssh-keygen -t ed25519 -C "your_email@google.com"
```

> **Info** :
> saisissez votre email Veltys à la place de `your_email@google.com`

Appuyez simplement sur 'Entrée' pour accepter l'emplacement de fichier par défaut et les options de phrase secrète. Après avoir généré la clé, elle sera enregistrée dans `~/.ssh/`.




