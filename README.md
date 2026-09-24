# 🃏 Le carte Bit | Laboratorio Interattivo sulla Codifica Binaria

![Scope](https://img.shields.io/badge/Uso-Didattico-indigo)
![License](https://img.shields.io/badge/Licenza-MIT-green)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20TailwindCSS%20%7C%20JS-blue)

**Le carte Bit** è un'applicazione web interattiva e gamificata concepita per la scuola secondaria[cite: 3]. Permette agli studenti di familiarizzare con la **notazione posizionale in base 2** e con la conversione tra il **sistema numerico decimale** e il **sistema binario** a 8 bit (un byte)[cite: 3].

L'applicazione si ispira alla celebre attività unplugged delle carte del *CS Unplugged*, in cui le carte bianche rappresentano il bit `1` (ON) e le carte nere rappresentano il bit `0` (OFF)[cite: 3].

---

## 🎯 Obiettivi Didattici

- **Padroneggiare la notazione posizionale**: Comprendere il peso di ciascun bit associato alle potenze di 2 ($2^0$ fino a $2^7$, da 1 a 128)[cite: 3].
- **Calcolo visivo e mentale**: Associare la presenza/assenza della carta al calcolo della somma dei pesi decimali[cite: 3].
- **Comprendere l'Algoritmo Greedy**: Sperimentare il metodo di sottrazione progressiva per convertire un numero decimale nella sua rappresentazione binaria[cite: 3].
- **Gamification e feedback**: Incentivare l'apprendimento con un sistema di punteggio, serie di successi (*streak*) e feedback sonori sintetizzati in tempo reale tramite Web Audio API[cite: 3].

---

## 🕹️ Modalità di Gioco e Sfide

### 👁️ Sfida 1: Decodifica Flash (Binario ➔ Decimale)
- L'app genera una sequenza casuale di 8 carte bit[cite: 3].
- Lo studente deve calcolare la somma dei valori delle carte attive (bianche) e inserire il numero decimale corrispondente[cite: 3].

### 🪄 Sfida 2: Disegna il Codice (Decimale ➔ Binario)
- Viene fornito un numero decimale target compreso tra 1 e 255[cite: 3].
- Lo studente deve fare clic sulle carte per attivarle (`1`) o disattivarle (`0`) fino a raggiungere il valore richiesto[cite: 3].
- In caso di errore o per approfondire, l'app mostra la spiegazione passo-passo basata sull'**Algoritmo Greedy**[cite: 3].

### 📚 Guida Rapida Integrata
In fondo alla pagina è sempre presente una tabella riassuntiva dei pesi delle potenze di 2 per una consultazione immediata durante lo svolgimento degli esercizi[cite: 3].

---

## 💻 Come Utilizzare l'App

L'applicazione è contenuta in un **unico file HTML** autonomo, senza bisogno di librerie esterne da installare o server di backend[cite: 3].

### Esecuzione Locale
Scarica il file `index.html` ed aprilo con un qualsiasi browser web (Chrome, Firefox, Edge, Safari)[cite: 3].

### Pubblicazione su GitHub Pages
Per condividere l'app con la classe tramite un semplice link:
1. Crea un repository GitHub e carica il file rinominandolo in `index.html`[cite: 3].
2. Vai su **Settings** > **Pages**[cite: 3].
3. Imposta la sorgente su `main` branch e salva[cite: 3].
4. Il link per accedere al laboratorio sarà generato in pochi secondi[cite: 3].

---

## 📜 Licenza

Rilasciato sotto licenza **MIT**[cite: 2]. Libera fruizione, modifica e condivisione per scopi didattici e formativi[cite: 2].
