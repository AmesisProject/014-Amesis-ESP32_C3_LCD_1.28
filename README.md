# ESP32_C3_LCD_1.28
Comment programmer un écran ESP32 C3 LCD 1.28" Tactile dans l'IDE ARduino
Voici un exemple de code qui simule une sonde AFR et un cadran RPM vitesse moteur

## Photos
<P>
<img src="https://github.com/AmesisProject/014-Amesis-ESP32_C3_LCD_1.28/blob/main/Visuel/Photo2.png" width="307" hspace="30" />
<img src="https://github.com/AmesisProject/014-Amesis-ESP32_C3_LCD_1.28/blob/main/Visuel/Photo.png" width="300" />
</P>
## Viedos

https://youtube.com/shorts/v-2n1YXnOEw?si=QRJvghyAqLN_8sJP

https://youtube.com/shorts/3pu_u2d-Tx4?si=zI3GUF_M9BrRnhQM

## Installation

Dans l'IDE arduino "Ficher->Preference->Emplacement du carnet de croquis" Il faut metre l'adresse de la librairie du dossier qui est avec le programme arduino.
Cette librairie est dans ce repos C:\ProgrammePerso\GitHub\014-Amesis-ESP32_C3_LCD_1.28\Fichier\Arduino_Code_Jauge
Ensuite il faut mettre ce lien dans les gestions de cartes supplémentaires, toujour dans l'onglet préference

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json

<img src="https://github.com/AmesisProject/014-Amesis-ESP32_C3_LCD_1.28/blob/main/Visuel/Preference%20IDE%20arduino.png" width="1000" />

Ensuite dans l'onglet "Outils->Type de carte->Gestionnaire de carte" Taper "ESP32" et installer

La Vertion 2.0.6 MEME SI IL EXISTE DES PLUS RECENTE, sinon cela ne fonctionnera pas !!!

<img src="https://github.com/AmesisProject/014-Amesis-ESP32_C3_LCD_1.28/blob/main/Visuel/AjoutDeCarte.png" width="1000" />

Ensuite dans "Outils" veuillez régler les parammetre de la carte comme suite. 

Attention dans type de carte il faut bien choisir ESP32C3 Dev Module même si dans elle est reperée comme ESP32S3 Dev Module dans le port COM choisis.

<img src="https://github.com/AmesisProject/014-Amesis-ESP32_C3_LCD_1.28/blob/main/Visuel/ParametreCarteESP32C3.png" width="1000" />


Vous pouvez a présent choisir le bon port COM et televerser le code.

## Shemas Electrique

<img src="https://github.com/AmesisProject/014-Amesis-ESP32_C3_LCD_1.28/blob/main/Visuel/s-l1600.jpg" width="1000" />

## Liens

Ecran :

https://fr.aliexpress.com/item/1005005529878972.html?spm=a2g0o.productlist.main.11.1582oWeBoWeBX3&algo_pvid=25b1d736-9f33-453d-a15b-5d9342ef8d0b&algo_exp_id=25b1d736-9f33-453d-a15b-5d9342ef8d0b-5&pdp_npi=4%40dis%21EUR%2117.41%2116.29%21%21%2118.28%2117.10%21%40211b617b17198671596773038ece20%2112000037404171515%21sea%21FR%214081116368%21&curPageLogUid=FhJome33Pds8&utparam-url=scene%3Asearch%7Cquery_from%3A

https://fr.aliexpress.com/item/1005006049702059.html?spm=a2g0o.productlist.main.19.1582oWeBoWeBX3&algo_pvid=25b1d736-9f33-453d-a15b-5d9342ef8d0b&algo_exp_id=25b1d736-9f33-453d-a15b-5d9342ef8d0b-9&pdp_npi=4%40dis%21EUR%2118.47%2118.47%21%21%2119.39%2119.39%21%40211b617b17198671596773038ece20%2112000035491409365%21sea%21FR%214081116368%21&curPageLogUid=oqHTfrH84XHb&utparam-url=scene%3Asearch%7Cquery_from%3A

Download Fichier livré avec :
http://pan.jczn1688.com/directlink/1/ESP32%20module/3.2inch_ESP32-2432S032.zip

DataSheet :
https://docs.espressif.com/projects/esp-dev-kits/en/latest/esp32c3/esp32-c3-lcdkit/user_guide.html

