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
Pass in the X, Y and Radius of your Molecule and you are good to go.  
Aditionally you can set some other properties if you'd like:

```javascript
var molecule = new Molecule(0,0,6);
molecule.color = '#FF0000';
molecule.alpha = 1;
```
