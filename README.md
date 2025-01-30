# Automatic-Emotion-Annotation
This repository contains a Jupyter Notebook that explores the capabilities of Large Language Models in automatically annotating emotions.

# English Introduction

In media, particularly in news articles, emotions and moral values play a crucial role in shaping public opinion and influencing audience engagement.  

This project aims to annotate and analyze emotions and moral traits present in content published by HuffPost using advanced language models:  
- LLama 3.1  
- Mistral  
- Gemma  

The objectives are to assess the ability of different models in emotion annotation, evaluate their consistency, and measure the degree of agreement among them. This is particularly important as the availability of large datasets increases, and the cost of human annotation becomes a significant factor. Developing a reliable automated annotation methodology is therefore of utmost importance.  

The methodology used for dataset annotation involves providing the models with two distinct prompts: the first focuses on evaluating emotions within the text, while the second is used for annotating moral dimensions. For each model, three different decoding strategies have been explored: *greedy decoding*, *top-k sampling*, and *top-p sampling*. Additionally, the models annotated emotions under two different scenarios: in the first, they were allowed to consider a "neutral" emotion (or moral trait), while in the second, this option was restricted.  

This approach, inspired by the work [E2MoCase: A Dataset for Emotional, Event and Moral Observations in News Articles on High-impact Legal Cases](https://arxiv.org/abs/2409.09001), not only enables an analysis of the capabilities of advanced language models but also helps identify optimal strategies for robust, consistent, and scalable automatic annotation. The results of this study will provide a detailed comparison of the selected models, offering a unique perspective distinct from previous studies in the field.  

**NOTE**: The *prompt templates* used for the different models are specified in Appendix A. In addition to the prompts, a brief explanation is provided on why certain templates are more effective depending on the model used.


# Introduzione in Italiano

Nei media, in particolare nelle notizie, le emozioni e i valori morali svolgono un ruolo cruciale nel modellare l'opinione pubblica e nel determinare il coinvolgimento del pubblico.
Il progetto si propone di annotare e analizzare emozioni e tratti morali presenti nei contenuti pubblicati dall'HuffPost utilizzando modelli di linguaggio avanzato:
- LLama 3.1
- Mistral
- Gemma

Gli obiettivi sono verificare la capacità dei diversi modelli nell'annotazione delle emozioni, valutarne la coerenza e il grado di accordo che questi hanno tra di loro. Ciò risulta essere fondamentale poiché con l'aumento dei dati a disposizione e il costo dell'impiego umano per l'annotazione di dataset, risulta essere di estrema importanza avere a disposizione una metodologia automatica di annotazione che sia affidabile.

La metodologia utilizzata per l'annotazione del dataset preso in considerazione consiste nel fornire ai modelli due prompt distinti: il primo relativo alla valutazione delle emozioni all'interno del testo; il secondo utilizzato invece per l'annotazione delle dimensioni morali. Per ogni modello sono state esplorate tre diverse modalità di decoding: *greedy decoding*, *top-k sampling*, *top-p sampling*. I modelli, inoltre hanno annotato le emozioni in due scenari differenti: in un caso veniva data possibillità al modello di considera una "emozione" (o tratto morale) neutrale, nel secondo è stata preclusa questa possibilità.

Questo approccio, ispirato dal lavoro [E2MoCase: A Dataset for Emotional, Event and Moral Observations in News Articles on High-impact Legal Cases](https://arxiv.org/abs/2409.09001) consente non solo di analizzare le capacità di modelli linguistici avanzati, ma anche di identificare strategie ottimali per un'annotazione automatica che sia robusta, coerente e scalabile. I risultati di questo studio offriranno un confronto dettagliato tra i modelli selezionati aggiungendo un punto di vista diverso dai lavori effettuati nello stesso ambito.

**NOTA**: I *template* dei prompt utilizzati per i diversi modelli sono specificati nell'Appendice A. Oltre ai prompt, è presente una breve spiegazione del perché questi, a seconda del modello, risultano essere più efficaci.


# WorkFlow Scheme

![Project WorkFlow]("diagramma di flusso progetto.png")



# Autori

- Gallo Ilaria
- Irtuso Remo

