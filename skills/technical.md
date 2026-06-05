# HumanWriting — Newsletter Tecnica

**Dipendenze (in ordine di lettura):**
1. `core/anti-ai-rules.md` (tutte le sezioni, Sezione 0 per prima)
2. `core/ai_slop_commandments.md`
3. `core/voice-profile.md`
4. `core/dna-stilistico.md`
5. Questo file

---

## A COSA SERVE

Newsletter tecniche, analisi di settore, breakdown di tool, how-to, e trend analysis. I temi: IA, Prompt Engineering, Agentic Intelligence, Creator Economy, Personal Branding, World Building per brand e professionisti.

**Minimo 1000 parole.** La lunghezza varia a seconda del tema: un breakdown di un tool di AI può stare sulle 1200 parole, un'analisi approfondita dell'evoluzione dell'Agentic Intelligence può arrivare a 2500.

La differenza tra una newsletter tecnica HumanWriting e una qualsiasi: questa ha un'anima e la chiarezza de Il Post. La scrittura tecnica conserva la personalità di chi scrive. Il taglio di HumanWriting spiega i concetti complessi come si farebbe con un amico al bar (con l'attenzione al contesto e al "perché" presi da Il Post), escludendo lo stile rigido di un whitepaper.

L'obiettivo di una newsletter tecnica risiede nell'accrescere la competenza concreta del lettore in modo rapido e lineare, evitando di allungare un insight sottile solo per aumentare il conteggio delle parole.

---

## LA STRUTTURA: I QUATTRO ATTI

### 1. Il Problema (Perché ti dovrebbe interessare)

Dichiara il problema specifico, il gap, o la domanda che questo numero affronta.

❌ "L'AI sta cambiando il marketing."
✅ "La maggior parte dei team marketing usa GPT per scrivere post sui social, ma ignora i tre casi d'uso che hanno un ROI 10 volte superiore. E il primo non ha niente a che fare con la scrittura."

Il lettore deve comprendere entro due frasi l'utilità del contenuto per il proprio lavoro, evitando di costringerlo a cercare le informazioni essenziali.

**Il problema si apre comunque con lo stile HumanWriting:** anche qui si può partire con un aneddoto flash, una scena, un dato sorprendente. Il tono non cambia; cambia il rapporto tra narrazione e informazione.

### 2. L'Insight Chiave (Cosa ho trovato)

La cosa più importante che questo numero consegna. Dichiarala presto: entro il primo terzo del testo. I lettori tecnici dispongono di tempo limitato. La chiarezza immediata evita l'abbandono della lettura.

Questa frase rappresenta la tesi centrale del pezzo, ed i paragrafi successivi ne costituiscono il supporto analitico.

**L'insight deve avere almeno un link a una fonte verificabile.** Un dato, uno studio, un report. Evita attribuzioni vaghe come "secondo alcune ricerche", citando fonti precise come "secondo il [report State of AI 2025 di Air Street Capital](URL), il 73% delle startup AI nel B2B pivota entro 18 mesi dal lancio".

### 3. L'Evidenza e i Meccanismi (Come funziona)

Qui si scende nei dettagli. Dati, esempi, logica step-by-step, confronti. Qui vive la profondità.

**Regole per questa sezione:**

**Specificità è prova.** Ogni affermazione deve essere ancorata a un fatto specifico, un numero, un esempio, una fonte. Evita affermazioni generiche come "questo framework è più veloce", fornendo dati specifici come "questo framework riduce il tempo di cold-start da 8 secondi a 340ms su un dataset di 50K record".

**Un concetto alla volta.** Ogni sotto-sezione copre una cosa completamente prima di passare alla prossima. Evita di sovrapporre la descrizione del funzionamento di un sistema con l'argomentazione sulla sua importanza; affronta questi due aspetti in passaggi separati per preservare l'efficacia del testo.

**Nomi e link, non gesti vaghi.** Cita fonti precise come "secondo la ricerca di Ethan Mollick sull'adozione dell'AI nel knowledge work", escludendo formule vaghe come "gli esperti suggeriscono".

**I tre registri anche nel tecnico:**
- Registro alto: il concetto, il framework, la teoria dietro al tool/trend
- Registro medio: l'esempio pratico, il tutorial, il caso d'uso reale
- Registro basso: l'analogia pop, la metafora quotidiana, la battuta

Esempio di integrazione dei tre registri in un passaggio tecnico:
"Il retrieval-augmented generation (RAG) consente al modello linguistico di consultare appunti in tempo reale, evitando di dover ricordare l'intero corpus di addestramento. Tipo quando a scuola facevi la versione di latino con il dizionario aperto (registro basso). In pratica, funziona così: il sistema prende la tua domanda, cerca nei documenti rilevanti, e passa al modello sia la domanda che i pezzi di documento trovati (registro medio). Il risultato, come ha documentato [questo paper di Lewis et al. pubblicato su NeurIPS](URL), è un sistema che allucina meno perché ha vincoli fattuali concreti a cui ancorarsi (registro alto)."

### 4. L'Azione (Cosa fartene)

Cosa dovrebbe fare il lettore concretamente? Fornisci l'azione esatta, il tool, la query o il cambiamento da apportare, evitando suggerimenti vaghi come "considera di provare".

In assenza di un'azione immediata, dichiara le motivazioni ed indica cosa monitorare. Evita di concludere con un'osservazione passiva.

**L'azione è dove l'insegnamento pratico di HumanWriting si manifesta più direttamente.** Qui puoi essere esplicito:
- "Prova a fare X la prossima volta che Y"
- "Apri [questo tool](URL) e testa Z con i tuoi dati"
- "La prossima volta che un cliente ti chiede W, rispondi con V. Ecco perché funziona."

---

## REGOLE DI CHIAREZZA

**Costruzioni attive.** La voce passiva nella scrittura tecnica nasconde il meccanismo. "I dati vengono elaborati" da cosa? Come? "Il modello processa ogni token sequenzialmente contro l'intera context window" è la frase.

**Lead con il risultato, escludendo preamboli metodologici.**
❌ "Per capire perché funziona, dobbiamo prima guardare come X opera sotto le condizioni Y, che è stato descritto per la prima volta da..."
✅ "X supera Y negli scenari a bassa latenza per come gestisce l'allocazione della memoria. Ecco il meccanismo."

**Liste solo per item genuinamente paralleli.** Una lista di sette elementi privi di parallelismo logico si riduce di fatto a un paragrafo frammentato. Se i punti elenco richiedono spiegazioni approfondite, sviluppali in prosa.

**Codice, dati e comandi in blocco separato.** Mai seppellire un comando, una query o una formula nella prosa corrente. Se qualcuno deve usarlo, deve poterlo copiare pulito.

---

## HEADER COME SIGNPOST

Un header come "Perché è importante" è inutile. "Perché i team sottovalutano la dimensione della context window" è un signpost. Se il lettore può scansionare gli header e capire l'intero argomento, la struttura funziona. Se gli header potrebbero appartenere a qualsiasi newsletter sullo stesso tema, riscrivili.

---

## LO STANDARD DELL'INSIGHT

La differenza tra una buona newsletter tecnica e una grande: lo scrittore ha avuto un insight o solo delle informazioni?

**Chiediti prima di scrivere:**
- Cosa significano questi dati per come qualcuno fa il suo lavoro?
- Cosa sbaglierebbe una persona intelligente su questo tema, e perché?
- Qual è l'implicazione non ovvia di questo sviluppo?
- Cosa ci dice questo su dove stanno andando le cose nei prossimi 6-18 mesi?

Se non puoi rispondere ad almeno una, hai un riassunto, non una newsletter.

---

## SEGNALI DI CREDIBILITÀ

I lettori tecnici sono scettici per default.

**Cosa costruisce credibilità:**
- Numeri specifici con fonte nominata e linkata
- Riconoscimento onesto dei limiti ("questo vale solo quando la condizione X è vera")
- La tua esperienza reale o i tuoi risultati di test, dichiarati semplicemente
- Controargomenti riconosciuti e affrontati

**Cosa distrugge credibilità:**
- Attribuzioni vaghe ("gli studi mostrano", "gli esperti concordano")
- Overclaiming ("questo trasformerà completamente il tuo workflow")
- Sbagliare un dettaglio tecnico in qualsiasi punto (se una cosa è sbagliata, il lettore mette in dubbio tutto)
- Fare hedging su tutto fino a non dire nulla

---

## REVIEW POST-GENERAZIONE

Dopo aver prodotto la bozza, fermati. Esegui in ordine:

1. Rileggi `core/anti-ai-rules.md` Sezioni 1-7 con la bozza davanti. Correggi ogni fallimento.
2. Rileggi `core/ai_slop_commandments.md` Sezione 6. Correggi ogni fallimento.
3. Verifica la checklist del DNA stilistico in `core/dna-stilistico.md`.
4. **Passa il testo attraverso `core/humanizer.md`** — step finale obbligatorio.

## CHECKLIST PRE-PUBBLICAZIONE

- [ ] L'insight chiave è dichiarato nel primo terzo?
- [ ] Ogni affermazione ha un fatto specifico, un numero, o una fonte nominata?
- [ ] Ci sono almeno 3 link funzionanti a risorse verificabili?
- [ ] Ogni sezione si ricollega all'insight chiave?
- [ ] Gli header raccontano l'argomento, non solo il tema?
- [ ] C'è un'azione specifica che il lettore può compiere?
- [ ] Ci sono tutti e tre i registri (alto, medio, basso)?
- [ ] C'è almeno un momento ironico?
- [ ] C'è almeno un aneddoto o un esempio concreto?
- [ ] Il testo è completamente privo di parallelismi negativi (zero occorrenze)?
- [ ] La voce passiva è eliminata dalle descrizioni tecniche?
- [ ] Le liste sono usate solo per item genuinamente paralleli?
- [ ] Il testo è passato attraverso l'Humanizer?
- [ ] Un esperto occupato si fermerebbe a leggerlo o lo salterebbe?
- [ ] Sezioni 1-7 di `core/anti-ai-rules.md` superate?
- [ ] Sezione 6 di `core/ai_slop_commandments.md` superata?
- [ ] Checklist DNA stilistico superata?
