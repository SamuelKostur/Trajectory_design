# Trajectory_design
Tento súbor obsahuje návod ako spustiť aplikáciu Trajectory_design.mlapp  
Pred spustením aplikácie `Trajectory_design.mlapp` je potrebné vykonať nasledujúce kroky:
1. Stiahnuť repozitár https://github.com/jonabalzer/braccio_description ako ZIP archív,  
   obsahujúci urdf súbor s opisom robota Tinkerkit Braccio a všetky ďalšie potrebné súbory.
2. Extrahovať stiahnutý ZIP archív, čím sa vytvorí priečinok.
3. Vytvorený prečinok pridať k vyhľadávacím cestám Matlabu.
4. V Matlabe nainštalovať Robotics System Toolbox.
5. Stiahnuť aplikáciu `Trajectory_design.mlapp` do ľubovolného priečinku.
6. V príkazovom riadku Matlabu napísať "appdesigner" 
    ````
    >> appdesigner;
    ````
    
7. Po otvorení okna App Designer stlačiť tlačidlo "Open..."
8. Otvorí sa prieskumník, a pomocou prieskumníka otvoriť aplikáciu `Trajectory_design.mlapp`
9. Uvedeným postupom sa otvorí v App Designeri aplikácia `Trajectory_design.mlapp`
   * kliknutím na "Code View" je možné vidieť zdrojový kód aplikácie
   * aplikáciu je možné spustiť tlačidlom "Run", ktoré sa nachádza v karte "DESIGNER" hornej lišty App Designeru
