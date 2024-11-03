# Ingénieur Linux, devops depuis 2008

## Patrick Bernard - 18/11/1980

### Savoir faire

|Compétences|Niveaux (Débutant-Confirmé-Expert [10 ans min])|
|---|---:|
|Administration système Linux|Expert|
|Hyperconvergence, Conteneurs|Expert|
|Maintien en condition opérationnel|Expert|
|Maintien en condition de sécurité|Expert|
|Achat/gestion Matériel|Expert|
|Bases de données SQL|Confirmé|
|Configuration (IAC)|Confirmé|
|Gestion de projet|Débutant|

## Savoir être

* Vigilance, curiosité, intégrité, polyvalence

## OUTILS

|Nom | Niveaux (Débutant-Confirmé-Expert [10 ans min])|
|---|---:|
|Linux (Debian)|Expert|
|LXC|Expert|
|Bash|Confirmé|
|Proxmox|Confirmé|
|Ansible|Confirmé|
|Zabbix|Confirmé|
|pfsense|Confirmé|
|Git|Confirmé|
|GlusterFS|Confirmé|
|web server|Confirmé|
|haproxy|Confirmé|
|keepalived|Confirmé|
|gitlab|Confirmé|
|docker|Débutant|
|gitea|Débutant|
|minio|Débutant|

***

## Nevrax - Développeur Zope - 2006/01 à 2007/01

Nevrax était éditeur/développeur du MMORPG Ryzom
En charge de la création des sites, gestion des serveurs web communautaire, management et formation de l'équipe de développeurs Python/Zope et de la création des outils en lien avec les équipes marketing, QA et lore du jeu Ryzom

### Ryzom Ring

Le Ryzom Ring était un projet d'extension pour permettre aux game designer, puis aux joueurs d'éditer de nouvelles zones pour le MMO Saga Of Ryzom. Malgré une alpha concluante, le projet n'a jamais été déployé une fois Nevrax racheté.

* Objectifs
  * Création du site mettant en lien les créations des joueurs sur le ryzom ring et l'extérieur
  * Gestion d'équipe de joueurs (MJ, invitations ... )
  * Débogage du Ryzom Ring

* Stack technique
  * Python, zope, plone, zeo, squid, apache, mysql, torrent, cvs, bugzilla, …

### Création site communautaire

Utiliser le nouveau moteur web du ryzom ring pour refaire le site communautaire

* Objectifs
  * Création d'un nouveau site communautaire
  * Création d'outils pour le staff interne
  * Migration de données
  * Téléchargement de client lourd
  * Optimisation de charge

* Stack technique
  * Python, zope, plone, zeo, squid, apache, mysql, torrent, cvs, bugzilla, …

### Management de l'équipe de développement web

* Objectifs
  * Formation python, html, css
  * Formation à la gestion de contrôle
  * Distribution des tâches
  * Validation du code
* Stack technique
  * Python, zope, plone, mysql, cvs, bugzilla, …

### Gestion des campagnes publicitaires

* Objectifs
  * Vérifier l'origine de l'accès depuis la publicité
  * Optimiser la distribution du streaming vidéo publicitaire
* Stack technique
  * zope, python, pound, php, …

### Administration Infrastructure Web

Gestion des serveurs web communautaire

* Objectifs
  * Maintien en condition opérationnel, sécurité
  * Sauvegarde
  * Déploiement
* Stack technique
  * bash, apache, squid, ssh, rsync

### Game Dev

Participation à la conception de nouveau élément du jeu Saga of ryzom

* Objectifs
  * Création de boss pour le jeu Saga of Ryzom
  * test QA du client du jeu
  * test de charge
  * debug
* Stack technique
  * Brainstorming

***

## Aday, Administrateur système, 2008/10 à 2021/11

Aday est une entreprise d’archivage et panorama de presse
Au sein de l'équipe exploitation, en charge de la gestion matériel et logiciel des Datacenters, de la mise en place du CI/CD, de la haute disponibilité, des différents plan de sécurité et du monitoring
Mise en place d'une architecture presque entièrement virtualisé dès 2009
Gestion des bases de données, et des clusters de calculs

### Automatisation de l'installation des serveurs

* Mise en oeuvre
  * vlan dédié à l'installation (dhcp)
  * vlan de maintenance (ilo, idrac, ipmi, ...)
  * Création d'une image avec les firmwares pour les serveurs
  * Recette d'installation semi-automatique
  * Miroir debian local
* Stack technique
  * pfsense, juniper, tftp, dhcp, preseed, bash, ...

### Automatisation des déploiements applicatif

Infrastructure de déploiement des applications permettant le rollback sans coupures de services

* Objectifs
  * Redondance des nodes
  * Génération de recettes de déploiement
  * Pilotage via un bastion
  * Possibilité de Rollback
  * Stockage des artefacts
* Mise en oeuvre
  * Recette de déploiement générique
  * Génération de job Jenkins
  * Lancer un job Jenkins avec le tag/artefact correspondant
  * Déploiement app sur un noeud fictif identique à la prod, test local
  * Pour chaque noeud : Coupure des accès, copie app du master sur le noeud, test local, réinjection
* Stack technique
  * bash, jenkins, ansible, git, gitlab, haproxy, keepalived, nexus

### Gestion de Projets

* Objectifs
  * Gestion de projet
  * Gestion de tickets
  * Versioning
  * Droits/Gestion Utilisateur
* Stack technique
  * redmine, request tracker, gitlab, git, gitolite, svn, openldap, …

### Gestion DNS

* Objectifs
  * Gestion de zones externe
  * Gestion de zones interne semi-automatisée
* Stack technique
  * bind (externe), powerdns (interne), bash, ansible

### Infrastructure Datacenter

* Objectifs
  * Gestion, achat, maintenance des serveurs physique
  * Serveurs applicatif dans des conteneurs
  * Serveurs windows dans des machines virtuel
  * Serveurs monolithique pour les bases de données, et l'archivage
  * Migration dev/preprod sur un cloud privé (hyperviseur)
* Stack technique
  * Serveur physique : hpe, dell, supermicro, ...
  * Switch : Juniper
  * linux (debian)
  * conteneurisation : LXC, libvirt, virt-manager, virsh, vservers
  * virtualisation : KVM, vmware ESXi
  * Proxmox : LXC, KVM

### Infrastructure Veille Audiovisuel

* Objectifs

Création et ajout des sous titres dans le moteur de recherche pour la quasi totalité des flux audio des chaînes TV et Radio FR

* Mise en Oeuvre
  * Flux permanent de fichiers audio
  * Stockage temporaire (7-14j)
  * Accès multiples au dépôt de fichiers audio par les noeuds de calcul speech2text
  * Transformation flux audio vers textes
  * Ajout dans le moteur de recherche
  * Serveur d'apprentissage IA speech2text
  * Rediffusion des sous-titres
* Stack technique
  * Serveurs ftp redonder (vsftpd)
  * Haute disponibilité des serveurs ftp (keepalived)
  * Stockage distribué (GlusterFS)
  * Stockage asynchrone (lsyncd,rsync)
  * Machine d'apprentissage IA (cuda)

### Infrastructures Sauvegardes

* Objectifs
  * Archivage froid (pas/peu d'accès) pour le retraitement éventuel de l'historique des documents
  * Archive tar.gz historiquement format cd (600-700mo)
  * Serveur avec de multiple extension de raid pour ajouter des extensions de stockage de disques
  * Dupliquer sur chaque datacenter
* Stack technique
  * bash, rsync, lsyncd, backupninja, …

### Maintien en condition de sécurité

* Objectifs
  * Veille sécurité
  * Mise en place d'une politique d'upgrade régulier
  * Surveillance des logs, repérer les tentatives d'accès anormaux
  * Blocage préemptif
  * Certification tls externe let's encrypt
  * Certification tls interne autosigné
  * SSO (single sign on) pour les apis/applications
  * Education des utilisateurs
* Stack technique
  * unattended-upgrades, let's encrypt, pfsense, fail2ban, zabbix, keycloak

### Maintien en condition opérationnel

* Objectifs
  * Monitoring applicatif
  * Monitoring hardware
  * Redondance applicatif
  * Redondance matériel
  * Inventorier les ressources matériel disponible
* Stack technique
  * Bash, Zabbix, hobbit/xymon, haproxy, keepalived, Raid, ZFS, glpi, racktable, fusion inventory, …

### Monitoring

* Objectifs
  * Remonter d'information hardware et applicatif
  * Prévenir les pannes
  * Retracer après incidents
  * Centralisation de log
  * Visualisation de log
* Stack technique
  * hobbit/xymon, smokeping, bash, zabbix, …
  * elk (elasticsearch, logstash, kibana)

### Gestion Téléphonie VoIP

* Objectifs
  * Configuration automatique des téléphones
  * Attribution des numéros pour chaque utilisateurs
  * Gestion des groupes
* Stack Technique
  * Wazo

### Outils Communications

Mise en place d'outils de communications interne, les équipes étant dispatcher aux 4 coins de la France

* Objectifs
  * Gestions mails interne / externe
  * Outils divers pour les présentations, partage de fichiers, ...
* Stack technique
  * ejabberd, rocket.chat
  * mail (imapsync, dovecot, spamassassin, clamav, roundcube )
  * ethercalc, etherpad, haste, plik

### Outils Divers

* Stack technique
  * Serveur web : nginx, apache, lighttpd, gunicorn, ...
  * Stockage objets : memcached, redis, minio, couchdb
  * Message broker/queuing : kafka, rabbitmq
  * Téléphonie : wazo
  * SQL : Opération de routine sur PostgreSQL (+tail_n_mail), Mysql/MariaDB, SQLite et Oracle 8

***

## SJT - Formateur - 2023/10 à 2023/11

Solidarités et Jalons pour le Travail est une association d'accompagnement à la réinsertion de jeunes et d’adulte

### Formateur PIX

* Objectifs
  * Réduire la fracture numérique.
  * Aider le retour à l'emploi.
* Mise en oeuvre
  * Capacité à simplifier des concepts techniques.
  * Adaptabilité pour répondre aux besoins des apprenants.
  * Création d'atelier didactique
  * Démonstration technique
* Stack technique
  * Rédaction de documentation
  * Connaissance globale en informatique
  * Démonstration de bruteforce John the ripper, openSSL
  * ChatGPT

***

## OC3 - Ingénieur Linux - 2024/03 à 2024/05

OC3 est un hébergeur, proposant d’héberger des infrastructures complète de leurs clients infrastructure répartie sur 3 datacenters

### Ingénieur Linux

* Objectifs
  * MCO
  * MCS
  * Support
* Mise en oeuvre
  * Répondre au ticket
  * Résoudre les pannes
* Stack technique
  * VMWare vSphere
  * Proxmox
  * Zimbra
  * Bash, postfix, ...
