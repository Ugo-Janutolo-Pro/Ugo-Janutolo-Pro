# Audit de sécurité — HardeningKitty

## Contexte
Audit de sécurité réalisé lors de mon stage chez Limon IT (Saint-Étienne, juin 2024), sur un environnement de test structuré selon le modèle 3-Tiers Microsoft/ANSSI.

## Objectif
Évaluer et renforcer la configuration de sécurité des postes Windows à l'aide de l'outil **HardeningKitty**, en s'appuyant sur les recommandations du CIS Benchmark et de l'ANSSI.

## Environnement technique
- Contrôleur de domaine + serveurs + postes Windows 10/11
- Environnement de test via mRemoteNG
- VLAN isolé sur pare-feu Fortinet
- Structuration Active Directory selon le modèle 3-Tiers Microsoft/ANSSI

## Résultats
- **130+ paramètres de sécurité** analysés et corrigés
- **70 GPO** créées pour appliquer les recommandations à l'échelle du domaine
- Amélioration mesurable du score de conformité HardeningKitty avant/après

## Ce que j'ai appris
- Utilisation concrète d'un outil d'audit de sécurité en environnement Windows
- Traduction de recommandations théoriques (CIS/ANSSI) en GPO appliquées
- Rigueur dans la documentation et le suivi des correctifs appliqués

## Ressources
- [HardeningKitty (GitHub officiel)](https://github.com/scipag/HardeningKitty)
- [Recommandations ANSSI](https://cyber.gouv.fr/)

---
*Les configurations spécifiques à l'entreprise (noms de domaine, IP, données internes) ont été anonymisées ou omises pour respecter la confidentialité.*
