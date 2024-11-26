# Analysis Instacart Online Grocery

Un progetto di analisi dati sviluppato per il corso **Modelli e Tecniche per Big Data** presso l'Università della Calabria.

## Introduzione

L'obiettivo principale è analizzare i dati relativi agli ordini online di Instacart, una delle più grandi piattaforme di consegna di generi alimentari negli Stati Uniti. Il progetto esplora tecnologie avanzate per raccogliere, archiviare e analizzare grandi dataset, fornendo insight utili per il marketing e la gestione aziendale.

## Obiettivi del Progetto

1. Identificare i prodotti più venduti e le loro variazioni durante la settimana.
2. Ottimizzare la gestione delle risorse aziendali.
3. Migliorare le strategie di marketing per incrementare il fatturato.
4. Incrementare la soddisfazione dei clienti.

## Dataset

- **Fonte**: [Kaggle - Instacart Online Grocery Dataset](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)
- Oltre 200,000 utenti e 50,000 prodotti.

## Tecnologie Utilizzate

- **Apache Spark (PySpark)**: Per elaborazione distribuita e query SQL.
- **Python**: Per scripting e analisi dati.
- **Tkinter e Matplotlib**: Per l'interfaccia grafica e la visualizzazione dei risultati.

## Implementazione

### Pre-Processing dei Dati
- Rimozione ordini di test.
- Verifica univocità delle chiavi.
- Unione dei dataset `order_prior` e `order_train`.
- Controllo di prodotti inesistenti e rimozione duplicati.

### Analisi dei Dati
- Query per individuare abitudini di acquisto, come:
  - Orari e giorni con il maggior numero di ordini.
  - Top prodotti acquistati nel weekend.
  - Prodotti più riordinati e correlati.
- Classificazione delle query per velocità: **Fast**, **Medium**, **Slow**, **Very Slow**.

## Risultati Principali

1. **Prodotti più venduti nel weekend**: 
   - Banana
   - Bag of Organic Bananas
   - Organic Strawberries
2. **Corridoi più attivi**:
   - Fresh Fruits: 3,792,661 prodotti.
   - Fresh Vegetables: 3,568,630 prodotti.
3. **Dipartimenti con maggior riacquisto**:
   - Dipartimento 4, corridoio 24: 2,726,251 prodotti.

## Conclusioni

Il progetto dimostra come i Big Data possano fornire insight preziosi per l'ottimizzazione delle risorse aziendali e il miglioramento delle strategie di vendita. L'uso combinato di PySpark e Python ha garantito prestazioni elevate e facilità di implementazione.

## Come Utilizzare il Progetto

1. **Requisiti**:
   - Python 3.x
   - Apache Spark
   - Librerie: Tkinter, Matplotlib, Pandas, Numpy

