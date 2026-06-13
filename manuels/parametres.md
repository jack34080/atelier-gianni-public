# ⚙️ Paramètres – Manuel d’utilisation

## Présentation
Configurez toutes les clés API, les tokens externes et votre licence.

## Prérequis
- Atelier GIANNI P. installé

## Clés API DeepSeek
Vous pouvez enregistrer jusqu’à 4 clés DeepSeek. L’Atelier utilise automatiquement la première clé valide.

1. Collez votre clé dans le champ correspondant.
2. Cliquez sur **Tester** pour vérifier qu’elle fonctionne.
3. Le voyant passe au vert si la clé est valide.

## Autres plateformes
- **OpenAI** : si vous possédez une clé OpenAI.

## Mode réel
Activez ce mode pour autoriser les actions réelles (push GitHub, emails). Désactivé = simulation.

## Tokens externes
- **GitHub** : token d’accès personnel pour les déploiements.
- **Dépôt** : nom du dépôt GitHub (exemple : `jack34080/atelier-gianni`).
- **Reddit / Email** : pour des fonctionnalités futures.

## Licence
Collez votre licence (format JSON) et cliquez sur **Activer**. La liste des licences actives s’affiche en dessous.

## Problèmes courants
| Problème | Solution |
|----------|----------|
| Clé testée invalide | Vérifiez qu’elle commence par `sk-` et qu’elle est active |
| Licence refusée | Vérifiez le format JSON (guillemets, virgules) |