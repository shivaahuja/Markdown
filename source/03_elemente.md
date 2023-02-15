# Verschiedene Elemente

## Geordnete Listen

1. Element 1
2. Element 2
3. Element 3

## Ungeordnete Liste

* Element 1
* Element 2
* Element 3

## Code

```html
<html>
  <head>
  </head>
</html>
```

## Zitate
Einzel Zitat:  
[vgl. @leeb_einfuhrung_2016, S. 13]

Zitatsammlung:  
(vergleich dazu @heise oder @t3n)  
[vgl. @hattie_lernen_2013, S. 33-35; außerdem @walker_problem_2009, S. 6 f.]

Zitat ohne Autor  
Hattie sagte bla bla [-@hattie_lernen_2013]

Name des Autors mit Jahr in Klammern  
@hattie_lernen_2013 sagte einmal bla bla bla


## Fußnote
Text mit Fußnote.[^1]  
Text mit Fußnote.[^2]

## Blockauszeichnung
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

## Dokumente einfügen

![Ein PNG Bild\label{fig:png_bild}](source/img/graph.png)

\begin{figure}
  \includegraphics[width=\textwidth,keepaspectratio]{source/img/graph.png}
  \caption[Ein Beispielbild mit Quellenangabe]{Ein Beispielbild. Eine unbekannte Quelle von Max Mustermann, 2013, \textit{Nicht in einem Buch zu finden}, 3, S. 110.}
  \label{fig:pp_test}
\end{figure}


## Referenzen
Ausgehend von dem Lorem ipsum Text in *Tabelle \ref{tab:lorem}* handelt es sich ...

Ausgehend von den Siebensprung in *Tabelle \ref{tab:ipsum}* handelt es sich ...

Eine Verlinkung zur *Abbildung \ref{fig:png_bild}*

Ein weitere Verlinkung zur *Abbildung \ref{fig:pp_test}*

[^1]: Diese Feststellung basiert auf vielseitigen Beobachtungen und Befragungen im Orientierungspraktikum sowie dem Kernpraktikum.

[^2]: Dies ist eine zweite Fußnote mit möglichen Ergänzungen.

\pagebreak