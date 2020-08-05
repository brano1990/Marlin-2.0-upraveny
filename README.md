# Marlin-2.0-upraveny
Marlin 2.0  upraveny
#define CUSTOM_MACHINE_NAME "Slovensko :-))"  -názov tlačiarne   -nájdeš Configuration.h

#define LCD_LANGUAGE sk  -zmena jazyka                     -nájdeš Configuration.h

#define DEFAULT_AXIS_STEPS_PER_UNIT   { 80, 80, 400, 98 }posledné číslo(98) som zmenil  z pôvodných 93 je to nakrokovanie môjho extrudera môže sa meniť v závislosti od filamentu treba to nastaviť podľa seba je nato aj aj parádne české video na YouTube    -nájdeš Configuration.h

#define X_BED_SIZE 232  rozmer plochy zarovno od trysky po plochu (manuálne vymerať ale nie je treba toto postačuje sú tam rezervy cca 2mm )  -nájdeš Configuration.h
#define Y_BED_SIZE 231   rozmer plochy zarovno od trysky po plochu (manuálne vymerať ale nie je treba toto postačuje sú tam rezervy cca 2mm) -nájdeš Configuration.h

----Toto by mala byt home pozícia-----"parkovanie"---inak je to pozícia osi ku koncovým spínačom ---------------------------------------
#define X_MIN_POS 3    vzdialenosť od koncového snímača +3    -nájdeš Configuration.h
#define Y_MIN_POS -6   vzdialenosť od koncového snímača +6    -nájdeš Configuration.h
#define Z_MIN_POS 0                                           -nájdeš Configuration.h
#define X_MAX_POS 232                                         -nájdeš Configuration.h
#define Y_MAX_POS 231                                         -nájdeš Configuration.h
#define Z_MAX_POS 250   vzdialenosť vrchu (tu žiaden spínač nie je s rezervou cca 3mm ) 
---------------------------------------------------------------------------------------------
#define LEVEL_BED_CORNERS - od komentoval som to týmto som spustil kalibráciu podložky podľa rohou v menu  -nájdeš Configuration.h

//#define SHOW_BOOTSCREEN -  za komentoval som čiže zakázal boot obrázok                       -nájdeš Configuration.h

#define POWER_LOSS_RECOVERY - od komentoval som to obnova po výpadku elektriny                 - nájdeš v Configuration_adv.h

//#define ARC_SUPPORT - toto som za komentoval toto neni potrebne na endera 3 ušetrime pamäť  - nájdeš v Configuration_adv.h

#define BOOT_MARLIN_LOGO_SMALL    od komentoval som to ušetrím tým pamäť je to malé logo      - nájdeš v Configuration_adv.h
 
//#define CUSTOM_STATUS_SCREEN_IMAGE za komentoval som zrušil som nejaký štartovací obrázok    -nájdeš Configuration.h

//#define LCD_INFO_MENU - za komentovaním som schoval info o tlačiarni ušetrime pamäť            - nájdeš v Configuration_adv.h
