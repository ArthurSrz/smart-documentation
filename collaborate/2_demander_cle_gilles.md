# Demander à Gilles de générer une clé pour pouvoir communiquer avec le club de Cochinchines . 

Pour pouvoir vous réserver votre place au "club de Cochinchines", Gilles va devoir créér une clé. Cette clé est le seul moyen de pouvoir communiquer avec le club de Cochinchines. Le seul et l'unique moyen. 

Pour demander à Gilles de créer une clé : 

1. Vérifiez si vous disposez déjà d'une clé. Pour cela, insérez la commande suivante dans votre terminal :

```bash
ls ~/.ssh/id_*.pub
```

2. Si elle n'existe pas, vous pouvez la créer avec la commande suivante : 

```bash
ssh-keygen -t ed25519 -C "your_email@google.com"
```

> **Info** :
> saisissez votre email Veltys à la place de `your_email@google.com`. Eh oui, il faut bien que le club de Cochinchines puisse vous contacter si jamais la suite René Cotty n'est plus disponible. 

Appuyez simplement sur 'Entrée' pour accepter l'emplacement de fichier par défaut et les options de phrase secrète. Après avoir généré la clé, elle sera enregistrée dans `~/.ssh/`.

Gilles vient bien de générer une clé qui va lui permettre de communiquer avec le club. 


3. [La suite -->](3_donner_la_cle_hubert.md)
