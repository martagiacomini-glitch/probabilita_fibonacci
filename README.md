# Percorso Didattico: Dalle Illusioni del Gioco d'Azzardo alla Probabilità Soggettiva di De Finetti

Un modulo didattico interattivo e innovativo per il secondo biennio e quinto anno del **Liceo Scientifico**, progettato per guidare gli studenti dalla decostruzione psicologica del gioco d'azzardo alla comprensione profonda della **definizione soggettivista di Bruno de Finetti**, fino all'inferenza bayesiana.

---

## 🎯 Panoramica del Progetto

Spesso l'insegnamento della probabilità a scuola si riduce a un'applicazione sterile del calcolo combinatorio (casi favorevoli su casi possibili). Tuttavia:
1. **L'approccio classico** cade nel circolo vizioso: definisce la probabilità assumendo che i casi siano *"equiprobabili"*, usando cioè il concetto che vorrebbe definire.
2. **L'approccio frequentista** fallisce di fronte agli eventi non ripetibili in condizioni identiche (es. *"Qual è la probabilità che domani nevichi a Roma?"*, *"Qual è la probabilità che l'imputato sia colpevole?"*, *"Chi vincerà la prossima gara?"*).
3. **L'approccio soggettivista (Bruno de Finetti, F. P. Ramsey)** affronta la realtà: *"La probabilità non esiste"* come proprietà intrinseca della materia, ma esprime il **grado di fiducia** che un individuo razionale assegna all'accadimento di un evento, misurabile mediante le condizioni sotto cui è disposto a scommettere. Gli assiomi matematici (Kolmogorov) non sono dogmi metafisici, ma **condizioni di coerenza** per non subire perdite certe (**Dutch Book Theorem**).

---

## 🚀 Come Utilizzare l'Applicazione Web

L'applicazione didattica è contenuta nel file [`index.html`](file:///C:/Users/Marta/.gemini/antigravity/scratch/percorso-probabilita/index.html).

1. **Avvio immediato**: È una *Single Page Application* moderna, responsive e interattiva.
2. **Nessuna installazione richiesta**: Basta fare doppio clic su `index.html` o aprirlo con qualsiasi browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).
3. **Utilizzo in classe**: Perfetto sia per la **LIM / Monitor Interattivo** durante la lezione frontale dialogata, sia nei **laboratori di informatica** o in modalità **BYOD** (smartphone/tablet degli studenti).

---

## 📂 Struttura del Percorso e delle Simulazioni

La pagina web è organizzata in 4 moduli progressivi:

### 🎰 Modulo 1: La Psicologia dell'Azzardo & Le Illusioni Cognitive
- **Simulatore Roulette & Gambler's Fallacy**: Sperimenta serie di eventi e smaschera l'illusione dei "numeri in ritardo".
- **Simulatore del Cavaliere de Méré (1654)**: Confronta 4 lanci di 1 dado (favorevole, 51.77%) con 24 lanci di 2 dadi (sfavorevole, 49.14%), ripercorrendo la nascita del calcolo delle probabilità tra Pascal e Fermat.
- **La Tassa sull'Ignoranza (Valore Atteso)**: Dimostrazione numerica del perché il banco vince sempre nel lungo periodo (Gratta e Vinci, Roulette, Lotto).

### ⚖️ Modulo 2: Le Definizioni a Confronto
- Tavola comparativa interattiva tra le 4 definizioni:
  - **Classica** (Laplace)
  - **Frequentista** (von Mises)
  - **Assiomatica** (Kolmogorov)
  - **Soggettivista** (de Finetti, Ramsey)
- Casi limite e aporie epistemologiche per stimolare il dibattito filosofico-scientifico.

### 🧠 Modulo 3: Il Cuore del Percorso — La Probabilità Soggettiva di Bruno de Finetti
- **"La Probabilità non esiste"**: Il significato profondo della celebre provocazione di de Finetti.
- **La Definizione Operativa di De Finetti**: La probabilità come quota di scommessa reversibile.
- **Il Dutch Book Scanner (Verificatore di Coerenza)**: Lo studente imposta le proprie quote su un insieme di eventi. Se non rispetta le leggi della probabilità (somma quote $\neq 1$), l'algoritmo crea un portafoglio di scommesse che fa perdere lo studente **in ogni caso possibile**!
- **Test di Calibrazione Personale & Brier Score**: Gli studenti stimano la propria fiducia su 5 previsioni e misurano il proprio grado di sovrasicurezza (overconfidence).

### 🔍 Modulo 4: Aggiornare le Convinzioni — L'Approccio Bayesiano
- Come la mente razionale integra nuove prove empiriche per aggiornare il grado di fiducia iniziale (*Prior* $\rightarrow$ *Verosimiglianza* $\rightarrow$ *Posterior*).
- **Simulatore "Il Dado Sospetto"**: Un sacchetto contiene 4 dadi equi e 1 truccato (esce 6 il 50% delle volte). Estraendo un dado e lanciandolo ripetutamente, gli studenti vedono in tempo reale la curva di probabilità soggettiva aggiornarsi lancio dopo lancio.

---

## 📚 Materiali Didattici Inclusi
- Consultare il file [`GUIDA_DIDATTICA.md`](file:///C:/Users/Marta/.gemini/antigravity/scratch/percorso-probabilita/GUIDA_DIDATTICA.md) per:
  - Piano di lezione dettagliato (4 sessioni da 60-90 minuti).
  - Schede operative per gli studenti con domande guida ed esercizi di calcolo.
  - Griglia di valutazione per competenze.
