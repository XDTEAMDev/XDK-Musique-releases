# 🎧 XDK Musique — pour les DJ de la radio XDK

Mixe en direct avec **Virtual DJ** sur la radio de la TEAM XDK : **https://radio.winfordfa.fr** et le salon vocal
**🎧・DJ LIVE** du Discord XDK TEAM GAMES.

## ⬇️ Télécharger
**[XDK-Musique.exe (dernière version)](https://github.com/XDTEAMDev/XDK-Musique-releases/releases/latest/download/XDK-Musique.exe)**
— Windows 10 / 11 (64 bits), un seul fichier, rien à installer.

Au premier lancement, Windows peut afficher « Windows a protégé votre ordinateur » : clique sur
*Informations complémentaires* puis *Exécuter quand même*. L'empreinte SHA-256 de chaque version est dans ses notes.

## 🚀 Passer en direct
1. **Ta clé DJ** : XDK Vito t'ajoute comme DJ sur le Discord XDK TEAM GAMES ; le bot **XDK Team Games** t'envoie ta
   clé (`XDKDJ-…`) en message privé. Dans XDK Musique : ⚙️ Réglages › **Clé DJ** › colle › *Enregistrer* › *Tester* (✅).
2. **Virtual DJ**, une seule fois : *Diffusion* › *Serveur* :

   | Champ | Valeur |
   |---|---|
   | Protocole | **IceCast** |
   | URL du serveur | `127.0.0.1` |
   | Port | `8000` |
   | Adresse Mount | `/live` |
   | Connexion | `source` |
   | Mot de passe | ce que tu veux |

3. Garde **XDK Musique ouvert**, puis clique sur **DÉMARRER DIFFUSION** dans Virtual DJ : tu es en direct.

Bon à savoir :
- Un seul DJ à la fois sur la radio : si un autre DJ mixe, attends la fin de son set.
- Si Internet coupe pendant ton set, ton son est gardé et repart tout seul.
- Ta clé est personnelle : ne la donne à personne (XDK Vito peut la retirer et t'en refaire une).
- Ta clé est chiffrée pour ton compte Windows (`%LOCALAPPDATA%\XDK Musique`) et ne quitte pas ton PC, sauf pour
  se connecter à la radio XDK.
- XDK Musique te prévient quand une nouvelle version sort.
- N'envoie que de la musique que tu as le droit de diffuser.

---
Ce dépôt ne contient que les versions à télécharger de XDK Musique (logiciel de la TEAM XDK).
