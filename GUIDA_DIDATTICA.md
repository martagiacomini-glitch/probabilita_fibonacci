# GUIDA DIDATTICA PER IL DOCENTE
## Dalle Illusioni dell'Azzardo alla Probabilità Soggettiva di Bruno de Finetti
### Modulo Didattico per il Liceo Scientifico (Classi IV e V)

---

## 1. Quadro Pedagogico e Obiettivi di Apprendimento

### 1.1 Il problema dell'insegnamento tradizionale della probabilità
Tradizionalmente, nei licei la probabilità viene introdotta come un'appendice del calcolo combinatorio. Gli studenti imparano a calcolare $P(E) = \frac{\text{casi favorevoli}}{\text{casi possibili}}$ contando anagrammi o estraendo palline colorate da urne ipotetiche.
Questo approccio presenta tre gravi limiti formativi:
1. **Circolo vizioso epistemologico**: La definizione classica di Laplace assume che tutti i casi possibili siano *"ugualmente probabili"*, definendo il concetto attraverso il concetto stesso.
2. **Scissione dalla realtà**: Nel mondo reale (dalle previsioni meteorologiche alle diagnosi mediche, dai processi giudiziari alle decisioni finanziarie) quasi nessun evento ammette simmetrie a priori o ripetibilità all'infinito.
3. **Vulnerabilità alle fallacie del gioco d'azzardo**: Senza un'educazione critica alla speranza matematica e all'indipendenza stocastica, gli studenti rimangono prede delle illusioni cognitive sfruttate dall'industria dell'azzardo (ludopatia).

### 1.2 La rivoluzione soggettivista di Bruno de Finetti
L'inclusione della definizione soggettivista (e dell'inferenza bayesiana) permette di:
- Mostrare che la probabilità non è un fluido fisico misterioso insito negli oggetti, ma **lo strumento matematico con cui un agente razionale quantifica il proprio stato di ignoranza e fiducia** in condizioni di incertezza.
- Fondare gli assiomi di Kolmogorov su una base logico-economica inoppugnabile: **la coerenza delle scommesse (Dutch Book Theorem)**.
- Fornire una competenza di cittadinanza attiva (educazione civica e contrasto al gioco d'azzardo patologico).

### 1.3 Riferimenti alle Indicazioni Nazionali (MIUR - Dati e Previsioni)
- Valutare la probabilità di eventi mediante la definizione classica, frequentista e soggettivista.
- Comprendere il concetto di probabilità condizionata e indipendenza stocastica.
- Applicare il Teorema di Bayes a problemi reali e interpretarlo in chiave inferenziale.
- Analizzare il valore atteso di un gioco e riconoscere l'iniquità dei giochi d'azzardo legali.

---

## 2. Cronoprogramma Didattico (4 Sessioni da 60-90 minuti)

```
Sessione 1 ──► Sessione 2 ──► Sessione 3 ──► Sessione 4
Azzardo &       I 4 Volti      De Finetti &    L'Aggiornamento
Fallacie        della P        il Dutch Book   Bayesiano
```

### 🎲 Sessione 1: L'Inizio Euristicamente Efficace — Giochi d'Azzardo & Fallacie
- **Fase 1 (15 min) - Stimolo**: Sondaggio d'ingresso senza formule: *"Se un numero al Lotto non esce da 120 estrazioni, è più conveniente giocarlo rispetto a uno uscito la settimana scorsa?"*. Discussione delle risposte spontanee.
- **Fase 2 (30 min) - Laboratorio con l'App**: 
  - Apertura del modulo 1 in `index.html`.
  - Simulazione della Roulette: ricerca della sequenza di 5 rossi consecutivi.
  - Smascheramento della *Gambler's Fallacy* e formalizzazione dell'indipendenza stocastica $P(A \cap B) = P(A)P(B)$.
- **Fase 3 (30 min) - Storia & Matematica**: 
  - Il paradosso del Cavaliere de Méré (1654) e la corrispondenza Pascal-Fermat.
  - Perché $1 - (5/6)^4 > 50\%$ mentre $1 - (35/36)^{24} < 50\%$.
  - Simulatore Monte Carlo della "Rovina del Giocatore" e calcolo della speranza matematica $E[X] < 0$.

### ⚖️ Sessione 2: Il Confronto Epistemologico (I 4 Volti della Probabilità)
- **Fase 1 (20 min) - Crisi dei Modelli**: Presentazione di tre scenari apparentemente irrisolvibili:
  1. *Lancio di una puntina da disegno*: quale faccia tocca terra? (La classica fallisce: non c'è simmetria).
  2. *L'imputato in tribunale è innocente*: (La frequentista fallisce: il delitto è un fatto unico irripetibile).
  3. *Un computer quantistico funzionerà entro il 2030?*
- **Fase 2 (30 min) - Studio guidato delle definizioni**:
  - Classica (Laplace) $\rightarrow$ Circolo vizioso dell'equiprobabilità.
  - Frequentista (von Mises) $\rightarrow$ Il problema del limite all'infinito e degli eventi irripetibili.
  - Assiomatica (Kolmogorov) $\rightarrow$ Rigore formale, ma assenza di interpretazione semantica.
  - Soggettivista (de Finetti, Ramsey) $\rightarrow$ Il grado di fiducia.
- **Fase 3 (20 min) - Palestra Interattiva**: Risoluzione guidata del quiz epistemologico nell'app.

### 🧠 Sessione 3: Il Cuore del Percorso — De Finetti, le Scommesse e il Dutch Book
- **Fase 1 (15 min) - La Provocazione**: Analisi del celebre saggio di Bruno de Finetti *"La probabilità non esiste"*. Dibattito filosofico: il caso è ontologico (nelle cose) o epistemico (nella nostra mente)?
- **Fase 2 (25 min) - Definizione Operativa**: 
  - Il prezzo equo di una lotteria che paga 1€ in caso di successo.
  - La clausola essenziale: la **reversibilità** della scommessa (chi fissa la quota deve accettare di fare sia da banco sia da scommettitore).
- **Fase 3 (35 min) - Il Dutch Book Simulator**:
  - Gli studenti aprono il simulatore nell'app e impostano quote a loro piacimento.
  - L'algoritmo rileva automaticamente le incoerenze e genera la strategia vincente dell'avversario.
  - Dimostrazione alla lavagna del perché $\sum p_i = 1$ è la condizione per non subire perdite certe.
  - Test di calibrazione con il *Brier Score*.

### 🔍 Sessione 4: Dalla Soggettività alla Verità — L'Inferenza Bayesiana
- **Fase 1 (15 min) - Il superamento del relativismo**: Se la probabilità è soggettiva, come fa la scienza a progredire e a convergere verso la verità? Risposta: attraverso l'evidenza empirica!
- **Fase 2 (30 min) - Laboratorio "Il Dado Sospetto"**:
  - Esperimento col sacchetto (4 dadi equi, 1 truccato).
  - Tracciamento della curva di probabilità a posteriori $P(\text{Truccato} \mid \text{Dati})$.
  - Visualizzazione dei "salti" bayesiani ad ogni uscita del numero 6.
- **Fase 3 (20 min) - Esercizio di sintesi e restituzione**: Risoluzione analitica con la formula di Bayes e chiusura del percorso.

---

## 3. Schede di Lavoro per gli Studenti (Materiale Fotocopiabile)

### 📄 SCHEDA 1: La Roulette e il Cavaliere de Méré
**Nome Studente:** _______________________ **Data:** _____________

#### Esercizio 1.1 (L'indipendenza)
Nel gioco della roulette ci sono 37 numeri (da 0 a 36). Lo zero è verde, 18 numeri sono rossi e 18 sono neri.
1. Calcola la probabilità classica $P(R)$ che esca un numero rosso in un singolo lancio:
   $$P(R) = \frac{\dots\dots}{\dots\dots} \approx \dots\dots\%$$
2. Supponi che siano usciti 5 numeri Rossi consecutivi. Dimostra analiticamente, usando la definizione di probabilità condizionata $P(A \mid B) = \frac{P(A \cap B)}{P(B)}$, che:
   $$P(R_6 \mid R_1 \cap R_2 \cap R_3 \cap R_4 \cap R_5) = P(R)$$

#### Esercizio 1.2 (Il Paradosso di De Méré)
Antoine Gombaud scommetteva alla pari (vince 1€ se vince, perde 1€ se perde) su due giochi:
- **Gioco 1**: Ottenere almeno un 6 in 4 lanci di un dado singolo.
- **Gioco 2**: Ottenere almeno un doppio 6 in 24 lanci di due dadi.

*Calcolo per il Gioco 1:*
- Probabilità di NON ottenere 6 in un lancio: $q = \dots\dots$
- Probabilità di NON ottenere MAI 6 in 4 lanci indipendenti: $q^4 = (\dots\dots)^4 = \dots\dots$
- Probabilità di ottenere ALMENO un 6 (evento complementare):
  $$P(\text{Vittoria 1}) = 1 - q^4 = 1 - \left(\frac{5}{6}\right)^4 = 1 - \frac{625}{1296} \approx \dots\dots\%$$
- Conviene giocare a lungo termine? **[ SÌ / NO ]**

*Calcolo per il Gioco 2:*
- Casi possibili con due dadi: $6 \times 6 = 36$. Probabilità di fare doppio 6: $1/36$.
- Probabilità di NON fare doppio 6 in un lancio: $35/36$.
- Probabilità di NON fare MAI doppio 6 in 24 lanci: $(35/36)^{24} \approx \dots\dots$
- Probabilità di fare ALMENO un doppio 6:
  $$P(\text{Vittoria 2}) = 1 - \left(\frac{35}{36}\right)^{24} \approx \dots\dots\%$$
- Conviene giocare a lungo termine? **[ SÌ / NO ]**
- Spiega perché il ragionamento intuitivo di De Méré ($4/6 = 24/36 = 2/3$) era fallace.

---

### 📄 SCHEDA 2: Il Teorema del Dutch Book e Bruno de Finetti

#### Il Principio di Reversibilità
Supponi che uno studente dichiari le seguenti probabilità per una partita di calcio a 3 esiti mutualmente esclusivi (Vittoria Squadra 1, Pareggio X, Vittoria Squadra 2):
$$p_1 = 0.50 \quad p_X = 0.35 \quad p_2 = 0.40$$

1. Calcola la somma delle probabilità soggettive:
   $$\sum p_i = p_1 + p_X + p_2 = \dots\dots$$
2. Poiché la quota è reversibile, uno scommettitore furbo **vende** allo studente 1 biglietto per ciascun esito:
   - Quanto denaro deve sborsare lo studente all'inizio per acquistare i 3 biglietti?
     $$\text{Costo iniziale} = \dots\dots\dots €$$
   - A fine partita, uno solo dei tre esiti si verificherà con certezza. Quanti euro incasserà lo studente dal biglietto vincente?
     $$\text{Incasso finale} = \dots\dots\dots €$$
   - Calcola il bilancio netto dello studente:
     $$\text{Bilancio} = \text{Incasso} - \text{Costo} = \dots\dots\dots €$$
3. Conclusione: Spiega perché questa perdita prescinde totalmente da quale squadra vincerà o dalla fortuna.

---

## 4. Dimostrazione Matematica del Teorema del Dutch Book

Questa dimostrazione può essere proposta agli studenti dell'ultimo anno come elegante esempio di connessione tra algebra lineare elementare, logica e teoria delle decisioni.

### Teorema (de Finetti, 1931 - Dutch Book Theorem)
Sia $\Omega = \{E_1, E_2, \dots, E_n\}$ una partizione dello spazio degli eventi (eventi a due a due incompatibili ed esaustivi, di cui esattamente uno si verificherà).
Sia $p = (p_1, p_2, \dots, p_n)$ il vettore delle quote/probabilità soggettive assegnate dal soggetto, con $p_i \ge 0$.
**Tesi:** Non esiste alcun vettore di scommesse $S = (S_1, S_2, \dots, S_n)$ in grado di provocare una perdita netta certa per il soggetto se e solo se:
$$\sum_{i=1}^n p_i = 1$$

### Dimostrazione:
Sia $S_i$ la posta associata all'evento $E_i$ (se $S_i > 0$ l'avversario acquista la scommessa, se $S_i < 0$ la vende).
Il costo pagato dall'avversario al soggetto al momento della stipula è:
$$C = \sum_{i=1}^n p_i S_i$$
Se si verifica l'evento $E_k$ (con $k \in \{1, \dots, n\}$), il soggetto deve liquidare la vincita $S_k$ all'avversario.
Il guadagno netto dell'avversario nel caso in cui accada $E_k$ è:
$$G_k = S_k - C = S_k - \sum_{i=1}^n p_i S_i$$
Un *Dutch Book* contro il soggetto esiste se l'avversario riesce a trovare un vettore $S$ tale che $G_k > 0$ per tutti i $k = 1, \dots, n$ (vittoria certa dell'avversario, ossia perdita certa del soggetto).

**Caso 1:** Supponiamo che $\sum_{i=1}^n p_i = c \neq 1$.
Scegliamo tutte le poste uguali tra loro: $S_1 = S_2 = \dots = S_n = s$.
Allora il guadagno dell'avversario per qualunque evento vincente $E_k$ diventa:
$$G_k = s - \sum_{i=1}^n p_i s = s \left(1 - \sum_{i=1}^n p_i\right) = s(1 - c)$$
- Se $c > 1$ (somma $> 1$), all'avversario basta scegliere $s < 0$ (vendere le scommesse). Allora $1 - c < 0$, per cui:
  $$G_k = s(1 - c) > 0 \quad \forall k$$
- Se $c < 1$ (somma $< 1$), all'avversario basta scegliere $s > 0$ (comprare le scommesse). Allora $1 - c > 0$, per cui:
  $$G_k = s(1 - c) > 0 \quad \forall k$$

In entrambi i casi, l'avversario ottiene un profitto strettamente positivo certo, condannando il soggetto alla perdita certa.
Ne consegue che l'unica condizione necessaria e sufficiente per evitare il Dutch Book è che $c = 1$, ossia:
$$\sum_{i=1}^n p_i = 1 \quad \blacksquare$$

---

## 5. Griglia di Valutazione delle Competenze

| Dimensione | Livello Base (6) | Livello Intermedio (7-8) | Livello Avanzato (9-10) |
| :--- | :--- | :--- | :--- |
| **Comprensione Concettuale** | Distingue tra approccio classico e frequentista su casi banali. | Spiega i limiti della definizione classica (circolarità) e frequentista (eventi non ripetibili). | Padroneggia l'interpretazione soggettivista di de Finetti ed espone con chiarezza la reversibilità della scommessa. |
| **Abilità di Calcolo e Modellizzazione** | Calcola probabilità composte semplici e complementari. | Risolve problemi con più eventi indipendenti (es. De Méré) e calcola il valore atteso. | Dimostra formalmente il legame tra coerenza di scommessa e assiomi di Kolmogorov (Dutch Book). |
| **Pensiero Critico e Consapevolezza** | Riconosce che il banco vince nei giochi d'azzardo. | Argomenta contro la fallacia dello scommettitore mediante il concetto di indipendenza stocastica. | Analizza l'overconfidence e la calibrazione personale; interpreta l'inferenza bayesiana come evoluzione delle credenze. |
