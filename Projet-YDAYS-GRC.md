# Projet GRC - Audit de cybersecurite

## Contexte

Projet mene en collaboration avec une entreprise partenaire dans le cadre de mon Bachelor Cybersecurite a Ynov Campus Lyon, en lien avec l'association GRC Lyon. L'entreprise partenaire est une structure publique locale gerant des services essentiels (eau et assainissement) depuis plusieurs decennies.

Le nom de l'entreprise et l'ensemble des donnees techniques specifiques (adresses, domaines, versions de logiciels, vulnerabilites precises) ne sont pas divulgues dans ce document, conformement aux engagements de confidentialite pris avec le partenaire.

## Objectif

Realiser un audit de cybersecurite complet couvrant l'ensemble du perimetre organisationnel et technique d'une structure, afin d'evaluer sa maturite en matiere de securite et de proposer un plan de remediation priorise.

## Perimetre de l'audit

L'audit a couvert 7 grands domaines :

1. Securite physique
2. Reseau et pare-feu
3. Active Directory (durcissement, gouvernance des identites)
4. Sensibilisation des utilisateurs
5. Gouvernance et processus (PCA/PRA)
6. Gouvernance globale de la securite du systeme d'information
7. OSINT (reconnaissance passive sur la surface d'exposition publique)

## Methodologie

- **Securite physique** : grille d'evaluation structuree, entretiens avec les services concernes (DSI, RH, QSE), ronde d'observation sur site
- **Reseau et pare-feu** : revue des regles de configuration, analyse des acces et de la journalisation
- **Active Directory** : audit technique avec l'outil PingCastle, evaluation selon plusieurs categories (gouvernance, gestion des identites, securite et surveillance, configuration technique, continuite)
- **Utilisateurs** : entretiens et evaluation du niveau de sensibilisation face aux risques cyber (phishing, remontee d'incidents, bonnes pratiques)
- **Gouvernance** : evaluation de la structuration globale de la SSI (gouvernance, postes de travail et nomadisme, resilience, securite reseau)
- **OSINT** : reconnaissance passive pour identifier les elements exposes publiquement (presence en ligne, empreinte numerique, composants techniques visibles depuis l'exterieur)

## Resultats generaux (anonymises)

L'audit de l'Active Directory a par exemple mis en evidence un score de risque eleve, avec des ecarts variables selon les categories analysees : une gestion des identites relativement correcte, mais des lacunes plus marquees sur la securite et la surveillance, ainsi que sur la configuration technique du domaine.

De maniere generale, l'audit a permis d'identifier :

**Points positifs constates**
- Des fondations de securite deja en place (segmentation reseau, gestion des droits d'administration, protection de la flotte mobile, sauvegardes structurees)
- Une reelle receptivite des utilisateurs aux enjeux de securite, sous reserve d'accompagnement
- Des premieres briques de gouvernance deja engagees (referent securite identifie, outils de gestion centralisee)

**Axes d'amelioration identifies**
- Renforcement de la securisation des comptes a privileges et isolation des niveaux d'administration critiques (modele de tiering)
- Formalisation des plans de continuite et de reprise d'activite (PCA/PRA)
- Mise en place d'un plan de sensibilisation structure et recurrent pour les utilisateurs
- Renforcement du controle d'acces reseau et de la traçabilite (journalisation, gestion des correctifs)
- Reduction de la surface d'exposition publique identifiee via l'OSINT

## Ce que j'ai appris

- Conduite d'un audit de cybersecurite dans sa globalite, du volet organisationnel (gouvernance, entretiens) au volet technique (AD, reseau, OSINT)
- Utilisation d'outils d'audit specialises (PingCastle) pour objectiver un niveau de risque
- Structuration de recommandations priorisees et adaptees a la maturite reelle d'une organisation
- Capacite a traduire des constats techniques en enjeux comprehensibles pour des decideurs non-techniques
- Travail en collaboration avec des professionnels du secteur, dans un contexte reel avec des enjeux de confidentialite

## Ressources

- Plus d'informations sur le projet : [LinkedIn - Association GRC Lyon](https://www.linkedin.com/company/association-grc-lyon/posts/)

---
Les elements confidentiels et identifiants (nom de l'entreprise, domaines, versions de composants, vulnerabilites precises) ne sont volontairement pas partages dans ce document, conformement aux engagements de confidentialite pris avec le partenaire.
