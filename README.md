# Named Entity Recognition (NER) 

## Overview

This project implements **Named Entity Recognition (NER)** using **Python** and **spaCy** to extract important 
entities from unstructured text and convert them into structured data.

The system identifies entities such as:

* **PERSON** – People names
* **ORG** – Organizations
* **GPE** – Locations (Country, State, City)
* **Custom Labels** – DISEASE / PRODUCT

---

## Features

* Load pre-trained NLP model using spaCy
* Detect standard entities (PERSON, ORG, GPE)
* Process real-world text data
* Visualize entities using **displaCy**
* Add custom entity labels like **DISEASE** or **PRODUCT**

---

## Technologies Used

* Python
* spaCy
* Pandas
* displaCy

---

## Installation

```bash
pip install spacy pandas
python -m spacy download en_core_web_sm
```

---

## Run Project

```bash
python ner.py
```

---

## Example Output

Input:

```text
Apple Inc. announced a new iPhone in California.
```

Output:

```text
Apple Inc. -> ORG  
California -> GPE
```

Custom Entity Example:

```text
COVID-19 -> DISEASE  
Diabetes -> DISEASE
```

---

## Applications

* Chatbots
* Search Engines
* Healthcare Analysis
* Information Extraction
* Knowledge Graph Creation

---

## Conclusion

This project demonstrates how NLP can extract useful information from unstructured text and 
convert it into structured machine-readable data for advanced analysis.
