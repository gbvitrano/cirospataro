---
hide:
  - toc
---


# `Read the Docs` vs `Material for MKDocs`

Template classici per progetti di documentazione online sono:

- [**Read the Docs**](https://docs.readthedocs.io/en/stable/index.html) 
- [**Material for MKDocs**](https://squidfunk.github.io/mkdocs-material) 

!!! note "Alcune differenze tra `"Material for MKDocs"` e `"Read the Docs"` per progetti di documentazione"

    === "Material for MKDocs"

        **Material for MKDocs** <img src="https://user-images.githubusercontent.com/3757525/139392575-e2462137-1d61-4110-8b76-8d3017f9d0de.JPG" width="35">

        `Material for MKDocs` si presenta con un architetuttura semplice per la costruzione del progetto di documentazione :slight_smile:
        
        Si basa sul linguaggio `MD` markdown per la redazione dei contenuti nelle pagine, un linguaggio semplice per sintassi :slight_smile: 
        
        Presenta una maggiore facilità nella configurazione dei parametri del codice sorgente su Github :slight_smile:
        
        Compila le pagine web direttamente su **Github** (gh-pages), quindi la parte di codice e quella di compilazione sono ospitate sullo stesso ambiente web :slight_smile:
        
        La guida [https://squidfunk.github.io/mkdocs-material/](https://squidfunk.github.io/mkdocs-material/) è realizzata in maniera perfetta, molto completa e dettagliata, copre ogni minimo aspetto per l'installazione e la personalizzazione grafica del progetto di documentazione, con esempi di codice da usare nella configurazione dei file :slight_smile:
        
        `Material for MKDocs` dal punto di vista grafico si presenta in una forma più elegante rispetto a `Read the Docs`. Su `Material for MKDocs` è possibile avere una sidebar verticale laterale a destra (oltre a quella generale di sinistra) che indica il menù della pagina che stiamo visualizzando (TOC) e ciò risulta molto comodo per comprendere l'andamento della lettura nel contesto dei paragrafi e sottoparagrafi della pagina visualizzata :slight_smile:
         

    === "Read the Docs"

        **Read the Docs** <img src="https://user-images.githubusercontent.com/3757525/139450435-d49f2bc7-d785-4cc9-b182-e16730b7d6a8.png" width="35">

        `Read the Docs` si basa sul linguaggio `RST` (*restructured text*), dalla sintassi più complessa rispetto a `md` :neutral_face: 
        
        Anche il linguaggio `MD` può essere utilizzato fornendo idonee istruzioni sul file di configurazione `conf.py` :slight_smile: 
        
        Il progetto grafico creato su `Read the Docs` presenta un layout più "scarno" rispetto a quello di `Material for MKDocs`, ad esempio c'è solo una sidebar verticale a sinistra per visualizzare il menù e i sottomenù dell'indice dei contenuti, mentre manca una sidebar a destra per visionare i paragrafi e sottoparagrafi della pagina che si sta leggendo  :neutral_face: 
        
        Con `Read the Docs`, prima si lavora su **Github** per la configurazione del codice sorgente e per la creazione dei contenuti (da esporre nel progetto di documentazione), poi si crea il profilo su **readthedocs.org** e si crea il progetto specifico creando la relazione (tramite l'URL) con il progetto contenente il codice sorgente su **Github**. Quindi la compilazione del progetto su pagine HTML avviene su readthedocs.org. Siamo - così - in presenza di 2 ambienti web sui quali operare, a differenza di `Material for MKDocs` in cui si opera solo su **Github** che provvede ad effettuare anche le compilazioni (gh-pages). Questo aspetto gioca indubbiamente a favore di `Material for MKDocs` :neutral_face:
