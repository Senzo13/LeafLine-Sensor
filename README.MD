# 🌿 LeafLine IoT Project 🌿

<div align="center" style="text-align:left">
<img src="LeafLineGif.gif" alt="Gif LeafLine" width="400px"/>
 </div>

## 🔬 Description
https://dl.espressif.com/dl/package_esp32_index.json
Bienvenue dans la partie IoT du projet LeafLine !

<p>Avec l'aide du kit <b>ELEGOO UNO R3</b>, nous surveillons et <br/>recueillons des informations vitales pour la croissance des plantes.<p>

## 🌱 Capteurs Utilisés

- 🌡️ **DHT11** : Mesure la température et l'humidité de l'air.
- 🌞 **DollaTek 5516 Photorésistance** : Permet de surveiller la luminosité ambiante.
- 🌧️ **SparkFun Soil Moisture Sensor** : Détecte l'humidité du sol pour garantir que les plantes sont bien arrosées.

### 📌 Capteurs à venir :

- 📡 **Hailege ESP32 ESP-32S ESP-WROOM-32** : Notre carte Wi-Fi pour connecter notre projet à Internet.
- 🖥️ **LCD-1602A** : Ecran LCD pour afficher les données en temps réel.

## 🔧 Configuration matérielle

- **Kit ELEGOO UNO R3** : Le cœur de notre système IoT, traitant les données des capteurs et communiquant avec le serveur.

## 📚 Bibliothèques utilisées

Adafruit_sensor (à ajouté en .zip dans librairy sur Arduino) https://www-arduinolibraries-info.translate.goog/libraries/adafruit-unified-sensor?_x_tr_sl=en&_x_tr_tl=fr&_x_tr_hl=fr&_x_tr_pto=sc
DHT (à ajouté en .zip dans librairy sur Arduino) https://www.arduinolibraries.info/libraries/dht-sensor-library
`#include "LiquidCrystal.h"` ➤ Pour l'affichage sur écran LCD<br/>
`#include "Measurement.h"` ➤ Une classe personnalisée pour gérer et traiter les données des capteurs<br/>
`#include <WiFiEsp.h> ` ➤ Gère la connectivité Wi-Fi de l'Arduino<br/>
`#include <DHT.h>` ➤ Pour le capteur DHT11<br/>

## 💻 Langage de programmation

Utilisation de **C++ Arduino** pour programmer et gérer le dispositif IoT.
