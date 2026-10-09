# VirtualScreen

**Français** · [English](#english)

<p align="center">
  <img src="images/virtualscreen.png" alt="VirtualScreen : un écran 16:9 découpé en deux zones et un écran ultra-large découpé en trois zones" width="100%">
</p>

<h3 align="center">Regardez, travaillez, jouez. En même temps.</h3>

<!-- VIDEO -->

VirtualScreen découpe votre écran en zones que Windows voit comme de vrais écrans.
Une série en plein écran dans un coin, votre travail à côté.

<p align="center"><a href="https://github.com/Mats-TH/VirtualScreen/releases/latest"><b>Télécharger la dernière version</b></a></p>

## Fonctionnalités

- **N'importe quel écran.** Bureau, portable, ultra-large ou téléviseur, un seul ou plusieurs.
- **De vrais écrans pour Windows.** Chaque zone a ses fenêtres, se maximise et passe en plein écran.
- **Préréglages ou sur mesure.** Un clic suffit, ou dessinez votre découpe et gardez-la.
- **Un éditeur en vraie grandeur.** Il s'ouvre en plein écran, sur tous vos écrans à la fois.
- **Ratios et zone principale.** Verrouillez un ratio (16:9, 21:9…) et choisissez la zone qui sert d'écran principal.
- **Vos séries en plein écran.** Netflix, Crunchyroll, Disney+ ou YouTube dans une zone, avec l'accélération matérielle et sans copie du contenu.
- **HDR et NVIDIA.** Des couleurs justes en HDR, et une optimisation NVIDIA qui respecte vos réglages.
- **Des bascules en douceur.** Une animation cache l'écran noir quand l'affichage change.
- **Raccourcis.** `Ctrl+Alt+S` active ou coupe la découpe. `Ctrl+Alt+Maj+F12` rétablit tout en urgence.
- **À votre goût.** Français ou anglais, thème clair ou sombre, test de fluidité intégré.

## En images

<p align="center">
  <img src="images/editeur-deux-ecrans.png" alt="L'éditeur plein écran ouvert sur deux écrans : un écran 16:9 en deux zones et un écran ultra-large en trois zones" width="100%"><br>
  <sub><b>L'éditeur</b>, ouvert sur tous vos écrans à la fois.</sub>
</p>

<table>
  <tr>
    <td width="50%" valign="top" align="center">
      <img src="images/installation.png" alt="Installateur de VirtualScreen : installation du pilote d'affichage en cours" width="100%"><br>
      <sub><b>Installation</b> : quelques clics, et c'est prêt.</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <img src="images/decoupe.png" alt="Réglages, onglet Découpe : un écran ultra-large en deux zones et les préréglages" width="100%"><br>
      <sub><b>Découpe</b> : un préréglage, ou la vôtre.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" align="center">
      <img src="images/general.png" alt="Réglages, onglet Général : raccourcis, démarrage, thème, langue, vidéos protégées, optimisation NVIDIA" width="100%"><br>
      <sub><b>Général</b> : raccourcis, langue, vidéos, NVIDIA.</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <img src="images/a-propos.png" alt="À propos : mises à jour, matériel, empreinte de VirtualScreen et test de fluidité" width="100%"><br>
      <sub><b>À propos</b> : mises à jour et test de fluidité.</sub>
    </td>
  </tr>
</table>

<sub>Images tirées des maquettes de l'application. Les noms d'écrans et les valeurs sont des exemples.</sub>

## Télécharger

- Rendez-vous dans les [releases](https://github.com/Mats-TH/VirtualScreen/releases/latest).
- Prenez `VirtualScreen-x.y.z-setup.exe`.
- Ce dépôt contient les versions publiées et leur documentation, pas le code source.

## Configuration requise

- Windows 11 22H2 ou plus récent, 64 bits (ni Windows 10, ni ARM).
- Une carte graphique DirectX 11 avec un pilote à jour.
- Les écrans à découper branchés sur la même carte graphique.
- Un compte administrateur pour l'installation.

## Installation

1. Téléchargez `VirtualScreen-x.y.z-setup.exe`.
2. Conseillé : vérifiez son empreinte avec `Get-FileHash` dans PowerShell. Elle doit correspondre à `SHA256SUMS.txt` de la même release.
3. Lancez l'installateur et suivez l'assistant.
4. Au premier lancement, acceptez l'installation du pilote d'écran virtuel.

**SmartScreen.** L'installateur n'est pas encore signé par une autorité reconnue.
Si Windows affiche « Windows a protégé votre ordinateur », cliquez sur « Informations complémentaires », puis « Exécuter quand même ».

**Certificat du pilote.** Le pilote d'écran virtuel est signé par le certificat de publication de VirtualScreen.

- L'installation l'ajoute aux certificats approuvés de l'ordinateur.
- Il ne sert qu'à la signature de code, à rien d'autre.
- Seul le certificat attendu (empreinte vérifiée) est ajouté.
- La désinstallation le retire.

## Désinstallation

- Paramètres de Windows → Applications → Applications installées → VirtualScreen → Désinstaller.
- L'affichage d'origine revient, le pilote et son certificat sont retirés.
- Vos réglages sont gardés, sauf si vous cochez « Supprimer aussi mes réglages ».

## Mises à jour

- VirtualScreen **propose** les nouvelles versions, il ne les impose jamais.
- Rien ne s'installe sans votre clic.
- Chaque téléchargement est vérifié (manifeste signé, empreinte SHA-256).
- Si une nouvelle version ne démarre pas, la précédente revient d'elle-même.
- Vous pouvez couper la recherche des mises à jour dans « À propos ».

## Confidentialité

- Rien ne quitte votre ordinateur. Aucune télémétrie, aucun compte, aucune publicité.
- Seule exception : une fois par jour, VirtualScreen lit le fichier de mise à jour publié ici, sur GitHub (désactivable).
- Cette lecture ne transmet que votre adresse IP et la version de VirtualScreen, comme toute connexion à GitHub.

## Aide et sécurité

- **Un problème d'affichage ?** `Ctrl+Alt+Maj+F12`, ou `Win+P` puis « Écran du PC uniquement ».
- **Un bug, une idée ?** Dites-le dans les [Issues](https://github.com/Mats-TH/VirtualScreen/issues).
- **Une faille de sécurité ?** Jamais dans une issue publique : voir [SECURITY.md](SECURITY.md).

## Licence

- Logiciel propriétaire gratuit, © 2026 Mats Thiebaud, tous droits réservés : voir [LICENCE.md](LICENCE.md).
- Les composants de tiers sont listés dans l'application (« À propos » → « Mentions et licences ») et dans la nomenclature logicielle (SBOM) de chaque release.

---

<a id="english"></a>

# VirtualScreen (English)

<p align="center">
  <img src="images/virtualscreen.png" alt="VirtualScreen: a 16:9 screen split into two zones and an ultrawide screen split into three zones" width="100%">
</p>

<h3 align="center">Watch, work, play. All at once.</h3>

<!-- VIDEO -->

VirtualScreen splits your screen into zones that Windows sees as real displays.
A show playing full screen in one corner, your work right next to it.

<p align="center"><a href="https://github.com/Mats-TH/VirtualScreen/releases/latest"><b>Download the latest version</b></a></p>

## Features

- **Any screen.** Desktop monitor, laptop, ultrawide or TV, one or several.
- **Real displays for Windows.** Each zone has its own windows, maximizes and goes full screen.
- **Presets or your own layout.** One click, or draw your split and save it.
- **A life-size editor.** It opens full screen, on all your screens at once.
- **Ratios and primary zone.** Lock a ratio (16:9, 21:9…) and pick the zone that acts as your main display.
- **Your shows, full screen.** Netflix, Crunchyroll, Disney+ or YouTube in a zone, with hardware acceleration and without copying the content.
- **HDR and NVIDIA.** Accurate colors in HDR, and an NVIDIA optimization that leaves your settings alone.
- **Smooth switching.** An animation hides the black screen while the display changes.
- **Shortcuts.** `Ctrl+Alt+S` turns splitting on or off. `Ctrl+Alt+Shift+F12` restores everything in an emergency.
- **Your way.** English or French, light or dark theme, built-in smoothness test.

## Screenshots

<p align="center">
  <img src="images/editeur-deux-ecrans.png" alt="The full-screen editor open on two screens: a 16:9 screen in two zones and an ultrawide screen in three zones" width="100%"><br>
  <sub><b>The editor</b>, open on all your screens at once.</sub>
</p>

<table>
  <tr>
    <td width="50%" valign="top" align="center">
      <img src="images/installation.png" alt="VirtualScreen installer: display driver installation in progress" width="100%"><br>
      <sub><b>Installation</b>: a few clicks and you're set.</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <img src="images/decoupe.png" alt="Settings, Split tab: an ultrawide screen in two zones and the presets" width="100%"><br>
      <sub><b>Split</b>: a preset, or your own.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" align="center">
      <img src="images/general.png" alt="Settings, General tab: shortcuts, startup, theme, language, protected videos, NVIDIA optimization" width="100%"><br>
      <sub><b>General</b>: shortcuts, language, videos, NVIDIA.</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <img src="images/a-propos.png" alt="About: updates, hardware, VirtualScreen footprint and smoothness test" width="100%"><br>
      <sub><b>About</b>: updates and smoothness test.</sub>
    </td>
  </tr>
</table>

<sub>Images taken from the app's design mockups, shown in French. Screen names and values are examples.</sub>

## Download

- Go to the [releases](https://github.com/Mats-TH/VirtualScreen/releases/latest).
- Get `VirtualScreen-x.y.z-setup.exe`.
- This repository holds the published versions and their documentation, not the source code.

## Requirements

- Windows 11 22H2 or later, 64-bit (not Windows 10, not ARM).
- A DirectX 11 graphics card with an up-to-date driver.
- The screens you split connected to the same graphics card.
- An administrator account for installation.

## Installation

1. Download `VirtualScreen-x.y.z-setup.exe`.
2. Recommended: check its fingerprint with `Get-FileHash` in PowerShell. It must match `SHA256SUMS.txt` in the same release.
3. Run the installer and follow the wizard.
4. On first launch, accept the virtual display driver installation.

**SmartScreen.** The installer is not yet signed by a recognized authority.
If Windows shows "Windows protected your PC", click "More info", then "Run anyway".

**Driver certificate.** The virtual display driver is signed with the VirtualScreen publisher certificate.

- Installation adds it to the computer's trusted certificates.
- It is restricted to code signing, nothing else.
- Only the expected certificate (fingerprint checked) is added.
- Uninstallation removes it.

## Uninstallation

- Windows Settings → Apps → Installed apps → VirtualScreen → Uninstall.
- Your original display comes back, the driver and its certificate are removed.
- Your settings are kept, unless you check "Also delete my settings".

## Updates

- VirtualScreen **offers** new versions, it never forces them.
- Nothing installs without your click.
- Every download is verified (signed manifest, SHA-256 fingerprint).
- If a new version fails to start, the previous one comes back on its own.
- You can turn update checks off in "About".

## Privacy

- Nothing leaves your computer. No telemetry, no account, no ads.
- One exception: once a day, VirtualScreen reads the update file published here, on GitHub (can be turned off).
- That read only sends your IP address and the VirtualScreen version, like any connection to GitHub.

## Help and security

- **Display trouble?** `Ctrl+Alt+Shift+F12`, or `Win+P` then "PC screen only".
- **A bug or an idea?** Tell us in [Issues](https://github.com/Mats-TH/VirtualScreen/issues).
- **A security vulnerability?** Never in a public issue: see [SECURITY.md](SECURITY.md).

## License

- Free proprietary software, © 2026 Mats Thiebaud, all rights reserved: see [LICENCE.md](LICENCE.md) (the French version prevails).
- Third-party components are listed in the app ("About" → "Notices and licenses") and in the software bill of materials (SBOM) of each release.
