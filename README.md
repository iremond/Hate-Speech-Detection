# Hate-Speech-Detection
Nei notebook presenti, vengono creati e valutati diversi modelli di machine learning per svolgere un task di hate speech detection (HaSpeeDe EVALITA 2018). Nello specifico, ho considerato:
- tre diversi SVC, addestrati su varie rappresentazioni testuali:
  - testo visto come feature di profiling linguistico (estratte tramite Profiling-UD);
  - testo rappresentato da n-grammi di parole;
  - testo rappreesntato da embeddings di parole;
- un Transformer specifico sull'italiano e basato su Bert base.

Le ricerche condotte e i risultati ottenuti sono riassunti nel file pdf.
