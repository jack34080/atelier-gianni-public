# 🧠 Orchestrateur – Manuel d’utilisation

## Présentation
Le poste de commande de l’Atelier. Supervisez tous les modules, consultez les tests et les alertes.

## Prérequis
- Atelier GIANNI P. installé

## Ouverture
Cliquez sur **🧠 Orchestrateur** dans le Chat. La fenêtre de supervision s’ouvre.

## Barre latérale
- **12 modules** avec leur voyant (vert = OK, rouge = problème).
- **Cliquez sur un module** pour voir ses tests détaillés à droite.

## Boutons spéciaux
| Bouton | Voyant vert | Voyant rouge | Action |
|--------|-------------|--------------|--------|
| 🧪 Tests fonctionnels | Tous les tests OK | Au moins un test en erreur | Affiche tous les résultats |
| 🛡️ Alertes intégrité | Aucune alerte | Fichiers modifiés détectés | Affiche les alertes |
| 📋 Actions automatiques | Tout OK | Défaillances | Affiche les actions exécutées |

## Barre d’outils
| Bouton | Action |
|--------|--------|
| 🔄 Actualiser | Recharge tous les rapports |
| 🔗 Workflow test | Lance une collaboration entre modules |
| 📋 Copier le rapport | Copie tout le rapport dans le presse-papier |

## Problèmes courants
| Problème | Solution |
|----------|----------|
| Connexion impossible | Vérifiez que l’Atelier est bien lancé |
| Licence absente | Activez une licence incluant `orchestrateur` |