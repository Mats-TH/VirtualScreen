# Sécurité de VirtualScreen

**Français** · [English](#english)

## Signaler une vulnérabilité

Merci de signaler toute faille de sécurité **en privé**, jamais dans une issue publique :

1. Ouvrez l'onglet [Security](https://github.com/Mats-TH/VirtualScreen/security) de ce dépôt.
2. Cliquez sur **« Report a vulnerability »** (signalement privé des vulnérabilités de GitHub).
3. Décrivez le problème : version de VirtualScreen (« À propos »), version de Windows, étapes pour reproduire, effet observé et, si possible, impact estimé.

Seuls vous et le mainteneur voyez ce signalement. Il n'y a pas d'adresse électronique de contact : passez uniquement par ce formulaire.

## Délais indicatifs

| Étape | Délai |
|---|---|
| Accusé de réception | 5 jours ouvrés |
| Première évaluation (confirmé ou non, gravité) | 14 jours |
| Correctif d'une faille grave ou critique | 30 jours, au mieux de nos possibilités |
| Publication de l'avis de sécurité | avec la version corrigée, ou au plus tard 90 jours après le signalement, en accord avec vous |

VirtualScreen est maintenu par une seule personne : ces délais sont des objectifs, pas des engagements contractuels. Vous serez tenu informé de l'avancement et, si vous le souhaitez, remercié dans l'avis.

## Versions prises en charge

| Version | Correctifs de sécurité |
|---|---|
| Dernière version publiée (1.x) | Oui |
| Versions antérieures | Non : installez la dernière version |

Les correctifs sont livrés sous forme de **nouvelle version**, jamais en modifiant une version déjà publiée (releases immuables). Les notes de chaque version ont une partie « Sécurité » quand elle corrige une faille, et VirtualScreen le signale dans sa notification de mise à jour. Les mises à jour sont proposées par l'application (« À propos ») et vérifiées avant installation : manifeste signé (ECDSA P-256) et empreinte SHA-256 de l'installateur.

**Durée de support** : des correctifs de sécurité sont prévus pendant au moins 2 ans après la publication de la dernière version.

## Périmètre

Concernent ce programme : l'application VirtualScreen, son gardien, son pilote d'écran virtuel SplitVdd, son installateur et son mécanisme de mise à jour. Les failles de Windows, des pilotes graphiques ou de Microsoft Edge WebView2 sont à signaler à leurs éditeurs.

Merci de ne pas accéder aux données d'autres personnes, de ne pas dégrader le service de GitHub et de nous laisser le temps de corriger avant toute divulgation.

---

<a id="english"></a>

# VirtualScreen security

## Reporting a vulnerability

Please report any security vulnerability **privately**, never in a public issue:

1. Open the [Security](https://github.com/Mats-TH/VirtualScreen/security) tab of this repository.
2. Click **"Report a vulnerability"** (GitHub private vulnerability reporting).
3. Describe the problem: VirtualScreen version ("About"), Windows version, steps to reproduce, observed effect and, if possible, estimated impact.

Only you and the maintainer can see the report. There is no contact email address: please use this form only.

## Target timelines

| Step | Timeline |
|---|---|
| Acknowledgement | 5 business days |
| Initial assessment (confirmed or not, severity) | 14 days |
| Fix for a high or critical vulnerability | 30 days, on a best-effort basis |
| Security advisory published | with the fixed version, or at the latest 90 days after the report, in agreement with you |

VirtualScreen is maintained by a single person: these timelines are goals, not contractual commitments. You will be kept informed and, if you wish, credited in the advisory.

## Supported versions

| Version | Security fixes |
|---|---|
| Latest published version (1.x) | Yes |
| Earlier versions | No: install the latest version |

Fixes are delivered as a **new version**, never by changing an already published one (immutable releases). The notes of each version have a "Security" section when it fixes a vulnerability, and VirtualScreen says so in its update notification. Updates are offered by the application ("About") and verified before installation: signed manifest (ECDSA P-256) and SHA-256 fingerprint of the installer.

**Support period**: security fixes are planned for at least 2 years after the most recent release.

## Scope

In scope: the VirtualScreen application, its watchdog, its SplitVdd virtual display driver, its installer and its update mechanism. Vulnerabilities in Windows, graphics drivers or Microsoft Edge WebView2 should be reported to their vendors.

Please do not access other people's data, do not degrade GitHub's service, and give us time to fix the issue before any disclosure.
