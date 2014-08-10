# MoleculeJs
The Particle System Library behind: http://epicexit.com

![Molecule.Js at Epicexit.com](http://wautersj.be/share/molecule-tml-2.png "Molecule.Js at Epicexit.com")

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

Finally, you add the Molecule to the Stage, like so:
```javascript
stage.addChild(molecule);
```

Find your Molecule on the stage by getting it at it's position:
```javascript
stage.getChildAt(0) //Param: Index of the Molecule.
```
