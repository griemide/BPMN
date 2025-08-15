# BPMN
Business Process Model and Notation

## Private Process Flows
https://github.com/griemide/mgBPMN

### Participant Handling & Token Simulation
![Pool](images/Participant_Token-Simulation_Testset.svg)

### Conditional Flow Handling & Token Simulation
![Conditional](images/Acceptance_Testing.svg)


---
## 🟢 Flow Objects (Flussobjekte)

### 1. Events (Ereignisse)
- **Start Event**: Beginn eines Prozesses  
- **Intermediate Event**: Zwischenereignis (z. B. Timer, Nachricht)  
- **End Event**: Abschluss eines Prozesses

### 2. Activities (Aktivitäten)
- **Task**: Einzelne Aufgabe  
- **Sub-Process**: Unterprozess (kann erweitert oder eingebettet sein)  
- **Call Activity**: Aufruf eines externen Prozesses

### 3. Gateways (Verzweigungen)
- **Exclusive Gateway (XOR)**: Entweder-oder  
- **Parallel Gateway (AND)**: Gleichzeitige Ausführung  
- **Inclusive Gateway (OR)**: Eine oder mehrere Pfade  
- **Event-based Gateway**: Entscheidung basierend auf Ereignis

---
## 🔵 Connecting Objects (Verbindungselemente)

- **Sequence Flow**: Standardfluss zwischen Aktivitäten  
- **Message Flow**: Kommunikation zwischen Pools  
- **Association**: Verbindung zu Annotationen oder Datenobjekten

---
## 🟠 Swimlanes (Bahnen zur Organisation)

- **Pool**: Repräsentiert eine Organisation oder ein System  
- **Lane**: Unterteilung eines Pools, z. B. nach Abteilungen
---
## 🟣 Artifacts (Zusätzliche Informationen)

- **Data Object**: Daten, die verwendet oder erzeugt werden  
- **Group**: Visuelle Gruppierung von Elementen  
- **Annotation (Text Annotation)**: Kommentare oder Erklärungen
