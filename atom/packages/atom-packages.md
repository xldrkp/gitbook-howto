# Atom-Plugins für die Entwicklung von GitBooks

## browser-plus

URL: https://atom.io/packages/browser-plus

Das Package öffnet lokale und entfernte Dateien und kann Live Reload. Damit eignet es sich sehr gut für eine geteilte Arbeitsoberfläche in Atom: links das Markdown-Dokument, rechts die URL der dazugehörigen GitBook-Seite. Sofern im Hintergrund der Entwicklungsserver läuft (gestartet mit `gitbook serve`), wird die Webseite rechts nach dem Speichern des Dokuments links neu geladen.

Komplikationen kann es im Zusammenhang mit [terminal-plus](https://atom.io/packages/terminal-plus) geben. Es ist vorgekommen, dass sich das Terminalfenster unten nicht wie gewohnt wieder einblenden ließ. Auch das Öffnen neuer Terminalfenster mit dem "+"-Symbol war nicht möglich. Der Konflikt konnte bisher nur gelöst werden, nachdem der Browsertab von *browser-plus* geschlossen und Atom neu geladen wurde. Dennoch erleichtert *browser-plus* die Arbeit sehr, da das Umschalten zu einem externen Browser entfällt.
