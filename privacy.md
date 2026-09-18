---
layout: default
title: Privacy
---

# Informativa privacy — Kid Job

**Ultimo aggiornamento**: 18 settembre 2026

> Da pubblicare a un indirizzo pubblico e stabile: lo chiedono Google Play, App Store e Apple
> dentro la schermata di acquisto. I campi `rothsthegame@gmail.com` sono gli unici che mancano.

## Chi tratta i dati

**Titolare del trattamento**: Robert Crivat Florian (persona fisica)
**Email di contatto**: rothsthegame@gmail.com

## In breve

Kid Job è un'app che le famiglie usano per trasformare i lavoretti di casa in «coin» e i coin in
paghetta. **L'account lo crea sempre un adulto**, che dichiara di essere il genitore o chi ne fa
le veci. Il bambino **non ha email, non ha password e non riceve pubblicità**.

## Quali dati raccogliamo

### Adulto che crea o entra in una famiglia
- **Email e password** (la password è conservata cifrata dal nostro fornitore di autenticazione, noi non la vediamo mai).
- **Nome visualizzato e avatar** scelto da una galleria interna: nessuna foto.
- **PIN di 4 cifre** dell'area genitore, conservato solo come impronta cifrata (bcrypt), mai in chiaro.
- **Token di notifica push**, se accetti i promemoria.
- **Ruolo** nella famiglia (titolare o aiutante) e fuso orario della famiglia.

### Bambino
- **Nome o soprannome** e **avatar** scelto dalla galleria: li inserisce l'adulto.
- **Nessuna email, nessuna password, nessuna foto, nessun contatto, nessuna geolocalizzazione.**
- Se usa un suo telefono, il dispositivo viene collegato con un **identificativo anonimo** creato
  dall'app: non è un account e non contiene dati personali.

### Attività dentro l'app
Missioni create e completate, coin guadagnati o tolti, movimenti del registro, richieste di
conversione, obiettivi di risparmio, orari dei promemoria. Servono a far funzionare il servizio e
restano dentro la famiglia.

### Acquisti
Se attivi Kid Job Pro, il nostro fornitore di abbonamenti registra **l'identificativo
dell'acquisto, il piano scelto, le date di rinnovo e di scadenza**. I dati della carta li tratta
solo lo store (Apple o Google): **noi non li vediamo mai**.

### Pubblicità — solo nell'area del genitore
Nella parte dell'app usata dagli adulti mostriamo annunci. Il fornitore pubblicitario può
raccogliere **l'identificativo pubblicitario del dispositivo** e dati tecnici. Prima di caricare
qualunque annuncio ti chiediamo il consenso con il modulo standard europeo.

**Nella vista del bambino non c'è pubblicità**: il codice non carica nemmeno la libreria degli
annunci, e questa scelta è scritta nel progetto (`docs/decisioni/002-pubblicita.md`). Gli annunci
sono limitati ai contenuti classificati per tutti.

## Perché li trattiamo, e con quale base giuridica

| Perché | Base giuridica (GDPR) |
|---|---|
| Far funzionare il servizio: account, famiglie, missioni, coin | Esecuzione del contratto (art. 6.1.b) |
| Promemoria push | Consenso, revocabile dalle impostazioni del telefono (art. 6.1.a) |
| Abbonamento Pro | Esecuzione del contratto (art. 6.1.b) |
| Pubblicità nell'area genitore | Consenso raccolto prima del primo annuncio (art. 6.1.a) |
| Sicurezza: PIN, blocco dopo tentativi errati, codici di collegamento a scadenza | Legittimo interesse (art. 6.1.f) |

## Bambini

Il servizio è pensato per essere **usato dai bambini sotto il controllo di un adulto**. L'account
lo apre l'adulto, che accettando dichiara di essere il genitore o il tutore e di prestare il
consenso anche per i minori che aggiunge (art. 8 GDPR). L'adulto può in ogni momento vedere,
correggere o eliminare i dati del bambino dalla scheda del profilo.

Non profiliamo i bambini, non mostriamo loro pubblicità e non consentiamo acquisti dalla loro
vista dell'app.

## Chi altro tratta i dati per noi

| Fornitore | Cosa fa | Dove |
|---|---|---|
| **Supabase** | Banca dati, autenticazione, notifiche | Unione Europea (Irlanda) |
| **Google AdMob** | Annunci nell'area genitore | Stati Uniti, con clausole contrattuali standard |
| **RevenueCat** | Gestione degli abbonamenti | Stati Uniti, con clausole contrattuali standard |
| **Expo** | Recapito delle notifiche push | Stati Uniti, con clausole contrattuali standard |
| **Apple, Google** | Pagamento e distribuzione dell'app | Secondo le rispettive informative |

Non vendiamo i dati a nessuno e non li usiamo per profilare le famiglie.

## Per quanto tempo li teniamo

- Finché l'account esiste.
- **Cancellazione**: dall'app, «Il mio account» → «Elimina account». Se sei il titolare vengono
  cancellati la famiglia, i bambini, le missioni e la storia; se sei un aiutante, la tua presenza.
  La cancellazione è immediata e non recuperabile.
- I codici per collegare un telefono durano **10 minuti** e valgono una volta sola.

## I tuoi diritti

Puoi chiedere accesso, correzione, cancellazione, limitazione, portabilità e opposizione
scrivendo all'indirizzo qui sopra. Rispondiamo entro 30 giorni. Puoi revocare il consenso agli
annunci o alle notifiche in qualsiasi momento senza perdere l'uso dell'app.

Se ritieni che il trattamento violi il GDPR puoi rivolgerti al **Garante per la protezione dei
dati personali** (www.garanteprivacy.it).

## Modifiche

Se cambiamo questa informativa aggiorniamo la data in cima e, se il cambiamento è rilevante, lo
segnaliamo dentro l'app.
