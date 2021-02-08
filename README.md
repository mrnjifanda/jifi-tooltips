# jifi-tooltips
Système de Tooltips en pure CSS

## Utilisation

Ajouter le fichier css dans votre page
```html
<link rel="stylesheet" href="dist/tooltips.css">
```

### Simple utilisation

Il sufit juste d'ajouter la classe `jifi-tooltip` et l'attribu `jifi-tooltip="Votre message"`

```html
 <a href="#" class="jifi-tooltip" jifi-tooltip="It's Sample tooltip">Black Top Tooltip</a>
```

### Position
Par defaut le message s'affiche en haut, vous avez trois autres positions `left`, `right` et `bottom`

```html
<a href="#" class="jifi-tooltip left" jifi-tooltip="It's Sample tooltip">Black Top Tooltip</a>
```