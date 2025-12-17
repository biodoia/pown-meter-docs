# Connettere Facebook - Guida Completa

## Perché Serve Facebook?

POWN METER monitora automaticamente i tuoi post per catturare le screenshot che pubblichi. Per farlo, ha bisogno di accesso (in sola lettura) ai tuoi post.

---

## Come Funziona

### 1. Clicca "Connetti Facebook"

Dalla tua dashboard, trovi il pulsante blu "Connetti Facebook".

### 2. Popup di Autorizzazione

Si apre una finestra di Facebook che ti chiede di autorizzare l'app.

```
┌─────────────────────────────────────────┐
│         f  Facebook                      │
├─────────────────────────────────────────┤
│                                          │
│  POWN METER vuole accedere a:           │
│                                          │
│  ✓ I tuoi post pubblici                 │
│  ✓ Le immagini nei tuoi post            │
│                                          │
│  [Continua come Mario]  [Annulla]       │
│                                          │
└─────────────────────────────────────────┘
```

### 3. Conferma

Clicca **"Continua come [tuo nome]"**.

### 4. Fatto!

Verrai reindirizzato alla dashboard. Vedrai:

```
✅ Facebook connesso
Profilo: Mario Rossi
Ultimo controllo: adesso
Prossimo controllo: tra 15 minuti
```

---

## Permessi Spiegati

### Cosa Chiediamo

| Permesso | Perché |
|----------|--------|
| `public_profile` | Per sapere chi sei |
| `user_posts` | Per leggere i tuoi post |

### Cosa NON Chiediamo

- ❌ Accesso ai messaggi privati
- ❌ Lista amici
- ❌ Possibilità di postare a tuo nome
- ❌ Email o telefono
- ❌ Informazioni sensibili

---

## Post Pubblici vs Privati

### Se i tuoi post sono PUBBLICI
Funziona tutto automaticamente. Nessuna configurazione extra.

### Se i tuoi post sono PRIVATI (solo amici)
L'autorizzazione Facebook ci permette di vederli comunque, perché tu ci hai dato il permesso esplicito.

### Se i tuoi post sono SUPER PRIVATI (solo io)
Anche questi li vediamo, sempre grazie alla tua autorizzazione.

---

## Frequenza di Controllo

Di default, controlliamo ogni **15 minuti** se hai nuovi post.

Puoi cambiare la frequenza nelle Impostazioni:
- 5 minuti (più reattivo, più consumo)
- 15 minuti (default, bilanciato)
- 30 minuti (meno frequente)
- 1 ora (risparmio massimo)

---

## Scollegare Facebook

Vuoi scollegare l'account?

1. Vai su **Impostazioni** → **Account**
2. Clicca **"Scollega Facebook"**
3. Conferma

Puoi anche revocare l'accesso direttamente da Facebook:
1. Facebook → Impostazioni → App e siti web
2. Trova "POWN METER"
3. Clicca "Rimuovi"

---

## Troubleshooting

### "Non vedo il popup"
- Disabilita il blocco popup del browser
- Prova un altro browser

### "Facebook dice 'App non disponibile'"
- L'app potrebbe essere in manutenzione
- Riprova tra qualche minuto

### "Non trova i miei post"
- Assicurati che i post contengano immagini
- Il primo controllo avviene dopo 15 minuti dalla connessione
- Puoi forzare un controllo immediato dalla dashboard

### "Vuole troppi permessi"
- Chiediamo solo i permessi strettamente necessari
- Se vedi permessi extra, potrebbe essere un problema tecnico - contattaci

---

## Sicurezza

- I token di accesso sono **criptati** nel nostro database
- **Non possiamo** postare a tuo nome
- **Non condividiamo** i tuoi dati con terzi
- Puoi **revocare** l'accesso in qualsiasi momento

---

*Altre domande? Vedi [FAQ](./FAQ.md)*
