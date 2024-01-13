# Luggage-Tracking-system-with-IoT
Gestion des bagages connectes (suivie, peotection...)
# Problématiques à résoudre
Perte de bagages : Le projet de bagage connecté aide à résoudre le problème des bagages perdus en fournissant un suivi en temps réel de la localisation du bagage.
Inquiétude des voyageurs : Il apaise les inquiétudes des voyageurs en leur permettant de suivre leurs bagages, ce qui réduit le stress lié à la perte ou à la détérioration des bagages.
Efficacité de Voyage : Il améliore l'efficacité du voyage en fournissant des informations sur l'état du vol et la conformité aux règles de sécurité.
Sécurité des Biens : Il contribue à la sécurité des biens en aidant les voyageurs à localiser rapidement leurs bagages en cas de vol.
Confort et Expérience Client : Il améliore l'expérience client en offrant des fonctionnalités telles que le suivi des bagages, l'enregistrement en ligne, et des notifications en temps réel.
Satisfaction du client : Il augmente la satisfaction des clients en réduisant les problèmes liés aux bagages et en offrant un service de qualité.
Optimisation des opérations aéroportuaires : Il contribue à l'optimisation des opérations aéroportuaires en réduisant la charge de travail liée aux réclamations pour les bagages perdus.
Économies pour les Compagnies Aériennes : Il permet aux compagnies aériennes de réaliser des économies en réduisant les coûts liés à la gestion des bagages perdus.
Gestion des Volumes de Bagages : Il aide les compagnies aériennes à mieux gérer les volumes de bagages et à optimiser les flux dans les aéroports.
Réduction de l'Impact Environnemental : Il contribue à la réduction de l'impact environnemental en minimisant les déplacements inutiles des voyageurs pour retrouver leurs bagages perdus.

# Objectifs du projet
Le projet de bagages connectés est un projet qui a comme objectif de présenter un produit final qui intègre des caractéristiques telles que le chargement de l'appareil, le suivi GPS, les serrures électroniques, les contrôles à distance via une application, la connectivité Bluetooth et Wi-Fi, les balances électroniques et une batterie en Lithium-ion. Ces éléments clés ont été identifiés pour répondre aux besoins clients cibles que sont les voyageurs individuels, les compagnies aériennes, routières et maritimes, où bien même les hôtels. 
![image](https://github.com/RavenMorgan/Luggage-Tracking-system-with-IoT/assets/93053186/73a9a007-23e4-4a21-93b3-0e615c62ed24)

Liste des Conceptions et Protocoles avec les Technologies Associées :

Module GPS (GPS module SKG13BL) :

Description : Fournit des coordonnées précises du bagage en temps réel via le système de positionnement global (GPS).
Technologie : Utilise le protocole NMEA pour recevoir les données de positionnement avec des chaînes au format $GPGGA.
Module GSM (GSM module SIM900A) :

Description : Permet la communication bidirectionnelle via des messages SMS pour transmettre les coordonnées du bagage.
Technologie : Communication série entre Arduino et le module GSM via la bibliothèque SoftwareSerial.
Écran LCD 16x2 (LiquidCrystal Library) :

Description : Interface visuelle pour afficher des messages de statut ou les coordonnées du bagage.
Technologie : Utilise la bibliothèque LiquidCrystal pour une gestion simplifiée de l'affichage.
Arduino UNO :

Description : Cerveau central coordonnant les interactions entre GPS, GSM, et l'écran LCD.
Technologie : Programmation en langage C++ pour la gestion des entrées/sorties et le traitement des données.
Connectivité Série (SoftwareSerial Library) :

Description : Établit la connectivité série entre le module GPS, le module GSM et Arduino.
Technologie : Utilise la bibliothèque SoftwareSerial pour une communication efficace.
Alimentation :

Description : Utilise une alimentation de 12 volts pour garantir une alimentation stable du GPS et du GSM.
Technologie : Source d'alimentation externe pour éviter les dysfonctionnements liés à une alimentation instable.
Potentiomètre 10 K :

Description : Ajuste le contraste ou la luminosité de l'écran LCD pour une visibilité optimale.
Technologie : Réglage du contraste de l'écran LCD via le potentiomètre.

![image](https://github.com/RavenMorgan/Luggage-Tracking-system-with-IoT/assets/93053186/95964e8c-7eb5-400b-a4a6-cf68d5abd3b6)



