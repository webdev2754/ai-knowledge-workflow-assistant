# AI Knowledge & Workflow Assistant

Dieses Projekt folgt dem Buch 
"AI Engineering – Building Applications with Foundation Models" von Chip Huyen.

Ziel: Ein vollständiges AI-System mit RAG, Agenten, Finetuning, Dataset Engineering,
Evaluation, Optimierung und Monitoring.
#
## Struktur
- /src – Code
- /docs – Dokumentation
- /tests – Tests
- /data – Datensätze
- /models – Modelle & Finetuning
- /config – Konfiguration

## Kapitel-zu-Modul Mapping
Dieses Projekt folgt exakt dem Aufbau des Buches:

- Modul 1 → Kapitel 1: Introduction & Planning
- Modul 2 → Kapitel 2: Foundation Models
- Modul 3 → Kapitel 3: Evaluation Methodology
- Modul 4 → Kapitel 4: Evaluate AI Systems
- Modul 5 → Kapitel 5: Prompt Engineering
- Modul 6 → Kapitel 6: RAG & Agents
- Modul 7 → Kapitel 7: Finetuning
- Modul 8 → Kapitel 8: Dataset Engineering
- Modul 9 → Kapitel 9: Inference Optimization
- Modul 10 → Kapitel 10: Architecture & Feedback

# 🚀 AI Knowledge & Workflow Assistant  
*Ein End‑to‑End‑Projekt entlang des Buches  
„AI Engineering – Building Applications with Foundation Models“ von Chip Huyen*

Dieses Projekt baut ein vollständiges AI‑System, das:

- Dokumente verarbeitet (RAG)  
- Fragen beantwortet  
- Tools nutzt (Agenten)  
- Workflows plant  
- ein eigenes Finetuning nutzt  
- eine Evaluierungs‑Pipeline besitzt  
- optimiert ist (Latenz, Kosten)  
- Monitoring & Feedback integriert  

Die gesamte Struktur folgt exakt dem Inhaltsverzeichnis des Buches.

---

# 📂 Projektstruktur


- /src – Code
- /docs – Dokumentation
- /tests – Tests
- /data – Datensätze
- /models – Modelle & Finetuning
- /config – Konfiguration



---

# 🧩 Workshop / Projektplan – Kapitel‑für‑Kapitel

---

## 📘 Modul 1 – Introduction to Building AI Applications with Foundation Models  
**Ziel:** Projekt definieren & planen

### 🔧 Projekt‑Steps
1. Use Case auswählen  
   → „AI Knowledge & Workflow Assistant“
2. Use Case Evaluation  
   - Welche Probleme löst der Assistant  
   - Welche Nutzer  
   - Welche Daten  
3. Expectations & Milestones  
   - MVP definieren  
   - Feature‑Roadmap  
4. Maintenance planen  
   - Datenupdates  
   - Modellupdates  
5. AI Engineering Stack  
   - Application Layer  
   - Model Layer  
   - Data Layer  
6. Vergleich  
   - AI Engineering vs ML Engineering  
   - AI Engineering vs Full‑Stack Engineering  

### ✅ Ergebnis  
📄 Projektplan + Architektur‑Skizze + Milestones

---

## 📗 Modul 2 – Understanding Foundation Models  
**Ziel:** Modell auswählen & verstehen

### 🔧 Projekt‑Steps
1. Modell auswählen  
   - GPT / Claude / Llama  
2. Training Data verstehen  
3. Domain‑Specific Models prüfen  
4. Sampling konfigurieren  
   - Temperature  
   - Top‑p  
   - Top‑k  
5. Structured Outputs definieren  
   - JSON‑Antworten  
   - Validierung  
6. Probabilistic Nature verstehen  

### ✅ Ergebnis  
📄 Modell‑Konfiguration + Sampling‑Strategie + Output‑Schema

---

## 📘 Modul 3 – Evaluation Methodology  
**Ziel:** Evaluierungs‑Grundlagen bauen

### 🔧 Projekt‑Steps
1. Metriken verstehen  
   - Perplexity  
   - Cross‑Entropy  
2. Functional Correctness definieren  
3. Embeddings verstehen  
4. AI as a Judge einrichten  
5. Comparative Evaluation planen  

### ✅ Ergebnis  
📄 Evaluierungs‑Framework + Metriken + Testplan

---

## 📙 Modul 4 – Evaluate AI Systems  
**Ziel:** Evaluierungs‑Pipeline entwickeln

### 🔧 Projekt‑Steps
1. Evaluation Criteria definieren  
2. Model Selection Workflow  
3. Build vs Buy Entscheidung  
4. Public Benchmarks nutzen  
5. Evaluation Pipeline bauen  
   - Komponenten testen  
   - Guidelines erstellen  
   - Methoden & Daten definieren  

### ✅ Ergebnis  
📄 Evaluierungs‑Pipeline + Benchmark‑Setup

---

## 📘 Modul 5 – Prompt Engineering  
**Ziel:** Prompt‑Stack entwickeln

### 🔧 Projekt‑Steps
1. System Prompt erstellen  
2. User Prompt definieren  
3. Few‑Shot Beispiele  
4. Prompt‑Versionierung  
5. Defensive Prompting  
6. Jailbreak‑Schutz  

### ✅ Ergebnis  
📄 Finaler Prompt‑Stack + Guardrails

---

## 📗 Modul 6 – RAG and Agents  
**Ziel:** RAG‑System + Agenten bauen

### 🔧 Projekt‑Steps

### RAG
1. Vektordatenbank einrichten  
2. Embeddings generieren  
3. Retrieval implementieren  
4. Re‑Ranking  
5. RAG‑Optimierung  

### Agenten
1. Tools definieren  
2. Planner implementieren  
3. Memory hinzufügen  
4. Failure Modes testen  

### ✅ Ergebnis  
🧠 Voll funktionsfähiges RAG‑System + Agent‑Engine

---

## 📘 Modul 7 – Finetuning  
**Ziel:** Eigenes Modell trainieren (LoRA)

### 🔧 Projekt‑Steps
1. Wann Finetuning sinnvoll ist  
2. Datensatz vorbereiten  
3. LoRA‑Finetuning durchführen  
4. Quantization nutzen  
5. Model Merging testen  

### ✅ Ergebnis  
🧠 Eigenes spezialisiertes Modell

---

## 📙 Modul 8 – Dataset Engineering  
**Ziel:** Hochwertigen Datensatz erstellen

### 🔧 Projekt‑Steps
1. Daten sammeln  
2. Daten bereinigen  
3. Deduplizieren  
4. Synthetische Daten erzeugen  
5. Daten annotieren  
6. Formatieren  

### ✅ Ergebnis  
📄 Produktionsreifer Datensatz

---

## 📘 Modul 9 – Inference Optimization  
**Ziel:** System für Kosten & Latenz optimieren

### 🔧 Projekt‑Steps
1. Latenz messen  
2. Caching einbauen  
3. Model Routing  
4. Quantization  
5. Batch‑Inference  
6. Hardware‑Optimierung  

### ✅ Ergebnis  
⚡ Schnelles, kosteneffizientes System

---

## 📗 Modul 10 – AI Engineering Architecture & User Feedback  
**Ziel:** Produktionsreife Architektur bauen

### 🔧 Projekt‑Steps
1. Context Enhancement  
2. Guardrails  
3. Model Router  
4. Gateway  
5. Caches  
6. Agent Patterns  
7. Monitoring  
8. Observability  
9. Feedback‑Loop  

### ✅ Ergebnis  
🏁 Produktionsreifes AI‑System mit Monitoring & Feedback

---

# 🎉 End‑Ergebnis des gesamten Workshops

Du baust ein vollständiges AI‑Produkt mit:

- RAG  
- Agenten  
- Finetuning  
- Dataset Engineering  
- Prompt Engineering  
- Evaluierung  
- Optimierung  
- Monitoring  
- Feedback  

Alles exakt entlang der Struktur des Buches.
