# Soziale Medien, algorithmische Sucht und digitale Entfremdung
Ein interdisziplinäres Projekt im Rahmen des Moduls **Informatik und Gesellschaft**

## Überblick

Dieses Repository enthält eine wissenschaftliche Analyse über die psychologischen, neurobiologischen und strukturellen Auswirkungen algorithmischer sozialer Medien. Der Fokus liegt auf der Entstehung digitaler Suchtmechanismen, emotionaler Manipulation und sozialer Entfremdung durch plattformspezifische Recommender-Systeme.

Das Projekt basiert auf aktuellen empirischen Studien (u. a. De et al., 2025; Santini et al., 2024; Milli et al., 2024; Kramer et al., 2014) und strukturiert die Wirkung von Social Media entlang fünf zentraler Wirkungsebenen:  
**Neurobiologisch**, **technisch**, **psychologisch**, **gesellschaftlich** und **ethisch**.

### Inhalte

- `Documentation.tex` – Vollständiges Konferenzpapier im wissenschaftlichen Stil
- `Presentation.tex` – Beamer-Präsentation im Metropolis-Design zur Begleitung des Vortrags
- `run.sh` – Automatisiertes Build-Skript zum Kompilieren der Dokumente via `pdflatex`

## Installation

Zum Kompilieren wird eine funktionierende LaTeX-Distribution (z. B. TeX Live oder MikTeX) sowie das `pdflatex`-Kommando benötigt. Das verwendete Präsentationstemplate basiert auf dem [Metropolis Beamer Theme](https://github.com/matze/mtheme).

## Usage

```shell
./run.sh Documentation.tex
