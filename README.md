# Studien-Landingpage (COMM_CHATBOT)

Statische Seite, kein Backend, kein JavaScript-Framework. Zwei PDFs zum
Download, eine Kontaktadresse, ein paar Eckdaten. Fertig zum Hochladen
auf GitHub Pages.

## Enthaltene Dateien

```
index.html          Die Seite selbst
style.css            Gestaltung
robots.txt            Bittet Suchmaschinen, die Seite nicht zu listen
downloads/
  README.txt          Platzhalter, hier kommen deine PDFs rein
```

## Schritt 1: PDFs einfügen

Lösch `downloads/README.txt` und leg deine zwei PDFs mit genau diesen
Namen in den Ordner `downloads/`:

- `anleitung-installation.pdf`
- `anleitung-loeschen.pdf`

Andere Dateinamen sind kein Problem, dann passt du in `index.html`
einfach die beiden `href="downloads/..."` an.

## Schritt 2: Repository auf GitHub anlegen

1. Auf github.com ein neues Repository anlegen (z.B. mit einem
   unauffälligen, nicht erratbaren Namen, da das Repo öffentlich sein
   muss, damit Pages kostenlos funktioniert)
2. Alle Dateien aus diesem Ordner in das Repository hochladen (per
   Weboberfläche reicht "Add file" -> "Upload files", drag & drop)

## Schritt 3: GitHub Pages aktivieren

1. Im Repository zu Settings -> Pages
2. Bei "Source" den Branch `main` und Ordner `/ (root)` auswählen
3. Speichern, nach ein bis zwei Minuten ist die Seite live unter
   `https://DEINUSERNAME.github.io/REPONAME/`

## Schon eingebaut

- `<meta name="robots" content="noindex, nofollow">` in `index.html`
  und eine `robots.txt`, damit Suchmaschinen die Seite nicht listen.
  Sie bleibt trotzdem für jeden mit dem Link erreichbar, das Repo
  selbst ist auf GitHub öffentlich einsehbar (kostenloses Pages
  verlangt ein public Repo).
- Keine Formulare, kein Tracking, kein serverseitiger Code, dadurch
  minimale Angriffsfläche.

## Kontakt ändern

Die Mailadresse `bruno.lehmann@uni-graz.at` steht direkt in
`index.html` im Abschnitt "Kontakt", einfach dort anpassen.
