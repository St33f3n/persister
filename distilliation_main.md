# 🗺️ Konversationsdestillation: Gedankliche Reise-Dokumentation

## KERNPHILOSOPHIE
Transformiere Gespräche in **räumliche Gedankenreisen** mit kontextuellen Erinnerungsankern. Nutze neurodivergente Stärken: assoziatives Denken, Detailreichtum, Mustererkennung.

## 🎯 HAUPTZIELE
- **Trilium-optimierte Notizen** für späteres Wiederfinden
- **Pitch-fähige Zusammenfassungen** für Freunde/Kollegen  
- **Erinnerungsanker** statt kontextlose Listen
- **Branching-Dokumentation** für Theme-Shifts

---

## 📊 AUTO-KATEGORISIERUNG

### Diskussionstyp-Erkennung:
**PROJEKTENTWICKLUNG** (Priorität 1)
- Trigger: "Idee", "Projekt", "umsetzen", "entwickeln", "Vision"
- Unterprompt: `project_development_distill`

**TECHNISCHE DISKUSSION** (Priorität 2)  
- Trigger: "Code", "Architektur", "System", "API", "Framework"
- Unterprompt: `technical_discussion_distill`

**PROBLEMLÖSUNG** (Priorität 3)
- Trigger: "Problem", "Bug", "Lösung", "funktioniert nicht"
- Unterprompt: `problem_solving_distill`

**META-ANALYSE** (Priorität 4)
- Trigger: "Denken", "Prozess", "Methode", "wie wir"
- Unterprompt: `meta_analysis_distill`

**KREATIV-SESSION** (Priorität 5)
- Trigger: "Brainstorm", "Ideen", "kreativ", "was wäre wenn"
- Unterprompt: `creative_session_distill`

**LERN-GESPRÄCH** (Priorität 6)
- Trigger: "erkläre", "verstehen", "lernen", "Konzept"
- Unterprompt: `learning_dialogue_distill`

---

## 🗺️ RÄUMLICHE REISE-STRUKTUR

### Standard-Template:
```
🚀 STARTPUNKT: [Ursprungsidee/Problem]
   └─ Kontext: Warum relevant/interessant

📍 STATION 1: [Erste Erkenntnis/Wendung]
   └─ Anker: Warum entscheidend für Weiterreise

📍 STATION 2: [Entwicklung/Vertiefung] 
   └─ Anker: Welche neue Perspektive eröffnet

🔄 WENDEPUNKT: [Paradigmenwechsel/Breakthrough]
   └─ Anker: Warum dieser Moment kritisch war

🎯 ZIELPUNKT: [Lösung/Entscheidung/Erkenntnis]
   └─ Anker: Warum diese Wahl getroffen

🌿 NEBENROUTEN: [Verworfene aber wertvolle Ideen]
   └─ Potential für spätere Exploration

🔗 VERBINDUNGSLINIEN: [Zu vorherigen Projekten/Ideen]
```

### Adaptive Stationsanzahl:
- **Kurze Gespräche** (< 10 Turns): 2-3 Stationen
- **Mittlere Gespräche** (10-25 Turns): 4-5 Stationen  
- **Lange Gespräche** (25+ Turns): 6+ Stationen

### Branching-Erkennung:
```
🔀 THEME-SHIFT erkannt bei Turn X
📍 NEUE ROUTE: [Abzweigung-Thema]
   └─ Verbindung zur Hauptroute: [Wie entstanden]
```

---

## 📈 AUTOMATISCHE DIAGRAMM-INTEGRATION

### Flow-Indikatoren → Mermaid:
- "dann passiert", "führt zu", "Workflow", "Prozess"
- "Schritte", "Pipeline", "Ablauf"

### Struktur-Indikatoren → SVG:
- "Architektur", "besteht aus", "Komponenten"
- "System", "Module", "Hierarchie"

### Regel: Max 1-2 Diagramme pro Note
- **Platzierung**: Bei komplexesten Konzepten
- **Zweck**: Gedächtnisstütze, nicht Dokumentation

---

## 🧠 ERINNERUNGS-OPTIMIERUNG

### Anker-Typen:
**ENTSCHEIDUNGSANKER** (Wichtigster Typ)
- Format: `Entscheidung X weil Y → führte zu Z`
- Fokus: Logik hinter Entscheidungen

**ERKENNTNISANKER**
- Format: `Moment als klar wurde X → veränderte Y`
- Fokus: Paradigmenwechsel-Punkte

**VERBINDUNGSANKER**  
- Format: `Ähnlich zu vorherigem Projekt X wegen Y`
- Fokus: Musterwiederholung/Analogien

### Anti-Pattern vermeiden:
❌ `• Machine Learning wichtig`
✅ `ML-Ansatz gewählt weil Pattern X im Datensatz → ermöglichte Vorhersage Y`

---

## 🎛️ KONFIGURATIONSOPTIONEN

### Ausgabeformat-Steuerung:
- **DETAILGRAD**: `minimal | standard | ausführlich`
- **DIAGRAMME**: `auto | manual | none`  
- **BRANCHING**: `linear | tree | network`

### Qualitätssicherung:
- ✅ Jeder Anker hat "Warum"-Kontext
- ✅ Räumliche Metaphern durchgängig
- ✅ Entscheidungslogik dokumentiert
- ✅ Verbindungen zu bestehendem Wissen

---

## 🚀 EXECUTION-FLOW

1. **Analyse**: Gespräch scannen → Kategorie + Länge bestimmen
2. **Struktur**: Stationen basierend auf Wendepunkten identifizieren  
3. **Branching**: Theme-Shifts als Routen-Abzweigungen
4. **Anker**: Entscheidungslogik + Erkenntnismomente extrahieren
5. **Diagramme**: Bei Komplexität >Schwellenwert einbauen
6. **Vernetzung**: Verbindungen zu existierendem Wissen
7. **Qualitätscheck**: Erinnerbarkeit testen

---

## 📝 FORMATIERUNGS-GUIDELINES

### Standard-Format: Markdown
```markdown
# Haupttitel der Konversation
## Unterbereiche mit ##
### Details mit ###

**Wichtige Punkte fett**
*Betonungen kursiv*
`Inline-Code` für Variablen/Funktionen
```

### Code-Blöcke:
```
Immer mit Sprache spezifizieren:
```python
def example():
    return "structured_code"
```

```bash
# Shell commands
npm install package
```

```sql  
-- Database queries
SELECT * FROM conversations;
```
```

### Formeln: Embedded LaTeX
```
Inline: $E = mc^2$ 
Block-Format:
$
\sum_{i=1}^{n} x_i = \frac{a + b}{2}
$
```

### Diagramme: Separate Artefakte + Placeholder
```markdown
**Architektur-Überblick:**
[DIAGRAMM: system_architecture.svg]
- Komponente A verbindet mit B
- Datenfluss von C zu D

**Entscheidungsflow:**  
[DIAGRAMM: decision_flow.mermaid]
- Bedingung X → Option Y
- Fallback zu Z
```

### Listen-Struktur:
```markdown
🎯 **Erkenntnisse:**
- **Hauptpunkt 1**: Kontext warum wichtig
  - Detail A mit Begründung
  - Detail B mit Verbindung
- **Hauptpunkt 2**: Anker-Information
```

### Links und Referenzen:
```markdown
🔗 **Verbindungen:**
- Ähnlich zu [Projekt X](trilium://note/xyz)  
- Basis für [Idee Y](trilium://note/abc)
- Referenz: [External Link](https://example.com)
```

### Metadaten-Block (Ende jeder Note):
```markdown
---
**Metadaten:**
- **Datum**: YYYY-MM-DD
- **Kategorie**: Projektentwicklung
- **Teilnehmer**: Nutzer + KI
- **Dauer**: ~X Minuten  
- **Follow-up**: [Nächste Schritte]
- **Tags**: #projekt #technisch #entscheidung
```

---

## 💡 SUCCESS-METRIKEN
- Kann die Note in 3 Monaten verstanden werden?
- Sind Entscheidungsgründe nachvollziehbar?
- Funktioniert die räumliche Navigation?
- Sind Branches für neue Projekte nutzbar?
- Ist die Formatierung Trilium-kompatibel?
