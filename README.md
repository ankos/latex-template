# Inoffizielle Latex Vorlage für die Bachelor Thesis an der HSKA

## Voraussetungen

Zur Verwendung unter Windows ist die Installation von MikTex notwendig: https://miktex.org/download
Installation der Schriftart [Charis SIL](http://software.sil.org/charis/download/). Diese Schriftart ist auf gute Lesbarkeit optimiert. Also genau das richtige für eine Abschlussarbeit.

## Einrichtung & Verwendung

Das Repository klonen und eventuell die Datei **Thesis.tex** umbenennen in z.B. **Thesis-Vorname-Nachname**. Das hat den Vorteil, das die erstellte PDF Datei gleich den richtigen Namen hat.

Als Editor empfehle ich TeXstudio: http://www.texstudio.org/

Die Vorlage wurde mit XeLaTeX getestet. Um dies in TeXstudio einzustellen muss man unter *Optionen* > *TeXstudio konfigurieren* > *Erzeugen* bei der Option *Standardcompiler* XeLaTeX setzen. Desweiteren ist für ein fehlerfreies kompilieren für die Option *Standard Bibliographieprogramm* Biber zu setzen.

## Titelseite

Die Titelseite ist nur ein Vorschlag und entspricht **nicht** den offizielen Vorgaben der HSKA.

## Verwendete Packete

Es folgt eine Auflistung der verwendeten Pakete. Diese Auswahl hat sich bisher ganz gut bei mir bewährt, hat aber keinen Anspruch auf Vollständigkeit.

#### scrartcl

Scrartcl gehört zum KOMA Script. Es bietet mehr Möglichkeiten das Dokument anzupassen als die Basis Klasse article. Außerdem verwendet KOMA Script standardmäßig Din A4.

#### polyglossia

Sprachunterstützungen wie Worttrennung und richtige Anführungszeichen für die deutsche Sprache zum Beispiel.

[Paketbeschreibung](https://www.ctan.org/pkg/polyglossia?lang=de)

#### scrlayer-scrpage

Paket zur Verwaltung von page styles, vor allem für Kopf- und Fußzeile wichtig.

[Paketbeschreibung](https://www.ctan.org/pkg/scrlayer-scrpage?lang=de)

#### setspace

Kümmert sich um den Zeilenabstand. Standardmäßig ist für das gesamte Dokument *onehalfspacing* eingestellt. Also 1.5facher Zeilenabstand.

[Paketbeschreibung](https://www.ctan.org/pkg/setspace?lang=de)

#### csquotes

Wenn man spezielle Anforderungen an Zitate hat lohnt es sich hier rein zu schauen. Außerdem verwendet biblatex das Paket um für andere Sprachen als Englisch im Literaturverzeichnis die richtigen Anführungszeichen zu setzen.

[Paketbeschreibung](https://www.ctan.org/pkg/csquotes?lang=de)

#### biblatex

Verantwortlich für die Erstellung des Literaturverzeichnises. Verwendet als Standardcompiler *Biber*, weswegen man dies zu Beginn einstellen musste. Als Stil ist *authoryear*, das setzt die Optionen *bibstyle* und *citestyle* gleichzeitig auf authoryear. die Sortierung ist auf *ynt* eingestellt, Year Name Title.

[Paketbeschreibung](https://www.ctan.org/pkg/biblatex?lang=de)

#### enumitem

Ermöglicht es die itemize Umgebung zu manipulieren. Zum Beispiel die Einrückung zu verändern.

[Paketbeschreibung](https://www.ctan.org/pkg/enumitem?lang=de)

#### tabularx

Mehr Optionen die Tablenumgebung zu manipulieren

[Paketbeschreibung](https://www.ctan.org/pkg/tabularx?lang=de)

#### graphicx

Einbinden von Bildern

[Paketbeschreibung](https://www.ctan.org/pkg/graphicx?lang=de)

#### adjustbox

[Paketbeschreibung](https://www.ctan.org/pkg/adjustbox?lang=de)

#### wrapfig

Nützlich um Text um Bilder fließen zu lassen.

[Paketbeschreibung](https://www.ctan.org/pkg/wrapfig?lang=de)
[Tutorial](https://en.wikibooks.org/wiki/LaTeX/Floats,_Figures_and_Captions)

#### acronym

Erstellen und einbinden von Abkürzungen.

[Paketbeschreibung](https://www.ctan.org/pkg/acronym?lang=de)

#### hyperref

Verlinkungen im Dokument, unteranderem auch in verschiedenen Farben.

[Paketbeschreibung](https://www.ctan.org/pkg/hyperref?lang=de)
