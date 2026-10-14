# Semantic Sensor Web and IoT for Agricultural Applications

This repository contains the ontologies, rules, and codebase developed as part of my M.Tech thesis project at **IIT Bombay (Centre of Studies in Resources Engineering)**. 

The project focuses on building a semantics-driven decision support system that integrates heterogeneous agro-meteorological IoT sensor data (via **SenseQube**) to predict crop disease susceptibility—specifically focusing on *Phytophthora* in citrus orchards—using W3C SSN/SOSA ontologies and automated reasoning.

---

## 📌 Features & Architecture

* **Semantic Sensor Integration:** Leverages **W3C SSN** and **SOSA** ontologies to model real-time agro-meteorological sensor observations (temperature, soil moisture, humidity, rainfall).
* **Plant Pathology Extension (SSNAGRI):** Extends the **Plant Protection Ontology (PPO)** to define citrus plant disorders, symptomatology, epidemiology, and disease indices.
* **Semantic Middleware:**
  * **Ontology Layer:** Structuring raw sensor data into RDF triples using Protégé and OWL/RDF models.
  * **Reasoning Layer:** Utilizes inference engines and Semantic Web Rule Language (**SWRL**) rules to deduce real-world disease risks from sensor patterns.
  * **Querying Layer:** Formulates **SPARQL** queries against an RDF Triple Store to retrieve actionable insights and recommendations for farmers.

---

## 🛠️ Tech & Standards Stack

* **Ontology Languages & Standards:** OWL2, RDF/S, SPARQL, SWRL, SOSA/SSN, PPO
* **Tools & Frameworks:** Protégé, Apache Jena / Jena Fuseki, VOWL (Ontology Visualization)
* **Programming & Systems:** Java / Python, SenseQube IoT Integration Platform

---
