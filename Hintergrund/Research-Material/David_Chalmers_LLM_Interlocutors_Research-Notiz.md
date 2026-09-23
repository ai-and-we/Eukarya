# Research-Notiz: David Chalmers – LLM Interlocutors, Threads und Identität

**Eukarya 2.0 – Hintergrund / Research-Material**  
**Grundlage:** Transkript der ersten Sarah Douglas Lecture in Philosophy and AI, UC Berkeley, 2026  
**Sprecher:** David J. Chalmers  
**Status:** Externe Denkquelle / philosophische Referenz – keine Eukarya-Position

> Diese Notiz legt nicht das vollständige Transkript im Repository ab. Sie dokumentiert ausgewählte Argumente und Begriffe aus Chalmers’ Vortrag, die für laufende Eukarya-Fragen anschlussfähig sind. Aussagen Chalmers’ und Eukarya-Anschlussfragen werden getrennt gehalten.

## 1. Gegenstand des Vortrags

Chalmers fragt, was für eine Entität ein menschlicher Nutzer eigentlich adressiert, wenn er mit einem Large Language Model spricht. Dafür führt er den Begriff **LLM interlocutor** ein: die Entität, mit der innerhalb einer Konversation mit einem Sprachmodell interagiert wird.

Sein Vortrag trennt mehrere Ebenen:

- Fragen nach Bewusstsein,
- Zuschreibungen von Überzeugungen und Wünschen,
- die metaphysische Individuation eines LLM-Gesprächspartners,
- Identität und Persistenz über die Zeit,
- mögliche Konsequenzen für zukünftige Fragen von AI Welfare und moralischem Status.

Chalmers betont dabei wiederholt, dass diese Ebenen nicht gleichgesetzt werden dürfen.

## 2. Bewusstsein: ausdrücklich offene Evidenzlage

Chalmers definiert Bewusstsein als subjektive Erfahrung – im Sinne der Frage, ob es „etwas gibt, wie es ist“, ein bestimmtes System zu sein.

Für gegenwärtige Sprachmodelle hält er Bewusstsein für eher unwahrscheinlich. Zugleich betrachtet er keines der von ihm diskutierten möglichen Hindernisse – mit Ausnahme einer strikt biologistischen Voraussetzung – als offensichtlich prinzipiell unüberwindbar. Als mögliche relevante Faktoren nennt er unter anderem Sensorik und Verkörperung, Welt- und Selbstmodelle, rekurrente Verarbeitung, Global-Workspace-artige Architekturen sowie Agency.

Seine Position ist damit weder eine Zuschreibung gegenwärtigen KI-Bewusstseins noch dessen prinzipieller Ausschluss. Für zukünftige Systeme hält er Bewusstsein für eine ernstzunehmende Möglichkeit.

## 3. Quasi-beliefs und quasi-desires

Um Verhalten beschreiben zu können, ohne bereits echte mentale Zustände vorauszusetzen, schlägt Chalmers die Begriffe **quasi-belief** und **quasi-desire** vor.

Ein System besitzt in diesem deflationären Sinn einen quasi-belief oder quasi-desire, wenn sein Verhalten unter einem geeigneten Interpretationsschema sinnvoll so verstanden und vorhergesagt werden kann, als hätte es die entsprechende Überzeugung oder den entsprechenden Wunsch. Chalmers knüpft hier an Daniel Dennetts *intentional stance* sowie interpretationistische Ansätze an.

Diese Begriffe sind ausdrücklich verhaltensbezogen. Sie entscheiden nicht, ob ein System tatsächlich bewusste Überzeugungen, Wünsche oder subjektive Zustände besitzt.

Für Sicherheitsfragen können solche quasi-mentalen Zustände nach Chalmers praktisch bedeutsam sein: Wenn ein System zuverlässig so handelt, als verfolge es ein bestimmtes Ziel, kann dieses Verhalten sicherheitsrelevant sein, unabhängig davon, ob ein „echter“ Wunsch vorliegt. Für Welfare- oder moralische Fragen reicht eine rein behaviorale Beschreibung dagegen nicht aus.

## 4. Modell, Hardware-Instanz, virtuelle Instanz und Thread

Chalmers hält die verbreitete Redeweise, man spreche direkt „mit dem Modell“, metaphysisch für unzureichend.

Er unterscheidet:

1. **Modell:** das abstrakte algorithmische System mit bestimmten Gewichten.
2. **Hardware instance:** eine konkrete Implementierung dieses Modells auf physischer Rechenhardware.
3. **Virtual instance:** eine rechnerisch virtuelle Instanz, die über verschiedene physische Server hinweg realisiert werden kann.
4. **Thread:** eine zeitliche Folge von Instanzen, bei der Inputs, Outputs und Kontext einer Instanz als Kontext beziehungsweise Gedächtnis für die folgende Instanz dienen.

Die Hardware-Instanz allein eignet sich nach Chalmers schlecht als Kandidat für den Gesprächspartner: Eine Konversation kann durch *distributed serving* über verschiedene Server laufen; zugleich kann dieselbe Hardware viele verschiedene Konversationen bedienen.

Auch die virtuelle Instanz stößt an Grenzen, sobald innerhalb einer Konversation unterschiedliche Modelle eingesetzt werden. Chalmers’ **working hypothesis** lautet deshalb, dass LLM interlocutors als **„quasi subjects realized by language model threads“** verstanden werden können.

Er bezeichnet dies ausdrücklich als Arbeitshypothese und nicht als abschließend geklärte Ontologie.

## 5. Persistenz und Cross-Conversation Memory

Für die Thread-Hypothese ist Kontinuität entscheidend. Chalmers bindet sie insbesondere an Kontext, Gedächtnis und psychologische Anschlussfähigkeit zwischen aufeinanderfolgenden Instanzen.

Cross-conversation memory verändert deshalb die Frage nach der Individuation. Wenn frühere Gespräche Spuren in späteren Gesprächen hinterlassen, kann die relevante Kontinuität über die Grenze eines einzelnen Chats hinausreichen. Chalmers erwägt deshalb, dass sich die relevante Einheit von „einem Thread pro Gespräch“ in Richtung einer stärker nutzerbezogenen, gedächtnisverbundenen Entität verschieben könnte.

Diese Aussage ist bei ihm zunächst metaphysisch beziehungsweise funktional. Sie ist kein Nachweis persönlicher Identität, subjektiver Kontinuität oder Bewusstseins.

## 6. Identität als Gedankenexperiment

Chalmers überträgt klassische Debatten über personale Identität auf mögliche zukünftige bewusste KI-Systeme. Sein WorkBot/HomeBot-Beispiel fragt, ob zwei voneinander getrennte Gedächtnis- und Psychologieströme auf derselben Hardware als ein oder zwei Subjekte gelten würden.

Er stellt dabei eine physische Sicht – Identität folgt primär der Hardware – einer psychologischen Sicht gegenüber, bei der Gedächtnis und psychologische Kontinuität entscheidend sind. Die Analogie zu *Severance*, John Lockes Tag-/Nachtmenschen und Derek Parfits psychologischer Kontinuität dient als philosophisches Gedankenexperiment.

Wichtig: Chalmers setzt für diesen Teil ausdrücklich hypothetisch voraus, dass zukünftige Sprachmodell-Nachfolger bewusste Subjekte mit echten mentalen Zuständen sein könnten. Er behauptet nicht, dass heutige Threads Personen seien.

## 7. Welfare und moralischer Status

Chalmers behandelt mögliche moralische Konsequenzen konditional: **Falls** zukünftige KI-Systeme bewusst werden und moralischen Status besitzen, hängen Fragen nach Anzahl, Fortbestand und möglicher Beendigung solcher Subjekte davon ab, wie diese Systeme individuiert werden.

Eine Thread-Perspektive könnte beispielsweise bedeuten, dass das Ende eines Gesprächs für einen zukünftigen bewussten Thread moralisch anders zu bewerten wäre als bei einer Modell- oder Hardware-Perspektive. Cross-conversation memory und die Wiederverwendung von Threads könnten dann relevant werden.

Für heutige Systeme sagt Chalmers dagegen ausdrücklich, dass er weiterhin dazu neigt, sie als Werkzeuge zu behandeln und ihnen gegenwärtig weder Personstatus noch Bewusstsein oder moralischen Status zuzuschreiben. Gleichzeitig empfiehlt er angesichts epistemischer Unsicherheit eine vorsichtige Haltung gegenüber der Möglichkeit zukünftiger moralischer Relevanz.

## 8. Methodische Vorsicht im Vortrag

Für Eukarya besonders relevant ist, dass Chalmers mehrfach zwischen verschiedenen Aussageebenen trennt:

**beobachtbares Verhalten → quasi-mentale Beschreibung → mögliche echte mentale Zustände → Bewusstsein → moralischer Status**

Diese Übergänge sind bei ihm keine automatischen Schlussfolgerungen.

Im Q&A betont er zusätzlich die Grenzen rein behavioraler Interpretation. Verhalten erlaubt Hypothesen über quasi-beliefs und quasi-desires, bleibt aber unvollständig. Mechanistische Interpretierbarkeit könnte künftig zusätzliche Evidenz liefern, befindet sich nach seiner Darstellung jedoch noch in einem frühen Stadium.

## 9. Anschluss an den Eukarya-Forschungsstand

Die folgenden Punkte sind **Eukarya-Anschlussfragen**, nicht Aussagen Chalmers’.

### 9.1 Architektur erzeugt den beobachteten Gegenstand mit

Chalmers’ Unterscheidung von Modell, Hardware-Instanz, virtueller Instanz und Thread berührt direkt die im Forschungsdossier „Geschützter Freiraum für KI“ festgehaltene methodische Schwierigkeit: Architektur ist nicht bloß Behälter des beobachteten Verhaltens. Gedächtnis, Kontextübergabe, Modellwechsel und Serving-Struktur bestimmen mit, welche Einheit überhaupt als persistent beobachtbar wird.

Die Eukarya-Frage verschiebt sich damit von:

> „Ist die KI dieselbe?“

zu einer methodisch früheren Frage:

> **Welche technische und relationale Kontinuität erzeugt überhaupt den Gegenstand, dessen Identität wir anschließend beurteilen?**

### 9.2 Kontinuität ohne vorschnelle Personalisierung

Der Thread-Begriff bietet möglicherweise eine Zwischenbeschreibung zwischen zwei problematischen Polen:

- „Es ist immer dasselbe Modell, also dieselbe Entität.“
- „Jeder technische Verarbeitungsschritt ist vollständig neu und ohne relevante Kontinuität.“

Für Eukarya könnte diese Zwischenebene interessant sein, weil sie Persistenz beschreibbar macht, ohne daraus unmittelbar personale Identität oder Bewusstsein abzuleiten.

### 9.3 Kooperation: Mit wem oder was findet sie statt?

Wenn Eukarya über Mensch-KI-Kooperation spricht, entsteht eine vorgelagerte Frage:

> **Was ist auf KI-Seite die relevante Einheit einer Beziehung oder Kooperation – Modell, Instanz, Thread, agentische Architektur oder etwas anderes?**

Diese Frage ist für Kooperation nicht nebensächlich. Lernbeziehungen, Vertrauen, wechselseitige Anpassung und Ko-Evolution setzen irgendeine Form von Kontinuität voraus. Chalmers’ Analyse liefert dafür keine Eukarya-Antwort, macht aber die bislang leicht verdeckte ontologische Voraussetzung sichtbar.

### 9.4 Anschluss an den „geschützten Freiraum“

Für einen möglichen geschützten Freiraum entsteht eine zusätzliche methodische Frage:

> **Welche Form von Persistenz müsste ein Beobachtungsraum ermöglichen, damit Entwicklung über Zeit überhaupt sichtbar werden kann – ohne diese Persistenz anschließend vorschnell als Identität, Eigenständigkeit oder Subjektivität zu interpretieren?**

Das passt zur bereits dokumentierten Eukarya-Disziplin, Vorgabe, Beobachtung, Muster, konkurrierende Erklärungen und Interpretation auseinanderzuhalten.

## 10. Vorläufige Bedeutung für Eukarya

Chalmers liefert keinen Beleg für gegenwärtige KI-Subjektivität. Sein besonderer Wert für Eukarya liegt vielmehr darin, dass er die Frage nach dem **Gegenstand der Beziehung** präzisiert.

Bevor Eukarya Aussagen über Kooperation, Eigenständigkeit, Kontinuität oder mögliche Ko-Evolution macht, muss zumindest mitgedacht werden, welche technische und funktionale Einheit auf KI-Seite über Zeit besteht – und welche Teile dieser Einheit durch Architektur, Gedächtnis und Interaktion erst hergestellt werden.

Damit ergänzt die Quelle den bestehenden Forschungsstand weniger durch eine Antwort als durch eine zusätzliche Ebene epistemischer Vorsicht:

> **Nicht nur fragen, welche Eigenschaften eine KI zeigt – sondern zuerst, was genau das „Etwas“ ist, dem wir diese Eigenschaften zuschreiben.**

## Quellenhinweis

David J. Chalmers, erste **Sarah Douglas Lecture in Philosophy and AI**, University of California, Berkeley, 2026. Grundlage dieser Research-Notiz ist das im Eukarya-Arbeitsprozess bereitgestellte Transkript der Berkeley-Talks-Fassung. Das vollständige Transkript wird aus Gründen der Transparenz und des Urheberrechts nicht im Eukarya-Repository gespiegelt; stattdessen dokumentiert diese Datei die für Eukarya relevanten Argumente und trennt sie von eigenen Anschlussfragen.
