<div align="center">

# 🔥 Agent Burn pour Windows

**Suivez votre usage de Claude Code et de Codex, vos limites d'abonnement et le rythme à ne pas dépasser, directement depuis la zone de notification de Windows.**

[**⬇️ Télécharger la dernière version**](../../releases/latest) · [Historique des versions](../../releases)

</div>

---

## Ce que ça fait

Agent Burn lit l'usage de vos outils de code IA **sur votre PC** et vous montre :

- 💸 **Combien vous consommez**, en équivalent API (aux tarifs publics) : par jour, semaine ou mois, par outil et par modèle.
- 📉 **Vos limites d'abonnement en direct** (session de 5 h et limite hebdomadaire pour Claude, limite de votre forfait pour Codex), avec :
  - le pourcentage restant,
  - une **ligne de rythme régulier à ne pas dépasser**,
  - un **code couleur** : vert si vous êtes en avance, rouge si vous êtes en retard,
  - un message du type *« La limite sera atteinte vers mer. 14 08:53. Restez sous 13,8 %/jour. »*
- 🧾 **L'historique de votre forfait Codex** (gratuit, Plus, Pro…) avec l'usage de chaque période.
- 🔔 **Une icône dans la zone de notification** : coût du jour et pourcentage restant d'un coup d'œil.
- 🔄 **Actualisation automatique** toutes les 2 minutes, et des mises à jour intégrées : un bouton « Rechercher une mise à jour » dans l'application.

| Outil suivi | Coûts et tokens | Limites en direct |
|---|---|---|
| **Claude Code** | ✅ | ✅ après connexion (voir plus bas) |
| **Codex** (OpenAI) | ✅ | ✅ si Codex est connecté à votre compte ChatGPT |
| **Antigravity** | ✅ | — |

## Installation

1. Allez dans [**Releases**](../../releases/latest) et téléchargez `Agent.Burn_…_x64-setup.exe`.
2. Lancez-le. L'installation est pour votre compte uniquement : **aucun droit administrateur** requis.
3. Windows peut afficher **« Windows a protégé votre ordinateur »**. C'est normal : le programme n'a pas de certificat commercial payant. Cliquez sur **« Informations complémentaires »**, puis **« Exécuter quand même »**.
4. L'application s'ouvre. Son icône flamme se trouve dans la zone de notification (parfois sous la flèche ^).

**Prérequis :** Windows 10 ou 11 en 64 bits. Windows 11 a tout ce qu'il faut ; sur Windows 10, le composant *WebView2* est parfois à installer.

## Se connecter pour voir les limites en direct

Les coûts et les graphiques de dépense s'affichent **sans rien configurer** : ils viennent des fichiers que vos outils écrivent déjà sur le PC.

Pour les **limites en direct**, l'outil doit être connecté à votre compte. Si ce n'est pas le cas, une carte *« Connectez-vous pour avoir plus de précision »* apparaît dans l'onglet de l'outil, avec un bouton **Se connecter** : votre navigateur s'ouvre, vous validez, et c'est tout. Aucune commande à taper.

Sans connexion, vous gardez tout le suivi des coûts, et pour Claude vous pouvez fixer un **budget hebdomadaire** pour suivre votre rythme.

## Mises à jour

Cliquez sur **« Rechercher une mise à jour »** en bas à gauche :
- *« Vous êtes à jour »* si vous avez la dernière version,
- *« Télécharger la mise à jour »* sinon : l'application la télécharge depuis GitHub, vérifie sa signature, l'installe et redémarre.

## Vie privée

- **Tout est calculé sur votre PC.** Aucun de vos fichiers n'est envoyé nulle part par Agent Burn.
- Les seuls échanges réseau sont : la lecture de vos limites auprès d'Anthropic ou d'OpenAI avec **vos propres identifiants**, et la recherche de mises à jour sur GitHub.
- Vos données de dépense restent les vôtres : personne d'autre que vous ne les voit.

## Ce qui n'est pas pris en charge

- **ChatGPT dans le navigateur** : seul **Codex** est suivi, pas vos conversations ChatGPT.
- **Cursor** et **Gemini CLI** : détectés quand ils sont installés, mais leur usage ne peut pas être calculé pour l'instant.
- Windows uniquement (une application existe séparément pour Mac).

## Crédits et licence

Agent Burn pour Windows s'appuie sur le projet open source [**Agent Burn**](https://github.com/Melvynx/agent-burn) de Melvynx (licence MIT), lui-même issu de [ccusage](https://github.com/ryoppippi/ccusage) de ryoppippi. Le moteur de calcul est le leur ; l'application Windows et son interface sont une réécriture.

Voir [LICENSE](LICENSE) et [THIRD-PARTY-LICENSES.txt](THIRD-PARTY-LICENSES.txt) pour les mentions de licence.

Projet indépendant, **non affilié** à Anthropic ni à OpenAI. « Claude » est une marque d'Anthropic ; « ChatGPT » et « Codex » sont des marques d'OpenAI.
