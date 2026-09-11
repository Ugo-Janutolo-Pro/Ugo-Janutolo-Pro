# Stagiaire Administrateur Reseaux - Limon IT

Saint-Etienne | Juin 2024

## Contexte

Stage centre sur la mise en place d'un environnement de test et la conduite d'un audit de securite complet, dans une structure Active Directory conforme au modele 3-Tiers Microsoft/ANSSI.

## Missions principales

- Mise en place d'un environnement de test via mRemoteNG (controleur de domaine, serveurs, postes Windows 10/11)
- Isolation reseau via VLAN sur pare-feu Fortinet
- Structuration Active Directory selon le modele 3-Tiers Microsoft/ANSSI
- Audit de securite avec HardeningKitty : plus de 130 parametres analyses, 70 GPO creees pour appliquer les recommandations

## Environnement technique

- mRemoteNG
- Active Directory, modele 3-Tiers Microsoft/ANSSI
- Pare-feu Fortinet, VLAN
- HardeningKitty, recommandations ANSSI / CIS Benchmark

## Detail de l'audit HardeningKitty

L'audit a permis d'identifier les ecarts de configuration par rapport aux recommandations de securite (CIS Benchmark, ANSSI), puis de corriger ces ecarts via la creation de 70 GPO appliquees a l'ensemble du domaine.

Etapes suivies :
1. Analyse de la configuration existante avec HardeningKitty
2. Priorisation des ecarts selon leur criticite
3. Creation des GPO correctives
4. Verification post-application

## Ce que cette experience m'apporte

Une comprehension approfondie du durcissement de systemes Windows en environnement structure, et la capacite a traduire des recommandations de securite theoriques en actions techniques concretes a l'echelle d'un domaine.

---
Les configurations specifiques a l'entreprise (noms de domaine, adresses IP, donnees internes) ont ete anonymisees ou omises pour respecter la confidentialite.
