# Scherzo Finestra Infinita

Questo script in VBScript crea un ciclo infinito di finestre di dialogo che scherzosamente invita l'utente a "chiudere la finestra". Ogni volta che si chiude una finestra, ne appare un'altra con messaggi sempre più provocatori, rendendo difficile la chiusura.

## Funzionalità

- **Messaggi Infiniti**: visualizza una serie di messaggi in un ciclo infinito che prendono in giro l'utente, dando l'impressione che non possa chiudere le finestre.
- **Messaggi Personalizzati**: ogni finestra visualizza un messaggio diverso per aumentare l'effetto comico.

## Requisiti

- Sistema operativo Windows con supporto VBScript

## Utilizzo

1. Esegui il file `.vbs` facendo doppio clic.
2. Le finestre di dialogo appariranno in sequenza, ognuna con un messaggio diverso.
3. Per fermare lo script, dovrai terminare il processo VBScript manualmente, ad esempio tramite **Gestione Attività** di Windows (Ctrl + Shift + Esc).

## Codice

```vbscript
Do
    m1 = MsgBox("Chiudi questa finestra", , "Provaci")
    m2 = MsgBox("Riprova", , "Provaci")
    m3 = MsgBox("Dai, Riprova", , "Provaci")
    m4 = MsgBox("Non ci riesci?? ah ah ah", , "Non ci riuscirai")
Loop
```

## Disclaimer

> **ATTENZIONE**: Questo script è pensato esclusivamente come scherzo innocuo per intrattenere o per esercitazione. 
> **Non eseguirlo su computer altrui senza autorizzazione**, poiché può risultare fastidioso e richiedere l'intervento manuale per essere chiuso. Eseguire questo script potrebbe causare frustrazione all'utente e potrebbe essere considerato inappropriato in contesti professionali o scolastici.

## Autore

Creato da HighMark come esempio di scherzo in VBScript.
