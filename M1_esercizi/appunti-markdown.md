# **Appunti Markdown**
**[Markdown](https://it.wikipedia.org/wiki/Markdown)** e' un *linguaggio di marcatura leggero* creato nel 2004 per aggiungere convenzioni di testo per i documenti digitali. <br>
Questi tipi di file si possono trovare ovunque:
- nei file di descrizione della repository (come **README.md**)
- nella documentazione tecnica
- segnalazioni di problemi su GitHub
- nelle applicazioni per appunti

## **Sintassi**
- #### *Titoli*
    Si scrive con uno o piu' **hashtag** (#) all'inizio della riga. Possono andare da 1 hashtag a 6.
- #### *Enfasi*
    Si scrive con *uno* o **due** asterischi. <br>
    *Corsivo* si scrive con un asterisco all'inizio e alla fine.<br>
    **Grassetto** si scrive con due asterischi all'inizio e alla fine. <br>
    Si possono anche fondere i due tipi, mettendo ***3 asterischi***.
- #### *Elenchi* 
    Si scrive facendo un numero o un trattino all'inzio della riga.
1. Questo e' un elenco numerato.
    1. Questo e' un sottoelenco numerato.
- Questo e' un elenco puntato.
    - Questo e' un sotto elenco puntato.

### **Collegamenti**
Un collegamento puo' essere con un'**immaggine** o con un **link** a una pagina web. <br>
Per i link, si mette prima il testo tra parentesi quadrate *[]*, e poi il collegamento con parentesi tonde *()*. <br>
Invece per le immaggini sono la stessa cosa, ma si deve mettere un punto esclamativo all'inizio *!*.

### **Codice in linea/blocchi di codice**
Come il titolo dice. Si mette all'interno di virgolette inverse, esempio: ` git commit -m "MESSAGGIO" `. <br>
Un blocco di codice invece si fa con **3** virgolette inverse all'inizio e alla fine. All'inizio si puo' anche specificare il linguaggio.
``` bash
git add .
git commit -m "Aggiunto il file di descrizione del progetto"
git push
```
### **Citazioni**
Si usa con un `>` all'inzio. Si usa per riportare un errore o parole di un'altro documento.
> Il comando ha risposto: nothing to commit, working tree clean

### **Tabelle**
Si scrive separando le celle con le barre verticali. La seconda riga si deve per forza usa i trattini per dire al programma che si deve fare una tabella.
| Esempio | Esempio 2 | Esempio 3 |
|---|---|---|
| 1 | ... | ... |
| 2 | ... | ... |

### **Caselle**
Si scrive usando un trattino al inizio, e poi facendo `[ ]` per una casella vuota o `[x]` per una fatta.
- [x] Esercizio 1
- [ ] Esercizio 2

---