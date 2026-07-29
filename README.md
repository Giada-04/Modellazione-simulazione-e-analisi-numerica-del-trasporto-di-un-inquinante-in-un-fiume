# Equazione di Avvezione-Diffusione

## Modellazione, simulazione e analisi numerica del trasporto di un inquinante in un fiume

Progetto sviluppato per il corso di **Calcolo Scientifico**.

**Autori:**  
Eleonora De Cicco  
Aurora Di Giovanna  
Giada Manfredi  

**Corso di laurea:** Scienze matematiche per l'intelligenza artificiale

**Università:** Sapienza Università di Roma

**Anno accademico:** 2025/2026

---

## Descrizione

In questo lavoro si studia l'equazione di avvezione-diffusione come modello per descrivere il trasporto e la diffusione di un inquinante in un tratto unidimensionale di fiume.

Il modello viene derivato a partire dalla legge di conservazione della massa e discretizzato mediante differenze finite centrate nello spazio ed Eulero esplicito nel tempo.

Per analizzare il metodo numerico viene introdotto un problema ausiliario con condizioni periodiche al bordo, per il quale si ricava una soluzione esatta tramite serie di Fourier. Questo caso permette inoltre di dimostrare la consistenza, la stabilità (mediante l'analisi di Von Neumann) e la convergenza dello schema numerico.

Infine, i risultati teorici ottenuti vengono utilizzati per simulare il problema originario con condizioni di Dirichlet all'estremo sinistro e di Neumann all'estremo destro.

---

## Contenuto del repository

- `relazione.pdf`
- `colab.ipynb` – implementazione in Python.
