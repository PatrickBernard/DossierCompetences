# Ingénieur Linux, AdminSys, SRE, DevOps

## Patrick Bernard - 18/11/1980

### Savoir-faire

| Compétences | Niveaux (Débutant-Confirmé-Expert [10 ans min]) |
| ------ | ------ |
| Administration système Linux | Expert |
| Hyperconvergence, Conteneurs | Expert |
| Maintien en condition opérationnelle | Expert |
| Maintien en condition de sécurité | Expert |
| Achat/gestion de Matériel | Expert |
| Bases de données SQL | Confirmé |
| Configuration (IAC) | Confirmé |
| Gestion de projet | Débutant |

### Savoir-être

* Vigilance, curiosité, intégrité, polyvalence

### OUTILS

| Nom | Niveaux (Débutant-Confirmé-Expert [10 ans min]) |
| ------ | ------ |
| Linux (Debian) | Expert |
| LXC | Expert |
| Bash | Confirmé |
| Proxmox | Confirmé |
| Ansible | Confirmé |
| Zabbix | Confirmé |
| pfSense | Confirmé |
| Git | Confirmé |
| GlusterFS | Confirmé |
| Serveur web | Confirmé |
| HAProxy | Confirmé |
| Keepalived | Confirmé |
| GitLab | Confirmé |
| Docker | Débutant |
| Minio | Débutant |

--------------------------------------------------------------------------------

## Indépendant - Gamedev, Freelance - depuis 2022

### Bluesky

* Création d'un projet de détection de bot pour lutter contre l'opération doppelgänger.
* Dans le cadre de récolte de preuve contre un harcèlement en ligne : Script pour sauvegarder le contenu d'un compte.

### Homelabs

* Gestion de mon infra perso me servant pour l'apprentissage.
* Un proxmox de 3 cluster / nas / switch L3 manageable / ...
* Test de services varié.

### Gamedev

* Participation à des gamejams
* Participation à des opérations caritatives
* Principalement Unity et Godot ( C# )

--------------------------------------------------------------------------------

## OC3 - Ingénieur Linux - 2024/03 à 2024/05

OC3 est un hébergeur, proposant d’héberger des infrastructures complètes de ses clients, l'infrastructure étant répartie sur 3 datacenters.

### Ingénieur Linux

* Objectifs : MCO, MCS, Support
* Mise en œuvre : Répondre aux tickets, Résoudre les pannes
* Stack technique : VMware vSphere, Proxmox, Zimbra, Bash, Postfix, etc.

--------------------------------------------------------------------------------

## SJT - Formateur - 2023/10 à 2023/11

Solidarités et Jalons pour le Travail est une association d'accompagnement à la réinsertion de jeunes et d'adultes.

### Formateur PIX

* Objectifs : Réduire la fracture numérique, Aider au retour à l'emploi.
* Mise en œuvre : Capacité à simplifier des concepts techniques; Adaptabilité pour répondre aux besoins des apprenants; Création d'ateliers didactiques; Démonstration technique
* Stack technique : Rédaction de documentation; Connaissance globale en informatique; Démonstration d'une attaque par force brute avec l'outil de John the Ripper, OpenSSL; ChatGPT
* Résultat : 90% de candidats certifiés au cours de ma formation.

--------------------------------------------------------------------------------

## Aday - Administrateur système - 2008/10 à 2021/11

Aday est une entreprise de services spécialisée dans la veille médiatique et la mise en valeur des données.

Au sein de l'équipe exploitation, en charge de la gestion matérielle et logicielle des Datacenters (100 serveurs physiques, 300 VM et conteneurs), de la mise en place du CI/CD, de la haute disponibilité, des différents plans de sécurité et du monitoring. Mise en place d'une architecture presque entièrement virtualisée dès 2008. Gestion des bases de données et des clusters de calculs.

### Automatisation de l'installation des serveurs

* Objectifs : Installation semi-automatisée des serveurs à distance selon le type d'usage.
* Mise en œuvre : VLAN dédié à l'installation (DHCP), VLAN de maintenance (iLO, iDRAC, IPMI, etc.), Création d'une image avec les firmwares pour les serveurs, Recettes d'installations semi-automatique, Miroir Debian local
* Stack technique : pfSense, Juniper, TFTP, DHCP, preseed, Bash, nexus.

### Automatisation des déploiements applicatifs

* Objectifs : Infrastructure de déploiement des applications permettant le rollback sans coupures de services depuis un bastion.
* Mise en œuvre : Standardisation des applications, Pilotage des recettes via Jenkins, Déploiement des artefact applicatifs sur un nœud fictif identique à la production, Validation, Déploiement en (pre)production.
* Stack technique : Bash, Jenkins, Ansible, Git, GitLab, HAProxy, Keepalived, Nexus

### Gestion de projets

* Objectifs : Déploiement et maintenance des outils de gestions de projets
* Stack technique : Redmine, Request Tracker, GitLab, Git, Gitolite, SVN, OpenLDAP, etc.

### Gestion DNS

* Objectifs : Maintenance et mise en place de zone DNS interne et externe
* Stack technique : BIND (externe), PowerDNS (interne), Bash, Ansible

### Gestion Bases de données

* Objectifs : Administrer les différentes bases de données
* Mise en œuvre : Installer et maintenir les différentes bases de données, réplication selon les besoin, gestion des droits, ...
* Stack technique : PostgreSQL (+tail_n_mail), MySQL/MariaDB, SQLite et Oracle 8

### Backup des Windows Server

* Objectifs : Réinstaller rapidement les plateformes Windows Server
* Stack technique : Clonezilla

### Virtualisation des plateformes d'un partenaire

* Objectifs : Migration des serveurs zope/plone d'un partenaire vers une solution de virtualisation
* Stack Technique : virtualbox, netcat, rsync

### Migration Serveur windows vers VMWare ESXi

* Objectifs : Migration des Serveurs Windows dans des machines virtuelles
* Stack Technique : VMware ESXi, VMware converter

### Infrastructure du Datacenter

* Objectifs : Gestion, achat, maintenance des serveurs physiques, virtuel, et des conteneurs
* Mise en œuvre : Serveurs applicatifs dans des conteneurs, Serveurs monolithiques pour les bases de données et l'archivage
* Stack technique : HPE, Dell, Supermicro, Juniper, Linux (Debian), LXC, libvirt, virt-manager, virsh, vservers, KVM, VMware ESXi, Proxmox

### Infrastructure Veille Audiovisuel

* Objectifs : Création et ajout des sous-titres dans le moteur de recherche pour la quasi-totalité des flux audio des chaînes TV et radio françaises.
* Mise en œuvre : Flux permanent de fichiers audio, Accès multiples au dépôt de fichiers audio par les nœuds de calcul
* Stack technique : vsftpd, Keepalived, GlusterFS, lsyncd, rsync

### Cluster de calcul Speech2text LLM/IA en partenariat avec l’université d’Aix

* Objectifs : Installation de l'IA de recherche d'apprentissage et de calcul
* Mise en œuvre : un serveur d'apprentissage à base de 3090, multiple serveur de calcules
* Stack technique : CUDA, lsyncd, supervisord, glusterfs

### Infrastructures des sauvegardes des documents de presse

* Objectifs : Archivage froid (pas/peu d'accès) pour le retraitement éventuel de l'historique des documents
* Mise en œuvre : Archive tar.gz historiquement au format CD (600-700 Mo), Serveur avec de multiples extensions de RAID pour ajouter des extensions de stockage de disques, Dupliquer sur chaque datacenter
* Stack technique : Bash, rsync, lsyncd, backupninja, etc.

### Maintien en condition de sécurité

* Objectifs : Veille sécurité
* Mise en œuvre : Mise en place d'une politique d'upgrade régulière, Surveillance des logs, Blocage préemptif, HTTPS interne/externe, SSO, Éducation des utilisateurs
* Stack technique : unattended-upgrades, Let's Encrypt, pfSense, fail2ban, Zabbix, Keycloak, OpenSSL

### Maintien en condition opérationnelle

* Mise en œuvre : Monitoring, redondance matériel et applicatives, Inventorier les ressources matérielles disponibles
* Stack technique : Bash, Zabbix, Hobbit/Xymon, HAProxy, Keepalived, RAID, ZFS, GLPI, Racktables, FusionInventory, etc.

### Monitoring

* Objectifs : Remonter d'informations matérielles et applicatives
* Mise en œuvre : Centralisation, Visualisation de logs
* Stack technique : Hobbit/Xymon, Smokeping, Zabbix, ELK (Elasticsearch, Logstash, Kibana), filebeat

### Gestion de la téléphonie VoIP

* Objectifs : Remplacement de la solution externe par notre propre infra VoIP
* Mise en œuvre : Installation de Wazo, Configuration automatique des téléphones, Attribution des numéros pour chaque utilisateur, Gestion des groupes
* Stack technique : Wazo, Asterisk

### Migration dev/preprod sur un cloud privé

* Objectifs : Uniformisation de l'infra, Passage à proxmox des serveurs de dev/preprod, migration des VM KVM et ESXi.
* Mise en œuvre : scripts de migrations
* Stack technique : Proxmox, Bash

### Migration Serveur windows vers proxmox

* Objectifs : Migration des Serveurs Windows VMWare ESXi vers proxmox
* Stack Technique : VMware ESXi, proxmox

### Gestion Mail client

* Objectifs : Fluidifier l'envoie de mail vers les clients.
* Mise en œuvre : Supervision des éléments bloquants.
* Stack technique : Zabbix, dns, dmarc, spf, postfix

### Gestion Mail Interne

* Objectifs : Gestion des mails internes des collaborateurs, lancement de scripts, spam
* Stack technique : postfix, dovecot, ldap, procmail, sieve, fetchmail, maildrop, clamav, roundcube, imapsync

### Gestion FTP réception Presse

* Objectifs : Recevoir les flux presse papier en continue
* Mise en œuvre : Multiple serveurs FTP, script de gestion des fournitures selon chaque type de réceptions
* Stack technique : keepalived, vsftpd, scripting

### Outils de communications

* Objectifs : Mise en place d'outils de communications internes, les équipes étant réparties aux quatres coins de la France.
* Stack technique : ejabberd, Rocket.Chat, EtherCalc, Etherpad, Haste, Plik, OpenVPN

### Déploiement d'outils divers

* Objectifs : Gestion et déploiements d'outils utilisé par nos applications
* Stack technique :
  * Serveur web : Nginx, Apache, Lighttpd, Gunicorn
  * Stockage d'objets : Memcached, Redis, Minio, CouchDB
  * Message broker/queuing : Kafka, RabbitMQ

### Etude de stockage distribués

* Objectifs : Permettre un flux de réception continu même en cas de panne d'un datacenter, Permettre à de multiples clients d'accéder au stockage.
* Technologie évaluer : GlusterFS, Ceph, Minio (S3)
* Résultat : Les solutions testées sont toutes robustes avec des performances similaires pour notre usage. Nous avons choisi GlusterFS pour des raisons de simplicité des retours arrière. GlusterFS s'ajoutant à un système de fichiers déjà existant, il suffit de le désactiver en cas de problème.

### Etude de passage en cloud public

* Objectifs : Pour le projet de veille audiovisuel il a été envisagé d'exporter les serveurs de calculs sur un cloud public.
* Mise en œuvre : Benchmarker le cloud publique, Comparaison des coûts versus nos solutions traditionnelles bare-metal.
* Résultats : Sur un an, le cloud revient au même prix que l'achat physique des serveurs, or les serveurs physiques dure bien plus d'un an.

###

* Objectifs :
* Mise en œuvre :
* Stack technique :

--------------------------------------------------------------------------------

## Nevrax - Développeur Zope - 2006/01 à 2007/01

Nevrax était éditeur/développeur du MMORPG Ryzom. En charge de la création des sites, de la gestion des serveurs web communautaires, du gestion et de la formation de l'équipe de développeurs Python/Zope et de la création des outils en lien avec les équipes marketing, QA et lore du jeu Ryzom.

### Ryzom Ring

Le Ryzom Ring était un projet d'extension pour permettre aux game designers, puis aux joueurs, d'éditer de nouvelles zones pour le MMO Saga Of Ryzom. Malgré une alpha concluante, le projet n'a jamais été déployé une fois Nevrax racheté.

* Objectifs :
  * Création du site mettant en lien les créations des joueurs sur le Ryzom Ring et les plateformes externes.
  * Gestion d'équipe de joueurs (MJ, invitations, etc.)
  * Débogage du Ryzom Ring
* Stack technique : Python, Zope, Plone, ZEO, Squid, Apache, MySQL, Torrent, CVS, Bugzilla, etc.

### Création du site communautaire

* Objectifs : Utilisation du nouveau moteur web du Ryzom Ring pour refaire le site communautaire
* Mise en œuvre :
  * Création d'un nouveau site communautaire
  * Création d'outils pour le staff interne
  * Migration de données
  * Téléchargement de clients lourds
  * Optimisation de la charge
* Stack technique : Python, Zope, Plone, ZEO, Squid, Apache, MySQL, Torrent, CVS, Bugzilla, etc.

### Management de l'équipe de développement web

* Objectifs :
  * Formation en Python, HTML, CSS
  * Formation à la gestion de version
  * Distribution des tâches
  * Relecture du code
* Stack technique : Python, Zope, Plone, MySQL, CVS, Bugzilla, etc.

### Gestion des campagnes publicitaires

* Objectifs :
  * Vérifier l'origine de l'accès depuis la publicité
  * Optimiser la distribution du streaming vidéo publicitaire
* Stack technique : Zope, Python, Pound, PHP, etc.

### Administration de l'infrastructure Web

* Objectifs : Gestion des serveurs web communautaires
* Mise en œuvre : MCO, MCS, backup, déploiement
* Stack technique : Bash, Apache, Squid, SSH, rsync

### Game Dev

* Objectifs : Participation à la conception de nouveaux éléments du jeu Saga of Ryzom
* Mise en œuvre : Création de boss pour le jeu Saga of Ryzom, Test QA du client du jeu, Test de charge, Debug
* Stack technique : Brainstorming
