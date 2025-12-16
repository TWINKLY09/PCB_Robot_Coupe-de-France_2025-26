Ce fichier résume les connexions et composants présents sur le pcb du  robot.

Les composants:

- 2x PCF8574T (expandeur i²C)
- 2x (levels shiffters)
- 2x ADS1115 (lecteurs analogiques i²C en 16 bits)
- 1x TCA (switch i²C)
- 7x WS2812B (leds adressables / neopixels)
- 2x Ardduino Uno R3 avec cnc shield et driver A4988 (contrôleurs moteurs)
- 1x ESP32 Wroom (cerveau du robot)
- 5x Résistances 330 Ω (sur lignes de données des leds adressables / neopixels)
- 4x Borniers 2 broches (alim)
- 6x Borniers 3 broches (alim / electrovannes / pompes)
- 6x connecteurs jst 2.54mm de 3 broches (pour les servos moteurs)
- 4x connecteurs jst 2.54mm de 6 broches (pour capteurs couleur)
- 8x connecteurs jst 2.54mm de 6 broches (pour capteurs tof {laser de distance} et ventiateurs) //peuvent êtres remplacés par des connecteurs jst 2.54mm de 4 broches si soudés complètement à droite.

Les connexions :
