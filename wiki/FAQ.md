# FAQ - Domande Frequenti

## Generale

### Cos'è POWN METER?
Una webapp che monitora i tuoi post Facebook, cattura le screenshot di chat che pubblichi, e crea una dashboard gamificata con statistiche sul "cringe level" dei messaggi che ricevi.

### È gratis?
Sì, completamente gratuito.

### Devo installare qualcosa?
No, è tutto web-based. Basta un browser.

---

## Facebook

### Perché serve collegare Facebook?
Per monitorare automaticamente i tuoi post e catturare le screenshot che pubblichi. Senza collegamento, dovresti caricare tutto manualmente.

### Quali permessi chiede?
Solo la lettura dei tuoi post. **Non** chiediamo accesso a messaggi privati, lista amici, o possibilità di postare a tuo nome.

### I miei post sono privati, funziona?
Sì! Quando autorizzi l'app, ci dai il permesso di vedere i tuoi post, anche se non sono pubblici.

### Posso scollegare Facebook?
Sì, in qualsiasi momento dalle Impostazioni. Puoi anche revocare l'accesso direttamente da Facebook.

### POWN METER può postare a mio nome?
**NO**. Non chiediamo quel permesso e non è tecnicamente possibile.

---

## Privacy

### I miei dati sono al sicuro?
- I token di accesso sono criptati
- Non condividiamo dati con terzi
- Non vendiamo i tuoi dati
- Puoi cancellare tutto in qualsiasi momento

### Chi può vedere la mia dashboard?
Solo tu, a meno che non scegli di renderla pubblica nelle impostazioni.

### Posso nascondere nomi e foto nelle screenshot?
Sì, c'è un'opzione per il blur automatico prima della condivisione.

### Come cancello il mio account?
Impostazioni → Account → Elimina Account. Tutti i tuoi dati vengono rimossi.

---

## Funzionamento

### Ogni quanto controlla i nuovi post?
Di default ogni 15 minuti. Puoi cambiare la frequenza nelle impostazioni (5 min - 1 ora).

### Come fa a riconoscere le screenshot di chat?
Usa intelligenza artificiale per:
1. Riconoscere il layout tipico delle chat (Messenger, WhatsApp, etc.)
2. Estrarre il testo con OCR
3. Analizzare il contenuto

### A volte non cattura un mio post, perché?
Possibili motivi:
- Il post non contiene immagini
- L'immagine non è riconosciuta come screenshot di chat
- Il sistema è ancora in fase di apprendimento

Puoi segnalare i falsi negativi per migliorare il riconoscimento.

### Come funziona il Cringe Score?
Un algoritmo AI analizza il testo e assegna punteggi basati su:
- Livello di disperazione
- Originalità (o mancanza di)
- Persistenza/insistenza
- Errori grammaticali
- Uso emoji inappropriato
- Pattern tipici di comportamento cringe

### Le categorie sono accurate?
Il sistema impara con il tempo. Se una categoria è sbagliata, puoi correggerla manualmente.

---

## Gamification

### Come guadagno punti?
- Nuovo specimen catturato: +10 punti (moltiplicato per cringe score)
- Voti ricevuti: +5 punti ciascuno
- Achievement sbloccati: bonus variabili

### Posso perdere punti?
No, i punti non si perdono mai.

### Gli achievement scadono?
No, una volta sbloccati restano per sempre.

### C'è una classifica?
Sì, ma solo tra utenti che hanno scelto di rendere pubblica la loro dashboard.

---

## Condivisione

### Posso condividere le screenshot?
Sì! Ci sono pulsanti per condividere su Facebook, Twitter, WhatsApp, Telegram e altri.

### Cosa viene condiviso?
Un'immagine con la screenshot originale + un overlay con il cringe score e categoria. Opzionalmente con blur sui nomi.

### Il link porta alla mia dashboard?
Solo se la tua dashboard è pubblica. Altrimenti porta a una pagina di preview limitata.

---

## Problemi Tecnici

### L'app non trova i miei post
1. Verifica che Facebook sia collegato (Impostazioni)
2. Aspetta 15 minuti dopo la connessione
3. Prova a forzare un controllo manuale
4. Controlla che i post contengano immagini

### Le notifiche non arrivano
1. Verifica che le notifiche siano abilitate nelle impostazioni
2. Controlla le impostazioni notifiche del tuo browser
3. Prova a disabilitare e riabilitare

### La pagina non si carica
1. Prova a ricaricare (Ctrl+F5)
2. Svuota la cache del browser
3. Prova un altro browser
4. Controlla la tua connessione internet

### Altro problema?
[Apri una Issue](../../issues/new?template=bug_report.md) con i dettagli del problema.

---

*Altre domande? [Contattaci](../../issues)*
