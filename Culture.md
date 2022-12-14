# LABO HARDWARE

# Sommaire
- [LABO HARDWARE](#labo-hardware)
- [Sommaire](#sommaire)
- [I. Brainfuck](#i-brainfuck)
- [II. Other say](#ii-other-say)
  - [1. La place des femmes dans l'inforamtique](#1-la-place-des-femmes-dans-linforamtique)
  - [2. Internet ](#2-internet-)
  - [3. Minitel](#3-minitel)
  - [4. Socket](#4-socket)
    - [B les générations](#b-les-générations)
  - [5. Ventilo boîtier](#5-ventilo-boîtier)
    - [Airflow](#airflow)


# I. Brainfuck

Inventé par Urban Müller en 1993. 
L'objectif était d'avoir un language simple, avec une taille de compilateur la plus réduite possible et pouvant tourner même sur une machine de Turing ()

|----------||
|Caractère | Signification |
|----------|---------------|
| > | incrémente (augmente de 1) le pointeur |
| < | décrémente (diminue de 1) le pointeur. |
| +​ | incrémente l'octet du tableau sur lequel est positionné le pointeur (l'octet pointé).|
| -​ | décrémente l'octet pointé.| 
| . | sortie de l'octet pointé (valeur ASCII).
| , | entrée d'un octet dans le tableau à l'endroit où est positionné le pointeur (valeur ASCII).
| [ | saute à l'instruction après le ] correspondant si l'octet pointé est à 0.
| ] | retourne à l'instruction après le [ si l'octet pointé est différent de 0.

# II. Other say

## <u>1. La place des femmes dans l'inforamtique</u>

Présnte au début mais vite éloigné du domaine. 

## <u>2. Internet </u>

APRPANet réservé plus à l'armée


## <u>3. Minitel</u>

1970 20Million 

Réseau transpack 100% fr -> qui passe par le réseau téléphonique

Les machines peuvent seuemet communiquer avec les serveurs.

Même avec l'apparation d'internet, banque et aéroport fonctionnent avec réseau transpack. 2012 fin du réseau transpack

## 4. Socket

socket = là où va se fiwer le processeur sur la carte mère.

Intel : (LGA = pin sur le socket) 1151 - 1200 - 1700 -> le nombre correspond au nombre de pin


AMD : 3 - 4 - 5 (PGA = pin sur le processeur)

De 3 à 4 (pin sur le processeur). Mais sur 5 passe sur du LGA 

Sous AM4 tout est compatible avec. Si

AMD: 1700 -> 1 = 1er génération


### B les générations

- AM4 : 1er -> 5° gen RYZEN
- AM5 : 7° gen RYZEN

AMD:
  - x3xx : RYZ = N3 = 4 coeurs 8 threads
  - x5xx : 6 coeurs 12 threads
  - x7xx : 8 coeurs 12 threads
  - x8xx : 8 coeurs 12 threads
  - x9xx :

-> Ax20 -> x = Generation / 1 slot de RAM; 1 slot d'extension / 

-> Bx50 -> 2-4 slots de RAM / overclocking possible

-> Xx70 -> 4 slots de RAM / RGB par le BIOS / 


Intel

K =  overclocking possible
F = sans interface graphique
H = laptop

Tyope carte mère
  - Hx10 -> Bas de gamme / peu d'option / pas d'overclocking
  - Bx60 -> Entrée de gamme / Plus d'option dans le BIOS / pas d'overclocking / plus de slots
  - Hx70 -> Millieu de gamme ++ / overclocking possible / 
  - Zx90 -> Haut de gamme / plus d'option

Génération carte mère
  - 4-10° -> Hx10 - Bx60
  - 5-12° -> Hx70 - Zx90

## 5. Ventilo boîtier

### Airflow

Plusieurs types de pressions:
  - Pression négative
  - Pression Positive
  - Pression neutre : entre à l'avant et sort en arrière

2 types d'hélices:
  - Fine
  - Large 

2 types de roulement:
- Bille (plus cher et centre l'hélice)
- Bague huilé (petit mouvement parasyte)
  
Les connectiques:
- 4 : Ground (-), 12V DC (+), RPM Signal (from Fan), PWM Signal (from MB)
- 3 : Ground (-), 12V DC (+), RPM Signal (from Fan)