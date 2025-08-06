# GoogleAppStore_Data_Manipulation_Visualization
Analisi EDA per  identificare la categoria ottimale per sviluppare una app  Google Play

## 🧭 Obiettivo dell'analisi

Identificare la categoria ottimale per sviluppare una app a tema sostenibilità su Google Play, 
basandosi su dati reali (rating, numero di recensioni, installazioni, concorrenza, tipologia, prezzo...).

---

## 📊 EDA per App Store Data

1. **Esplorazione del dataset**
   - `df.head()`, `df.info()`, `df.isnull()`
   - Comprendere le dimensioni e i tipi di dati
   - Capire come sono strutturate le colonne: `Category`, `Rating`, `Reviews`, `Installs`, `Type`, `Price`, ecc.


2. **Pulizia dei dati**
   - Conversione di `Installs`, `Price`, `Reviews` in numerico
   - Rimozione o imputazione dei valori mancanti
   - Gestione dei duplicati
   - Rimozione delle colonne non necessarie


3. **Analisi univariata**
   - Distribuzione di:
     - `Rating`, `Price`, `Size MB`
     - Tipi di app (Free vs Paid)
     - Conteggio per `Category`
     - `Sotto categorie`, `Content Rating`, `Last Update`


4. **Analisi bivariata e multivariata**
   - `Heatmap` fra `Rating`, `Reviews`, `Installs`, `Price_$`, `Size_MB`
   - `Scatterplot` fra `Installs` e `Reviews`
   - `Scatterplot` fra `Rating` e `Installs`
   - `Scatterplot` fra `Price_$(Paid)` e `Installs`
   - `Barplot` fra `Reviews Mean` e `Category`


5. **Analisi competitiva per categoria**
   - Media rating per categoria
   - Numero medio di installazioni per categoria
   - Varianza delle istallazioni per categoria
   - Matrice fra App, Rating medio, Installazioni medie e Istallazioni varianza


6.  **Clustering K-Means**
   - Preparazione dei dati per il clustering
   - Normalizzazione (fondamentale perché le scale delle variabili sono diverse)
   - Scelta ottimale del numero di cluster (k)
   - Applicazione di K-Means
   - Visualizzazione ed interpretazione 


7. **Sintesi e strategia finale**
   - Obbiettivi Strategici
   - Conclusione Pratica
