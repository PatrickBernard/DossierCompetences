# Ingénieur Linux, Adminsys, SRE, DevOps

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
| Gitea | Débutant |
| Minio | Débutant |

--------------------------------------------------------------------------------

## Nevrax - Développeur Zope - 2006/01 à 2007/01

Nevrax était éditeur/développeur du MMORPG Ryzom. En charge de la création des sites, de la gestion des serveurs web communautaires, du gestion et de la formation de l'équipe de développeurs Python/Zope et de la création des outils en lien avec les équipes marketing, QA et lore du jeu Ryzom.

### Ryzom Ring

Le Ryzom Ring était un projet d'extension pour permettre aux game designers, puis aux joueurs, d'éditer de nouvelles zones pour le MMO Saga Of Ryzom. Malgré une alpha concluante, le projet n'a jamais été déployé une fois Nevrax racheté.

* Objectifs
  * Création du site mettant en lien les créations des joueurs sur le Ryzom Ring et les plateformes externes.
  * Gestion d'équipe de joueurs (MJ, invitations, etc.)
  * Débogage du Ryzom Ring
* Stack technique
  * Python, Zope, Plone, ZEO, Squid, Apache, MySQL, Torrent, CVS, Bugzilla, etc.

### Création du site communautaire

Utilisation du nouveau moteur web du Ryzom Ring pour refaire le site communautaire

* Objectifs
  * Création d'un nouveau site communautaire
  * Création d'outils pour le staff interne
  * Migration de données
  * Téléchargement de clients lourds
  * Optimisation de la charge
* Stack technique
  * Python, Zope, Plone, ZEO, Squid, Apache, MySQL, Torrent, CVS, Bugzilla, etc.

### Management de l'équipe de développement web

* Objectifs
  * Formation en Python, HTML, CSS
  * Formation à la gestion de version
  * Distribution des tâches
  * Validation du code
* Stack technique
  * Python, Zope, Plone, MySQL, CVS, Bugzilla, etc.

### Gestion des campagnes publicitaires

* Objectifs
  * Vérifier l'origine de l'accès depuis la publicité
  * Optimiser la distribution du streaming vidéo publicitaire
* Stack technique
  * Zope, Python, Pound, PHP, etc.

### Administration de l'infrastructure Web

Gestion des serveurs web communautaires

* Objectifs
  * Maintien en condition opérationnelle, sécurité
  * Sauvegarde
  * Déploiement
* Stack technique
  * Bash, Apache, Squid, SSH, rsync

### Game Dev

Participation à la conception de nouveaux éléments du jeu Saga of Ryzom

* Objectifs
  * Création de boss pour le jeu Saga of Ryzom
  * Test QA du client du jeu
  * Test de charge
  * Debug
* Stack technique
  * Brainstorming

--------------------------------------------------------------------------------

## Aday, Administrateur système, 2008/10 à 2021/11

Aday est une entreprise d’archivage et de panorama de presse. Au sein de l'équipe exploitation, en charge de la gestion matérielle et logicielle des Datacenters, de la mise en place du CI/CD, de la haute disponibilité, des différents plans de sécurité et du monitoring. Mise en place d'une architecture presque entièrement virtualisée dès 2009. Gestion des bases de données et des clusters de calculs.

### Automatisation de l'installation des serveurs

* Mise en œuvre
  * VLAN dédié à l'installation (DHCP)
  * VLAN de maintenance (iLO, iDRAC, IPMI, etc.)
  * Création d'une image avec les firmwares pour les serveurs
  * Recette d'installation semi-automatique
  * Miroir Debian local

* Stack technique
  * pfSense, Juniper, TFTP, DHCP, preseed, Bash, etc.

### Automatisation des déploiements applicatifs

Infrastructure de déploiement des applications permettant le rollback sans coupures de services

* Objectifs
  * Redondance des nœuds
  * Génération de recettes de déploiement
  * Pilotage via un bastion
  * Possibilité de rollback
  * Stockage des artefacts
* Mise en œuvre
  * Recette de déploiement générique
  * Génération de tâches Jenkins
  * Lancer une tâche Jenkins avec le tag/artefact correspondant
  * Déploiement de l'application sur un nœud fictif identique à la production, test local
  * Pour chaque nœud : Coupure des accès, copie de l'application du master sur le nœud, test local, réinjection
* Stack technique
  * Bash, Jenkins, Ansible, Git, GitLab, HAProxy, Keepalived, Nexus

### Gestion de projets

* Objectifs
  * Gestion de projet
  * Gestion de tickets
  * Versioning
  * Droits/Gestion des utilisateurs
* Stack technique
  * Redmine, Request Tracker, GitLab, Git, Gitolite, SVN, OpenLDAP, etc.

### Gestion DNS

* Objectifs
  * Gestion de zones externes
  * Gestion de zones internes semi-automatisée
* Stack technique
  * BIND (externe), PowerDNS (interne), Bash, Ansible

### Infrastructure du Datacenter

* Objectifs
  * Gestion, achat, maintenance des serveurs physiques
  * Serveurs applicatifs dans des conteneurs
  * Serveurs Windows dans des machines virtuelles
  * Serveurs monolithiques pour les bases de données et l'archivage
  * Migration dev/preprod sur un cloud privé (hyperviseur)
* Stack technique
  * Serveur physique : HPE, Dell, Supermicro, etc.
  * Switch : Juniper
  * Linux (Debian)
  * Conteneurisation : LXC, libvirt, virt-manager, virsh, vservers
  * Virtualisation : KVM, VMware ESXi
  * Proxmox : LXC, KVM

### Infrastructure Veille Audiovisuel (IA/LLM)

* Objectifs

Création et ajout des sous-titres dans le moteur de recherche pour la quasi-totalité des flux audio des chaînes TV et radio françaises.

* Mise en œuvre
  * Flux permanent de fichiers audio
  * Stockage temporaire (7-14 jours)
  * Accès multiples au dépôt de fichiers audio par les nœuds de calcul speech2text
  * Transformation des flux audio vers du texte
  * Ajout dans le moteur de recherche
  * Serveur d'apprentissage IA speech2text
  * Rediffusion des sous-titres
* Stack technique
  * Serveurs FTP redondants (vsftpd)
  * Haute disponibilité des serveurs FTP (Keepalived)
  * Stockage distribué (GlusterFS)
  * Stockage asynchrone (lsyncd, rsync)
  * Machine d'apprentissage IA (CUDA)

### Infrastructures des sauvegardes de documents de presse

* Objectifs
  * Archivage froid (pas/peu d'accès) pour le retraitement éventuel de l'historique des documents
  * Archive tar.gz historiquement au format CD (600-700 Mo)
  * Serveur avec de multiples extensions de RAID pour ajouter des extensions de stockage de disques
  * Dupliquer sur chaque datacenter
* Stack technique
  * Bash, rsync, lsyncd, backupninja, etc.

### Maintien en condition de sécurité

* Objectifs
  * Veille sécurité
  * Mise en place d'une politique d'upgrade régulière
  * Surveillance des logs, repérer les tentatives d'accès anormales
  * Blocage préemptif
  * Certification TLS externe Let's Encrypt
  * Certification TLS interne autosignée
  * SSO (Single Sign-On) pour les API/applications
  * Éducation des utilisateurs
* Stack technique
  * unattended-upgrades, Let's Encrypt, pfSense, fail2ban, Zabbix, Keycloak

### Maintien en condition opérationnelle

* Objectifs
  * Monitoring applicatif
  * Monitoring matériel
  * Redondance applicative
  * Redondance matérielle
  * Inventorier les ressources matérielles disponibles

* Stack technique
  * Bash, Zabbix, Hobbit/Xymon, HAProxy, Keepalived, RAID, ZFS, GLPI, Racktables, FusionInventory, etc.

### Monitoring

* Objectifs
  * Remonter d'informations matérielles et applicatives
  * Prévenir les pannes
  * Retracer les incidents
  * Centralisation de logs
  * Visualisation de logs
* Stack technique
  * Hobbit/Xymon, Smokeping, Bash, Zabbix, etc.
  * ELK (Elasticsearch, Logstash, Kibana)

### Gestion de la téléphonie VoIP

* Objectifs
  * Configuration automatique des téléphones
  * Attribution des numéros pour chaque utilisateur
  * Gestion des groupes

* Stack technique
  * Wazo

### Backup des Windows Server

* Objectifs
  * Réinstaller rapidement les plateformes Windows Server

* Stack technique
  * Clonezilla (2008-2018)
  * VMware (2018-2020)
  * Proxmox (2020)

### Outils de communications

Mise en place d'outils de communications internes, les équipes étant réparties aux quatre coins de la France

* Objectifs
  * Gestion des mails internes / externes
  * Outils divers pour les présentations, le partage de fichiers, etc.

* Stack technique
  * ejabberd, Rocket.Chat
  * Mail (imapsync, Dovecot, SpamAssassin, ClamAV, Roundcube)
  * EtherCalc, Etherpad, Haste, Plik

### Outils divers

* Stack technique
  * Serveur web : Nginx, Apache, Lighttpd, Gunicorn, etc.
  * Stockage d'objets : Memcached, Redis, Minio, CouchDB
  * Message broker/queuing : Kafka, RabbitMQ
  * Téléphonie : Wazo
  * SQL : Opérations de routine sur PostgreSQL (+tail_n_mail), MySQL/MariaDB, SQLite et Oracle 8

### Etude de stockage distribués

Pour le projet de Veille audiovisuel plusieurs technologie de stockages ont été évalué.

* Objectifs
  * Permettre un flux de réception continue même en cas de panne d'un datacenter.
  * Permettre à de multiples clients d'acceder au stockage.

* Technologie évaluer
  * GlusterFS
  * Ceph
  * Minio (S3)
  * Bench
  * Cassage de l'infra, et observer le temps de reconstruction

* Résultat
Les solutions testés sont toute robustes avec des performances similaire pour notre usage.
Ceph est la plus onéreuse car requiert un réseaux distinct pour des performances optimal.
Nous avons choisi GlusterFS pour des raisons de simplicité des retours arrières.
GlusterFS s'ajoutant à un système de fichiers déjà existant, il suffit de le désactiver en cas de problème.

### Etude de passage en cloud publique

Pour le projet de veille audiovisuel il a été envisagé d'exporté les serveurs de calculs sur un cloud publique

* Objectifs
  * Benchmarker le cloud publique
  * Comparaison des couts versus nos solution traditionnel bare-metal

* Stack technique
  * déploiement des applications speech2text sur la plateforme cloud d'essai
  * Bench
  * Feuille de calculs pour exprimé les résultats

* Résultats

Sur un an, le cloud revient au même prix que l'achat physique des serveurs.
Or les serveurs physiques dure bien plus qu'un ans.

--------------------------------------------------------------------------------

## SJT - Formateur - 2023/10 à 2023/11

Solidarités et Jalons pour le Travail est une association d'accompagnement à la réinsertion de jeunes et d'adultes.

### Formateur PIX

* Objectifs
  * Réduire la fracture numérique.
  * Aider au retour à l'emploi.

* Mise en œuvre
  * Capacité à simplifier des concepts techniques.
  * Adaptabilité pour répondre aux besoins des apprenants.
  * Création d'ateliers didactiques
  * Démonstration technique

* Stack technique
  * Rédaction de documentation
  * Connaissance globale en informatique
  * Démonstration d'une attaque par force brute avec l'outil de John the Ripper, OpenSSL
  * ChatGPT

--------------------------------------------------------------------------------

### OC3 - Ingénieur Linux - 2024/03 à 2024/05

OC3 est un hébergeur, proposant d’héberger des infrastructures complètes de ses clients, l'infrastructure étant répartie sur 3 datacenters.

### Ingénieur Linux

* Objectifs
  * MCO
  * MCS
  * Support

* Mise en œuvre
  * Répondre aux tickets
  * Résoudre les pannes

* Stack technique
  * VMware vSphere
  * Proxmox
  * Zimbra
  * Bash, Postfix, etc.
