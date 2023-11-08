# 06.11.2023 - CSS FRAMEWORKS - Bootstrap

## Recap

## Heute

- Was ist ein CSS-Framework?
- Hinzufügen von Bootstrap zu unserem Projekt (mit CDNs) -
  JS-Abhängigkeiten und Bootstrap-CSS, `<script src=""..."">`
- Inhalte, Komponenten, Dienstprogramme - Navigieren in der Bootstrap-Dokumentation
- Verwendung des Bootstrap-Grid-Systems: Grid-Klassen und Flex
- Intelligentes Kopieren und Einfügen - lesen, verstehen, kopieren, ändern
- Verwendung von Bootstrap-Komponenten: Erstellen einer Seite mit nahezu 0 CSS

## Was ist ein CSS-Framework?

Ein CSS-Framework ist eine Bibliothek, die ein einfacheres, standardkonformes Webdesign unter Verwendung der Sprache Cascading Style Sheets ermöglicht.

- Die Stylesheets-Sammlung erleichtert die Arbeit eines UI-Entwicklers.
- Anstatt jedes Projekt von Grund auf neu zu beginnen, gibt uns ein CSS-Framework Werkzeuge an die Hand, mit denen wir schnell eine Benutzeroberfläche erstellen können, die wir während eines Projekts wiederholen und optimieren.

## Bootstrap-CDN

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
  rel="stylesheet"
  integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM"
  crossorigin="anonymous" />

<link rel="stylesheet" href="./style.css" />

<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz"
  crossorigin="anonymous"
  defer></script>
```

## Resources

- [Bootstrap](https://getbootstrap.com/)
- [Bootstrap Cheatsheet](https://bootstrap-cheatsheet.themeselection.com/)
