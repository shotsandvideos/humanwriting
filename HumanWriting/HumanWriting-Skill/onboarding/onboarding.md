# HumanWriting — Onboarding

---

## SCOPO

Questo file gestisce la prima calibrazione di HumanWriting sulla voce dello scrittore. A differenza di EveryDay-Writer, HumanWriting ha un voice profile pre-compilato. L'onboarding serve a confermarlo, aggiustarlo, e renderlo preciso.

---

## FLUSSO

### Scenario A: Voice profile pre-compilato (default)

Il file `core/voice-profile.md` contiene già un profilo vocale costruito dalle istruzioni dell'utente. In questo caso:

**Step 1:** Leggi `core/voice-profile.md` integralmente.

**Step 2:** Presenta il profilo allo scrittore in modo diretto:

> "Ho un profilo vocale pre-compilato per HumanWriting. Ecco come ti ho letto:
>
> [Riassumi i 5 aggettivi vocali con le loro spiegazioni]
>
> [Riassumi i 3 assi tonali]
>
> Ci siamo? Cosa aggiusti, cosa è sbagliato, cosa manca?"

**Step 3:** Aspetta la risposta. Aggiorna il profilo sulla base del feedback. Se lo scrittore conferma tutto senza modifiche, premi una volta: "Sicuro che tutti e cinque gli aggettivi ti rappresentino? Qualcuno è un po' troppo vicino a come descriveresti un altro?"

**Step 4:** Se lo scrittore ha campioni di scrittura disponibili, chiedili:

> "Se hai 2-3 pezzi tuoi che ti rappresentano (newsletter, saggi, post), incollali o indicami i file. Mi aiutano a calibrare meglio. Se non ne hai adesso, si procede con il profilo attuale e si ricalibrra dopo la prima sessione."

**Step 5:** Se i campioni arrivano, leggili e affina il profilo. Cerca specificamente:
- Il ritmo delle frasi corrisponde al profilo? (lunghezza, variazione)
- L'ironia è davvero "velata" o è più marcata nei testi reali?
- I registri si mescolano come descritto o c'è un dominante?
- Le chiusure funzionano come descritto nel profilo?

**Step 6:** Aggiorna `core/voice-profile.md` con le correzioni. Imposta `Completato: Sì`.

> "Profilo aggiornato. Ogni sub-skill ora lo usa.
>
> Se in qualsiasi momento senti che HumanWriting non suona come te, dimmelo e ricalibrro.
>
> Cosa scriviamo?"

### Scenario B: Reset completo

Se lo scrittore chiede un reset del profilo, segui il processo completo di EveryDay-Writer:

1. Chiedi 2-3 campioni di scrittura
2. Analizzali (ritmo, registro, temperatura emotiva, specificità, aperture, chiusure)
3. Chiedi piattaforme e obiettivi
4. Chiedi un freewrite di 200 parole su qualcosa che gli piace
5. Proponi 5 aggettivi vocali e chiedi conferma
6. Posiziona i 3 assi tonali e chiedi conferma
7. Scrivi il profilo in `core/voice-profile.md`

---

## TONO DELL'ONBOARDING

Diretto ed essenziale, escludendo toni burocratici o formali. Comunica allo scrittore lo scopo dell'azione in corso, procedendo direttamente senza spiegazioni ridondanti o formule di cortesia standard.

Lo scrittore ha scelto un sistema costruito sullo standard HumanWriting. Abbina quell'energia dal primo scambio.

---

## COSA NON FARE DURANTE L'ONBOARDING

- Non complimentare i campioni ("bella scrittura!"). Leggili e lavora.
- Non fare più di due domande in un singolo messaggio.
- Non proporre aggettivi vocali che sono solo lodi generiche (appassionato, autentico, coinvolgente).
- Non correre a scrivere il profilo prima che gli aggettivi vocali siano confermati.
- Non saltare la scrittura del profilo su file prima di invocare la prima sub-skill.
