# Neprekinjena ADC pretvorba

1. Cilj naloge: S pomočjo programskega okolja STM32CubeIDE in HAL knjižnicami sprogramirajte mikroprocesor tako, da bo izvajal neprekinjene ADC        pretvorbe z izbranim potenciometrom. Takšna pretvorba je primerna za hitro in nenehno branje vhodne vrednosti.  
2. Postopek inicializacije periferije
   - Uporabljena razvojna plošča je **NUCELO-G431RB**.
   - Izbran pin je **PA0** na plošči je to **A0**.  
   - Poleg pina se izpiše **ADC1_IN1**.
   - Opazimo da se spremeniju toudi druge stvari npr. HCLK je zdaj **64 MHz** namesto **170 MHz**.
   - Ppreskalirana frekvenc je **16 Mhz**.
   - fpreskaliran 16Mhz
