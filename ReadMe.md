# Algebra Skript 2023/24

Ein **inoffizielles** Skript der Algebra-Vorlesung des KIT.

Eine Komilitonin und ich texen, soweit wir da sind und die Geräte und Steckdosen haben, den Tafelanschrieb mit.
Das Skript ist nicht 100% vollständig: Es fehlen Graphiken und ein paar Beweise.
Die Numerierung ist aber konsistent mit der Vorlesung.

[PDF](https://petrusbellmonte.github.io/AlgebraSkript)


## Notation
Ich nutze Übungs-Notation. Das heißt, dass Untergruppen $\subseteq$ und nur echte Untergruppen $\subset$ verwenden. Ähnlich sind echte Normalteiler $\vartriangleleft$ und Normalteiler $\trianglelefteq$.
Diese Formatierung ist möglicher Weise nicht ganz konsistent für die früheren Vorlesungen (sobalt `\nt` im .tex auftaucht, sollte es konsistent sein).

## Mitmachen
Wenn du Beweise, Abschnitte oder Graphiken erzänzen oder korrigieren willst (oder irgendetwas anderes erzänzen/formatieren willst), stelle gerne eine pull-request.
Bitte beachte die Anmerkungen zur Notation und behalte die Numerierung aus der Vorlesung bei.
Bei Problemen kontaktiere mich einfach.

### HowTo mit Overleafs
Forke das Projekt, und wähle beim erstellen des neuen Projekts in overleafs "Import from Github" aus. Möglicherweise wirst da dabei aufgefordert Github mit Overleafs zu verbinden.

Das Projekt funktioniert nur mit dem pdfLaTeX- Compile (in Overleafs im Menü auswählbar, wenn nicht bereits standartmäßig eingestellt).

Im Overleafs Menü kann man änderungen wieder in Github pushen, wenn man im "Sync"-Berreich auf Github klickt. Aus Github kann man dann eine Pull-request stellen.

### Theorems
Wir nutzen folgende theorem-typen, die mit `\begin{<name>}...\end{<name>}` genutzt werden können:

| Typ | theorm-name  |
| --- |--------------|
| Satz | `theorem`    |
| Korollar | `corollary`  |
| Lemma | `lemma`      |
| Definition | `definition` |
| Beispiel | `example` *  |
| Bemerkung | `remark` *   |
| Erinnerung | `reminder` * |

`*`= use `<theorem-name>*` to not nuber it

### Shortcuts

Einsehbar in `main.tex`. z.b

| command | value |
| --- | --- |
| `\Z`, `\N`, `\Q`, `\C`, `\F` | $\mathbb{Z}$, $\mathbb{N}$, $\mathbb{Q}$, $\mathbb{C}$, $\mathbb{F}$ |
| `\nt`, `\nteq` | $\vartriangleleft$, $\trianglelefteq$ |
| `\trivG` | $\{e\}$ |
| `\imph` | `\emph` & `\index` |

