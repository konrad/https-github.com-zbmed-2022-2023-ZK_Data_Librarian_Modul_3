+++
title = "Machinelles Lernen - Automatische Textanalyse"
# If set, this will be used for the page's menu entry (instead of the `title` attribute)
# menuTitle = ""
weight = 700
# The title of the page in menu will be prefixed by this HTML content
 pre = "<b>7. </b>"
# pre = "<i class='fab fa-github'></i>"
# Table of content (toc) is enabled by default. Set this parameter to true to disable it.
# Note: Toc is always disabled for chapter pages
disableToc = "false"

# The title of the page in menu will be postfixed by this HTML content
post = ""
# Set the page as a chapter, changing the way it's displayed
chapter = true
# Hide a menu entry by setting this to true
hidden = false
# Display name of this page modifier. If set, it will be displayed in the footer.
LastModifierDisplayName = ""
# Email of this page modifier. If set with LastModifierDisplayName, it will be displayed in the footer
LastModifierEmail = ""
+++

### 18.03.21 - 24.03.21

# Machinelles Lernen - Automatische Textanalyse

## Zielsetzung

Final möchte wir mittels maschinellen Lernens Texte automatisch
analysieren. Auch hier wollen wir an einem kleinen Beispiel das
Verständnis für die Grundlagen und mögliche Anwendungen entwickelt. In
dem Beispiel werden wir Texte in Kategorien zuordnen und somit ein
kleines automatisches Verschlagwortungswerkzeug erstellen. Dazu bauen
wir auf das in der letzte Woche Erlernte zu Klassifizierugsverfahren,
aber auch auf einige Punkte aus Modul 2 namentlich Text-Frequency (TF)
und und [Term frequency inverse document
frequency](https://de.wikipedia.org/wiki/Tf-idf-Ma%C3%9F) (TFIDF)),
auf. Für die Implementation greifen wir wieder `scikit-learn` zurück.

Bitte nutzen Sie den Ordner `machine_learning` in ihrem Modul-Ordner
und erstellen Sie darin einen ein Jupyter-Notebook names
`Text-Analyse`. Die Einreichung der Ergebnisse erfolgt über einen
Commit bis zum Präsenztag. Musterlösungen sind [hier](./solutions) zu
finden.
