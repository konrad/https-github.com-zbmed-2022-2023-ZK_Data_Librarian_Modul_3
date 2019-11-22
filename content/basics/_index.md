+++
title = "Grundlagen"
# If set, this will be used for the page's menu entry (instead of the `title` attribute)
# menuTitle = "Einführung"
weight = 200
# The title of the page in menu will be prefixed by this HTML content
 pre = "<b>2. </b>"
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


### 27.01 – 02.02

# Grundlagen und deskriptive Statistik

Diese Einheit gibt eine Einführung in die Aufgaben und grundlegenden Begriffe der angewandten Statistik. Im zweiten Teil wird das `pandas` Paket vorgestellt und gezeigt, wie Datensätze eingelesen und bearbeitet werden können.

## Ziele

- Beschreiben Sie Datensätze mit dem statistischen Grundvokabular
- Lesen Sie Datensätze als `DataFrames` in Python ein und aus
- Filtern Sie `DataFrames` nach Spalten oder Zeilen
- Erstellen Sie absolute und relative Häufigkeitstabellen
- Berechnen Sie grundlegende Lagemaße, wie Median und Mittelwert

{{% customnotice exercise %}}

### Projektaufgabe

Die Pressestelle der San Francisco Public Library möchte einen Online-Artikel zum Kundenstamm der Bibliothek erstellen und braucht einige interessanten Zahlen zum Thema Alter und Bibliotheksnutzung.

- Lesen Sie [den Datensatz](/data-librarian/organisation/dataset/) ein und berechnen Sie einige interessante Statistiken.
- Senden Sie bis Freitag Ihre [Beschreibung des Datensatzes](/data-librarian/basics/basic_terms/) zusammen mit den Statistiken in Form eines integrierten *Python Notebooks* an [malte@bonart.de] (mailto:malte@bonart.de).

{{% /customnotice %}}



{{% customnotice tip %}}
Beispielfragen, die Sie mit dem Datensatz beantworten können:

- Wie viele Senioren und Kinder sind Kunden der San Francisco Public Library?
- Wie viele Nutzer möchten per Mail informiert werden?
- Wie alt sind diese Nutzer durchschnittlich im Vergleich zu Nutzern, die per Post informiert werden möchten?
{{% /customnotice %}}