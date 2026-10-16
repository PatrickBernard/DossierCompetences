# Patrick Bernard — Ingénieur Linux, Infrastructure & Reliability

**Infrastructure · SRE · DevOps · Linux · Automatisation · Virtualisation**

[GitHub](https://github.com/PatrickBernard) · [LinkedIn](https://www.linkedin.com/in/pb42/) · [Itch.io](https://patrx.itch.io/) · [Contact](mailto:bernardpatrickgerard@yahoo.fr)

## Profil

Ingénieur Linux et infrastructure avec **13 ans d’expérience** dans l’exploitation d’infrastructures complexes, la virtualisation, l’automatisation et la fiabilité des services. Expérience de la gestion de parcs de serveurs physiques et de machines virtuelles, de la mise en place de chaînes CI/CD, de la haute disponibilité, de la sécurité opérationnelle, du stockage distribué et de plateformes de calcul pour des projets IA/LLM.

Attaché aux technologies open source, à l’expérimentation et à la veille continue. En parallèle de mon activité infrastructure, je développe des projets de jeux vidéo et m’intéresse à la préservation vidéoludique ainsi qu’à la lutte contre la désinformation.

## Compétences clés

- **Systèmes Linux :** administration, exploitation, maintenance et automatisation.
- **Production & fiabilité :** MCO/MCS, supervision, diagnostic d’incidents, redondance et haute disponibilité.
- **Infrastructure as Code & automatisation :** Ansible, Bash, scripts d’installation et de migration.
- **CI/CD & déploiement :** industrialisation, validation, déploiements progressifs et stratégies de retour arrière.
- **Virtualisation & conteneurs :** Proxmox, VMware, KVM, LXC et Docker.
- **Stockage & données :** PostgreSQL, MySQL/MariaDB, Redis, GlusterFS, MinIO et étude de solutions distribuées.
- **Réseaux & services :** DNS, DHCP, VPN, reverse proxy, équilibrage de charge, messagerie et VoIP.
- **Sécurité opérationnelle :** mises à jour, surveillance des journaux, filtrage, HTTPS et gestion des identités.
- **Transmission :** conception d’ateliers, démonstrations techniques et vulgarisation de sujets complexes.

## Expériences professionnelles

### Administrateur système et cloud — Ediser
**Juin 2025 – Décembre 2025 · Montpellier**

- Exploitation et maintien en conditions opérationnelles et de sécurité d'une infrastructure virtualisée sous Linux.
- Déploiement, configuration et supervision d'une solution d'authentification centralisée Keycloak, destinée aux moniteurs et apprenants des auto-écoles, avec une architecture redondée sous Docker.
- Mise en place de la supervision de l'infrastructure avec Zabbix et de la protection des systèmes avec CrowdSec.
- Automatisation des déploiements avec Ansible : expérimentation et tentative d'intégration aux pratiques des équipes de développement.

### Ingénieur Linux — OC3 Network
**Mars 2024 – Mai 2024 · Montpellier**

- Maintien en condition opérationnelle et de sécurité de l’infrastructure sous **VMware vSphere**.
- Exploitation et dépannage d'environnements Linux et des services associés clients.
- Intervention sur la supervision Zabbix et les services de messagerie **Zimbra**.
- Étude d'une évolution de la plateforme de virtualisation VMware vSphere vers Proxmox, dans un contexte de maîtrise des coûts d'infrastructure.


### Formateur — SJT Formation
**Septembre 2023 – Octobre 2023 · Compiègne**

- Conception d’ateliers pédagogiques et de démonstrations techniques.
- Simplification de concepts techniques complexes.
- Adaptation des contenus aux profils et besoins des apprenants.

### Administrateur systèmes et réseaux — Aday
**Octobre 2008 – Novembre 2021 · Paris**

Au sein de l’équipe exploitation d’une entreprise spécialisée dans la veille médiatique et la valorisation des données, gestion d’infrastructures réparties sur plusieurs datacenters : **plus de 100 serveurs physiques et 300 machines virtuelles**.

#### Exploitation, infrastructure et virtualisation

- Administration et maintenance des serveurs physiques, machines virtuelles et conteneurs.
- Mise en place progressive d’une infrastructure largement virtualisée dès 2008.
- Gestion de serveurs applicatifs conteneurisés et de serveurs dédiés aux bases de données et à l’archivage.
- Migration de plateformes VMware ESXi/KVM vers Proxmox et migration de serveurs Windows virtualisés.
- Gestion du matériel, de son renouvellement et de sa maintenance.

**Environnement :** Debian/Linux, Proxmox, VMware ESXi, KVM, libvirt, LXC, vservers, HPE, Dell, Supermicro, Juniper.

#### Automatisation des installations et déploiements

- Automatisation semi-industrialisée de l’installation distante des serveurs selon leur usage.
- Mise en place de réseaux VLAN dédiés à l’installation et à la maintenance matérielle (iLO, iDRAC, IPMI).
- Création d’images intégrant les firmwares, de procédures d’installation et d’un miroir Debian local.
- Mise en place de chaînes de déploiement applicatif depuis un bastion, avec validation et possibilité de retour arrière sans interruption de service.
- Standardisation des applications et pilotage des recettes via Jenkins, sur un nœud de validation proche de la production.

**Environnement :** Bash, Ansible, Jenkins, Git, GitLab, Nexus, TFTP, DHCP, preseed, pfSense, HAProxy, Keepalived.

#### CI/CD et outils de développement

- Mise en œuvre et maintenance d’architectures CI/CD pour **plus de 300 applications internes**.
- Déploiement et maintenance d’outils de gestion de projets et de développement.
- Migration de dépôts CVS/SVN vers Git.

**Environnement :** Jenkins, Git, GitLab, Gitolite, SVN, CVS, Redmine, Request Tracker, OpenLDAP.

#### Haute disponibilité, réseau et services web

- Conception et exploitation de services web redondés et chiffrés, avec reverse proxy et répartition de charge.
- Gestion des DNS internes et externes.
- Mise en œuvre de mécanismes de redondance matérielle et applicative.
- Exploitation de services FTP pour la réception continue de flux de presse.
- Étude de solutions de stockage distribué pour assurer la continuité des flux en cas de panne d’un datacenter.

**Environnement :** BIND, PowerDNS, Nginx, Apache, PHP-FPM, HAProxy, Keepalived, Let's Encrypt, vsftpd, GlusterFS, lsyncd, rsync, Ceph, MinIO.

#### Bases de données, stockage et sauvegardes

- Administration des bases de données : installation, maintenance, gestion des droits, sauvegardes et réplication.
- Mise en place d’archives froides de documents de presse, répliquées sur plusieurs datacenters.
- Gestion de volumes de stockage et extensions RAID pour accompagner la croissance des données.
- Évaluation de GlusterFS, Ceph et MinIO ; choix de GlusterFS pour sa simplicité opérationnelle et la facilité de retour arrière dans le contexte étudié.

**Environnement :** PostgreSQL, MySQL, MariaDB, SQLite, Oracle 8, Redis, GlusterFS, MinIO, RAID, ZFS, rsync, backupninja.

#### Supervision, sécurité et maintien en condition

- Supervision des ressources matérielles et applicatives, centralisation et visualisation des journaux.
- Écriture de scripts de contrôle matériel et de surveillance des bases de données.
- Politique régulière de mises à jour, surveillance des logs, blocage préventif et généralisation du HTTPS.
- Gestion des sauvegardes, de l’inventaire et des outils de suivi de parc.

**Environnement :** Zabbix, Hobbit/Xymon, Smokeping, ELK (Elasticsearch, Logstash, Kibana), Filebeat, Bash, Python, unattended-upgrades, fail2ban, OpenSSL, Keycloak, GLPI, Racktables, FusionInventory.

#### Plateformes de calcul IA et traitement audio

- Déploiement et maintenance de clusters de calcul pour des projets de recherche, de transcription et de traitement de la parole (Speech-to-Text, IA/LLM), en partenariat avec l’Université d’Avignon.
- Mise en place d’un serveur d’apprentissage équipé de GPU NVIDIA RTX 3090 et de plusieurs serveurs de calcul.
- Organisation du stockage partagé entre nœuds de calcul.

**Environnement :** CUDA, lsyncd, supervisord, GlusterFS.

#### Messagerie, téléphonie et communication interne

- Administration de la messagerie interne et de ses mécanismes de filtrage, de distribution et de synchronisation.
- Supervision des éléments pouvant bloquer l’envoi de courriels aux clients ; suivi des paramètres DNS, SPF et DMARC.
- Remplacement d’une solution de téléphonie externe par une infrastructure VoIP interne.
- Déploiement d’outils de communication et de collaboration pour des équipes réparties géographiquement.

**Environnement :** Postfix, Dovecot, LDAP, Procmail, Sieve, Fetchmail, Maildrop, ClamAV, Roundcube, imapsync, Wazo, Asterisk, ejabberd, Rocket.Chat, EtherCalc, Etherpad, OpenVPN.

#### Études d’architecture et de coûts

- Étude du passage de serveurs de calcul vers un cloud public, avec comparaison des coûts sur un an par rapport à une infrastructure bare-metal.
- Analyse des solutions de stockage distribué en fonction de la robustesse, des performances et des contraintes de retour arrière.

### Développeur Zope — Nevrax
**Janvier 2006 – Janvier 2007 · Paris**

Au sein de l’éditeur du MMORPG **Ryzom**, développement web, administration des serveurs liés aux applications et accompagnement de l’équipe de développement.

- Développement et maintenance de sites web communautaires et d’outils internes.
- Participation au projet **Ryzom Ring**, notamment aux outils communautaires, à la gestion des données et au débogage.
- Administration des services web : déploiement, sauvegardes et maintenance.
- Formation et accompagnement de développeurs : Python, HTML/CSS et gestion de versions.
- Coordination avec les équipes marketing, QA et lore ; participation aux activités de test et de débogage du jeu.

**Environnement :** Python, Zope, Plone, ZEO, Squid, Apache, MySQL, CVS, Bugzilla, Bash, rsync.

## Activités indépendantes et projets personnels

**Depuis janvier 2022 · Développement de jeux et formation continue**

- Formation continue sur Ansible, Docker, CI/CD, Kubernetes et les pratiques DevOps.
- Prototypage de jeux vidéo avec **Godot** et **Unity**, avec publications sur [Itch.io](https://patrx.itch.io/).
- Participation à des game jams et à des initiatives caritatives autour du jeu vidéo.
- Déploiement et expérimentation d’infrastructures personnelles (homelab), incluant clusters Proxmox, NAS et réseau.
- Développement d’outils de détection de bots sur **Bluesky**, dans une démarche de lutte contre la désinformation.
- Développement de scripts d’archivage de contenus publics dans un contexte de collecte de preuves de harcèlement en ligne.
- Veille technologique sur l’open source, la cybersécurité et l’intelligence artificielle.

## Compétences techniques

| Domaine | Technologies et outils |
| --- | --- |
| Systèmes d’exploitation | Linux, Debian, RHEL |
| Automatisation & IaC | Ansible, Bash, Python |
| CI/CD & gestion de versions | Jenkins, Git, GitLab, Gitolite, SVN, CVS |
| Virtualisation & conteneurs | Proxmox, VMware vSphere/ESXi, KVM, libvirt, LXC, Docker |
| Stockage & sauvegardes | GlusterFS, MinIO, Ceph, rsync, lsyncd, backupninja, RAID, ZFS |
| Réseau & haute disponibilité | pfSense, OPNsense, Juniper, DNS, DHCP, VPN, HAProxy, Keepalived |
| Web & reverse proxy | Nginx, Apache, PHP-FPM, Lighttpd, Gunicorn, Squid |
| Bases de données & cache | PostgreSQL, MySQL, MariaDB, SQLite, Oracle, Redis, Memcached, CouchDB |
| Observabilité | Zabbix, Hobbit/Xymon, Smokeping, ELK, Filebeat |
| Sécurité & identité | Keycloak, OpenSSL, Let's Encrypt, fail2ban, unattended-upgrades, LDAP |
| Messagerie & VoIP | Postfix, Dovecot, Zimbra, Wazo, Asterisk |
| Files & messagerie applicative | Kafka, RabbitMQ |
| Développement | Bash, Python, C#, SQL |
| Game development | Godot, Unity |
| Outils et collaboration | Redmine, Request Tracker, GLPI, Racktables, Rocket.Chat |

## Formation

- **Master Sciences et Technologies — Ingénierie des systèmes, réseaux et applications distribués**, Université de Picardie Jules Verne — 2005–2006.
- **Maîtrise Informatique**, Université de Picardie Jules Verne — 2004–2005.
- **Licence Informatique — Intelligence artificielle**, Université de Picardie Jules Verne — 2003–2004.
- **DEUG MIAS — Mathématiques et informatique appliquées aux sciences**, Université de Picardie Jules Verne — 2001–2003.

## Langues

- Français
- Anglais

## Centres d’intérêt

- Développement de jeux vidéo et game jams.
- Préservation vidéoludique.
- Jeux de cartes à collectionner, jeux de rôle et jeux de plateau.
- Arbitre **Magic: The Gathering** pendant 10 ans ; joueur depuis environ 30 ans.
- Cybersécurité.
- Arts martiaux : Kobudo et Goju-ryu.
- Lutte contre la désinformation et veille open source.

---
