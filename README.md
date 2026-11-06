# Methoden der Data Science (MODS) – WS 2026/27

Universität Paderborn

Dieses Repository enthält alle **Python-Notebooks** zur Vorlesung und Übung **Methoden der Data Science**.

## Aufbau

Jede Woche kommt ein **neuer Ordner** hinzu. Er ist nach dem Thema der jeweiligen Vorlesung benannt und enthält die Notebooks dieser Woche:

- **Vorlesung:** Demo-Notebooks aus der Vorlesung (Dateiname endet auf `_Lecture`)
- **Übung:** Notebook zum Übungsblatt der Woche (Dateiname beginnt mit `MODS_`)

| Woche | Ordner                         | Notebooks                                                                                                                                                                                                                                                                                            |
| ----- | ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | `Intro_to_Python/`             | **Übung:** `MODS_Python_Intro.ipynb` – Einführung in Python: Variablen, Funktionen, Listen, NumPy                                                                                                                                                                                                    |
| 2     | `Transformation_and_Cleaning/` | **Übung:** `MODS_Transformation_and_Cleaning.ipynb` – Arbeiten mit Tabellen in pandas, Datentransformation und -bereinigung                                                                                                                                                                          |
| 3     | `Visualization/`               | **Übung:** `MODS_Visualization.ipynb` – Datenvisualisierung                                                                                                                                                                                                                                          |
| 4     | `Linear_Regression_1/`         | **Vorlesung:** `LM_by_hand_Lecture.ipynb` – Regressionsgerade von Hand anpassen<br>**Vorlesung:** `LM_with_OLS_Lecture.ipynb` – Lineare Regression mit OLS (Advertising-Datensatz)<br>**Übung:** `MODS_Linear_Regression_1.ipynb` – Einfache und multiple lineare Regression (BikeSharing-Datensatz) |

Weitere Ordner kommen im Laufe des Semesters dazu.

Der Ordner `data/` enthält alle Datensätze, die in den Notebooks verwendet werden.

## Notebooks öffnen

Die Notebooks lassen sich direkt in **Google Colab** öffnen, ohne lokale Installation. Gehen Sie dafür auf den Notebook und Ersetzen Sie im Browser in der GitHub-Adresse eines Notebooks `github.com` durch `colab.research.google.com/github`.

Beispiel:

```
https://colab.research.google.com/github/kbrennig/MODS_WS26_27/blob/main/Intro_to_Python/MODS_Python_Intro.ipynb
```

Die Datensätze werden in den Notebooks direkt aus dem Ordner `data/` dieses Repositorys geladen.
