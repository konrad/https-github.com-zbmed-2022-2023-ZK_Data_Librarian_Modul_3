+++
title = "Deskriptive Statistik und Visualisierungen"
# If set, this will be used for the page's menu entry (instead of the `title` attribute)
# menuTitle = "Einführung"
weight = 300
# The title of the page in menu will be prefixed by this HTML content
 pre = "<b>3. </b>"
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


### 04.03.21 – 10.03.21

# Deskriptive Statistik und Visualisierungen

Dieses Modul gibt eine Einführung in die deskriptive Statistik mit `pandas` und zeigt, wie statistische Visualisierungen in Python erstellt werden können. 

<!-- Versuchen Sie zuerst die Aufgaben innerhalb der angegeben Zeit selbstständig zu lösen. Versuchen Sie danach mit Hilfe der Musterlösung die Lösung nachzuvollziehen. Schreiben Sie sich bei Problemen Ihre Fragen auf, damit wir diese am Präsenztag zusammen besprechen können. 
-->
## Ziele

- Berechnen und interpretieren Sie grundlegende Lage- und Streuungsmaße
- Beschreiben Sie univariate stetige und diskrete Verteilungen
- Beschreiben und berechnen Sie Statistiken für stetige und diskrete bivariate Verteilungen
- Erstellen Sie einfache Visualisierungen

{{% customnotice exercise %}}

### Projektaufgabe

Für den Online-Artikel zum Kundenstamm der Bibliothek braucht die Pressestelle einige interessanten Zahlen zum Thema Alter und Bibliotheksnutzung. Außerdem möchte sie die Daten in einer Info-Graphik zusammenstellen.

Für eine erste Demo sind Sie verantwortlich.

- Berechnen Sie 2-3 Statistiken und Erstellen Sie 2-3 Visualisierungen basierend auf den Informationen im [Datensatz](/data-librarian/organisation/dataset/).
- Nutzen Sie `pandas` zur Berechnung der Statistiken und `seaborn` für die Visualisierungen.

Schicken Sie bis spätestens zum Projekttag Ihren Report in Form eines *Python Notebooks* an [malte@bonart.de](mailto:malte@bonart.de?subject=data%20librarian:%20library%20usage%20report). Sie können Ihr Notebook auch gerne mit den anderen Studierenden auf der Kursplatform teilen. 
{{% /customnotice %}}


{{% customnotice tip %}}
Beispielfragen, die Sie mit dem Datensatz beantworten und visualisieren können:

- Wie viele Senioren und Kinder sind Kunden der San Francisco Public Library?
- Wie viele Nutzer möchten per Mail informiert werden?
- Wie alt sind diese Nutzer durchschnittlich im Vergleich zu Nutzern, die per Post informiert werden möchten?
- Wie viele Ausleihen werden im Mittel pro Altersgruppe und pro Jahr getätigt? Ist die Streuung zwischen den Gruppen gleich?
{{% /customnotice %}}
