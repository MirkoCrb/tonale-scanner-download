# Tonale Scanner

App Android gratuita per l'**Alfa Romeo Tonale diesel**: tiene d'occhio il filtro antiparticolato (DPF) e avvisa quando l'auto sta rigenerando, anche su **Android Auto**.

## ⬇️ Download

**[Scarica l'ultima versione (APK)](https://github.com/MirkoCrb/tonale-scanner-download/releases/latest)**: nella pagina, sotto *Assets*, tocca il file `TonaleScanner-NN.apk`.

Per vederla su Android Auto va installata con **UnknownAuto + Shizuku** (senza root, una volta sola). Segui la guida passo passo con le immagini: **[Guida di installazione (PDF)](https://github.com/MirkoCrb/tonale-scanner-download/releases/latest/download/Guida_Tonale_Scanner.pdf)**, che trovi anche tra gli *Assets* di ogni versione.

> **Aggiornamenti:** dalla build 77 l'app ti avvisa con una notifica quando esce una versione nuova. Installala sopra la vecchia, sempre con UnknownAuto. **Non disinstallare**: perderesti lo storico delle rigenerazioni e le impostazioni.

## Prova gratuita e attivazione

L'app si prova **gratis per 7 giorni** dal primo collegamento all'auto, con tutte le funzioni. Dopo, i dati sul telefono restano liberi; per continuare ad avere **avvisi sonori e Android Auto** si sostiene il progetto con una donazione su [PayPal](https://www.paypal.me/MirkoCrabargiu) e si scrive a **mirko.crb@gmail.com** indicando il telaio (VIN), che l'app mostra in *Impostazioni › Attivazione*. Si riceve una chiave valida per quella auto.

## Cosa fa

- Intasamento DPF, avanzamento della rigenerazione, temperatura DPF, km dall'ultima rigenerazione, numero di rigenerazioni, pressione differenziale
- Avviso con suono e notifica a inizio e fine rigenerazione, promemoria ogni 5 minuti, avviso se spegni il motore durante la rigenerazione
- Schermata dedicata su Android Auto in **6 stili a scelta** (Uconnect, Sportiva carbonio, Numeri grandi e gli sportivi Corsa, Volante F1, Livrea); gli avvisi compaiono anche sopra Maps
- **Personalizza**: 6 tipi di quadrante (Tonale, con lancetta, Classico, LED, Anello, Mezzaluna), colore e spessore dell'avanzamento, 8 sfondi o una tua foto
- **La tua auto**: carichi una foto della tua auto e l'app toglie lo sfondo da sola
- Storico delle rigenerazioni: data, durata, grafico della temperatura, km tra una e l'altra, quelle interrotte
- Stima dei km alla prossima rigenerazione e dei km di AdBlue rimanenti, imparate dalla tua guida
- Livello AdBlue, tensione della batteria e **degradazione dell'olio motore**, con avvisi
- Si collega da sola quando accendi l'auto (o solo con Android Auto, a scelta) e si chiude quando la spegni
- **Prova senza auto**: dati simulati per vedere come funziona anche lontano dalla macchina
- Backup delle impostazioni e dello storico

## Cosa serve

- Telefono **Android 11** o più recente (**13** o più recente per il collegamento automatico quando sali in auto)
- Adattatore OBD **Bluetooth LE (BLE)** compatibile ELM327, testata con **Vgate iCar Pro BLE**, oppure un adattatore **Wi-Fi** (utile con gli AI Box). Dovrebbe collegarsi anche a molti altri adattatori, ma non sono stati provati. Gli adattatori Bluetooth "classici" **non** funzionano. Alcuni cloni economici si collegano ma non leggono i dati DPF: se ne provate uno, scrivete nel forum com'è andata.
- **Tonale diesel**: i dati DPF sono verificati sul 1.6 MultiJet 130 CV. Gli ibridi a benzina non hanno il DPF.

## Da sapere

- Progetto personale, **non ufficiale** e non collegato ad Alfa Romeo o Stellantis. Si usa a proprio rischio.
- Per leggere i dati l'app fa solo richieste di lettura: non modifica la centralina e non cancella errori.
- Gratuita e senza pubblicità. **I dati restano sul telefono**: internet serve solo a controllare una volta al giorno se c'è una versione nuova (si può spegnere in *Impostazioni › Aggiornamenti*).
- La foto della tua auto viene elaborata sul telefono e non viene inviata a nessuno.
- Testata su una sola auto: segnalazioni e prove su altri motori sono benvenute nella discussione sul forum Club Alfa.

## Versioni

| Versione | Novità |
| --- | --- |
| build 135 | Prova senza auto; chiusura automatica allo spegnimento; Quando collegarsi (Subito / Solo con Android Auto); stili sportivi più leggibili; notifica fissa corretta |
| build 114 | Tre stili sportivi per Android Auto (Corsa, Volante F1, Livrea); degradazione dell'olio motore in Diagnosi, con avvisi e indicazione su Android Auto |
| build 105 | Guida aggiornata: scheda Diagnosi e nuovi avvisi (app uguale alla 104) |
| build 104 | Scheda Diagnosi (codici errore, batteria, AdBlue) con avvisi, rigenerazioni totali su Android Auto, stima AdBlue corretta, Wi-Fi su AI Box |
| build 87 | Personalizza (quadranti, colore, spessore, sfondi, foto), La tua auto con sfondo tolto, adattatore Wi-Fi, quadranti ispirati al quadro della Tonale; tolta la musica |
| build 77 | Avviso di nuova versione dentro l'app; note delle release divise in Novità, Miglioramenti, Correzioni |
| build 76 | Tre stili a scelta per Android Auto e telefono: Uconnect, Sportiva carbonio, Numeri grandi |
| build 73 | Android Auto a riquadri stile Uconnect, pannello musica con Cambia app, arco Intasamento a colori, AdBlue riletto se all'avvio non risponde |
| build 64 | Guida aggiornata: attivazione con la sola chiave (app uguale alla 63) |
| build 63 | Prova gratuita di 7 giorni e attivazione con chiave legata al telaio |
| build 60 | Guida aggiornata: quali adattatori funzionano (app uguale alla 58) |
| build 59 | Guida di installazione in PDF allegata (app uguale alla 58) |
| build 58 | Prima versione pubblica |
