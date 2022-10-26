# LABO HARDWARE: Jour 1
# Sommaire
- [LABO HARDWARE: Jour 1](#labo-hardware-jour-1)
- [Sommaire](#sommaire)
- [Composition](#composition)
  - [Essentiels](#essentiels)
  - [Secondaire](#secondaire)
  - [Facultatifs](#facultatifs)
- [TP Demontage & remontage de PC fixe](#tp-demontage--remontage-de-pc-fixe)
  - [Demontage](#demontage)
  - [Remontage](#remontage)
- [Remarque](#remarque)

# Composition   

## Essentiels 

- Carte mère 
  - Relie les composant
  - Composé du BIOS
    - BIOS = info pc avannt OS
      - Sans Pile = pas BIOS
      - redémarre pendant MJ Bios = <b>PV MORT</b>
  - Connectique et de slots
- Processeur (k = Carte graphique, KF = pas de carte graphique)
  - Séquenceur
    - Unité de contrôle
    - Déocde les instructons
    - Gère les interruptions
    - Iitialise le registre
  - Unité entrée-sortie
  - horloge 
    - Vitesse
    - Fréquence d'horloge
  - registres
  - Cerveau de la machine
    - reçoit, interprête et distribue les tâches
  - Nombre de coeur (Thread)
    - + de coeurs = - de temps de calcule / application
      - 
- RAM
  - Mémoire vive
  - Stocke et transmet les info aléatoirement
  - Opposition avec mémoir disque dur
  - RAM = Disque dur écrit et éffacé tout le temps
- Alim
  - 2 types
    - Alim fixe / de tour
      - Regarder  la puissance (W)
        - Regarder ce quelle peut délirer
    - Alim portable
      - batterie en mA/h (sur le PC les + puissant 22)
      - si on donne moins de tension : ne pas charger
      - si on donne plus de tension : surchauffe et grille
      - Diff de 2-3 A à éviter alors que diff de 2-3 V ça passe
- Ventirad
  - Refroidit les composant

## Secondaire

- Disque de stockage
  - Interne ou externe 
  - Stocke les infos
  - Disque externe
    - On peut y mettre un OS
      - Au débranchement, PC s'éteint
  - HDD
    - Hard Drive Disk
      - 16 T max
      - 7200 tour/min
        - Plus il tourne vite plus l'info circule vite
      - Fonctionne par sys de disque
    - SSD
      - 600 Mo/s
      - A privilligier pour l'OS
    - Bus de communication
      - IDE = Interated Drive Electronics
      - PCI = Preip Component Interconnect
      - PCIe/PCI-E = PCI Express
      - Sata = Serial advanced Technology Attachment
      - M.2 = NGFF = Next Generation Form Factor
      - NVMe = Non-volatile Memory Express
    - Type de stockage (modifiable que par le BIOS)
      - AHCI
      - UEFI
      - RAID
        - Principalement pour server
        - Peut se modifier par Windows
        - RAID 0 et RAID 1 = 1 disk oou 2 Disk qui en fait 1
- Ventilateur
  - Refroidit l'ensemble des composant
  - Ventilo à l'avant (entre 2 et 3)
    - Aspire l'air frais
  - Ventilo à l'arrière (1)
    - Expire ce que la carte à fait chauffé
- Carte Graphique (ou carte vidéo ou adaptateur grphique)
  - Périphérique graphique
  - Processeur grahique
- Interface
  - Graphique
  - Audio numérique
    - HDMI, S/PDIF (jack rouge, jaune, blanc)
  - Audio analogique
  - Lecteur carte m"moire
  - Réseau
  - Périphérique
    - USB 3.0 (encadré par du rouge) plus rapide que 2.0
- Carte son
- Ecran
- Clavier
- Souris / Pad tactile 

## Facultatifs

- Lecteur/Graveur DVD/CD
- Webcam interne


# TP Demontage & remontage de PC fixe

## Demontage

- Tout décâbler
- Se libérer le chemin pour sortir la carte mère
  - Ventilo externe
  - lecteur/graveur ...
  - Disque (s'ils gênent)
- Sortir la Carte graphique
- Sortir la carte mère
- Démanteler la carte mère
  - RAM
  - VentiRad
  - Process
    - <b>ATTENTION : Ne pas laisser de saleté dessus</b>

## Remontage

- Monter sur la carte mère
  - Process
  - Venti-Rad
  - RAM
- Remettre la carte mère
- Lecteur/graveur
- Disque
- Alim 
- Tous re-câbler (en terminant par l'alim)

# Remarque

RAS