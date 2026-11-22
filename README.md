# Tonale Scanner

App Android gratuita per l'**Alfa Romeo Tonale diesel**: tiene d'occhio il filtro antiparticolato (DPF) e avvisa quando l'auto sta rigenerando, anche su **Android Auto**.

## ⬇️ Download

**[Scarica l'ultima versione (APK)](https://github.com/MirkoCrb/tonale-scanner-download/releases/latest)**: nella pagina, sotto *Assets*, tocca il file `TonaleScanner-NN.apk`.

Per vederla su Android Auto va installata con **UnknownAuto + Shizuku** (senza root, una volta sola). Segui la guida passo passo con le immagini: **[Guida di installazione (PDF)](https://github.com/MirkoCrb/tonale-scanner-download/releases/latest/download/Guida_Tonale_Scanner.pdf)**, che trovi anche tra gli *Assets* di ogni versione.

> **Aggiornamenti:** installa la nuova versione sopra la vecchia, sempre con UnknownAuto. **Non disinstallare**: perderesti lo storico delle rigenerazioni e le impostazioni.

## Cosa fa

- Intasamento DPF, avanzamento della rigenerazione, temperatura DPF, km dall'ultima rigenerazione, numero di rigenerazioni, pressione differenziale
- Avviso con suono e notifica a inizio e fine rigenerazione, promemoria ogni 5 minuti, avviso se spegni il motore durante la rigenerazione
- Schermata dedicata su Android Auto; gli avvisi compaiono anche sopra Maps
- Storico delle rigenerazioni: data, durata, grafico della temperatura, km tra una e l'altra, quelle interrotte
- Stima dei km alla prossima rigenerazione e dei km di AdBlue rimanenti, imparate dalla tua guida
- Livello AdBlue e tensione della batteria
- Backup delle impostazioni e dello storico

## Cosa serve

- Telefono **Android 11** o più recente (**13** o più recente per il collegamento automatico quando sali in auto)
- Adattatore OBD **Bluetooth LE (BLE)** compatibile ELM327, testata con **Vgate iCar Pro BLE**. Dovrebbe collegarsi anche a molti altri adattatori BLE, ma non sono stati provati. Gli adattatori Bluetooth "classici" e Wi-Fi **non** funzionano. Alcuni cloni economici si collegano ma non leggono i dati DPF: se ne provate uno, scrivete nel forum com'è andata.
- **Tonale diesel**: i dati DPF sono verificati sul 1.6 MultiJet 130 CV. Gli ibridi a benzina non hanno il DPF.

## Da sapere

- Progetto personale, **non ufficiale** e non collegato ad Alfa Romeo o Stellantis. Si usa a proprio rischio.
- Per leggere i dati l'app fa solo richieste di lettura: non modifica la centralina e non cancella errori.
- Gratuita, senza pubblicità e **senza permesso di accesso a internet**: i dati restano sul telefono.
- Testata su una sola auto: segnalazioni e prove su altri motori sono benvenute nella discussione sul forum Club Alfa.

## Versioni

| Versione | Novità |
| --- | --- |
| build 60 | Guida aggiornata: quali adattatori funzionano (app uguale alla 58) |
| build 59 | Guida di installazione in PDF allegata (app uguale alla 58) |
| build 58 | Prima versione pubblica |
