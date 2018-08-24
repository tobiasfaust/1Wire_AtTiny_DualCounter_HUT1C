# 1Wire_AtTiny_DualCounter_HUT1C
a 1Wire DualCounter with a ATTiny25 Emulation

### original code forked from https://www.tm3d.de/elektronik-projekte/alte-sachen/1-wire-simulation-alt

Zitat des Urhebers:
### DS2423 Emulation auf ATtiny25 und ATtiny2313
Emulation eines DS2423 DualCounters auf einem ATtiny25. Der NVRAM ist nicht mit implementiert. Die 
Trigger-Eingänge für die beiden Zähler sind PB3 und PB4. Eine Schaltung von p4trykx ist im im owfs-Forum (http://comments.gmane.org/gmane.comp.file-systems.owfs.devel/9614) zufinden. 
Zusätzlich habe ich auch die Anpassung für den ATtiny2313 mit angefügt. Der Code beinhaltet auch die Funktionen Skip-Rom und 
Read-Rom. Allerdings müssen diese erst in Zeile 180 aktiviert werden.
