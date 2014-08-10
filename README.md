# MoleculeJs

## Include Dependencies & Library

```html
<script type="text/javascript" src="Molecule/dependencies/jquery-1.11.1.js"></script>
<script type="text/javascript" src="Molecule/dependencies/requestanimationframe.js"></script>
<script type="text/javascript" src="Molecule/Molecule-1.0-min.js"></script>
```

## Setup a new Molecule Stage

```javascript
var canvas = document.getElementById('myCanvas');
var stage = new Stage(canvas);
```

## Create your first Molecule
Params: X, Y, SIZE
```javascript
var molecule = new Molecule(0,0,6);
```
