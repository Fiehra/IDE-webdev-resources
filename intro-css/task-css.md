# CSS Aufgaben

## Erstelle eine neue HTML-Datei:

- Erstelle eine Datei namens spezifitaet.html.
- Füge die grundlegende HTML-Struktur hinzu.
- Erstelle eine <div> mit der id="spezifitaet-test" und einer Klasse klasse-test.
- Füge innerhalb des <div> eine <p> hinzu.

```
<!DOCTYPE html>
<head>
    <title>CSS Spezifität</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        p {
            color: green;
        }
    </style>
</head>
<body>
    <div id="spezifitaet-test" class="klasse-test">
        <p>Dies ist ein Testparagraph.</p>
    </div>
</body>
</html>
```

## Erstelle eine neue CSS-Datei:

- Erstelle eine Datei namens styles.css.
- Füge die folgenden CSS-Regeln hinzu:

```

```

/\* Tag-Selektor /
p {
color: blue;
font-size: 16px;
}

/ Klassen-Selektor /
.klasse-test p {
color: red;
}

/ ID-Selektor \*/
#spezifitaet-test p {
color: purple;
}

```

```

## Inline-Stile hinzufügen:

- Füge den folgenden Inline-Stil zum <p> Element in der HTML-Datei hinzu:

```
<p style="color: orange;">Dies ist ein Testparagraph.</p>
```

## Untersuche die Ergebnisse:

- Öffne die HTML-Datei in einem Browser und untersuche, welche Farbe der Text im <p> Element hat.
- Ändere die Inline-Stile und die CSS-Datei, um zu sehen, wie sich die Änderungen auf die Spezifität auswirken.
