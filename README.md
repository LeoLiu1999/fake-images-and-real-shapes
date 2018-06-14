# Fake Images and Real Shapes

### by Leo Liu pd 10

## 3D Solids

#### Spinning a curve/2D shape about an axis
For example, spinning an S shaped curve around a vertical axis gets a vaselike solid.

Command:

```
spinny <function in x> <start x value> <end x value>
```

Example:

```
spinny .0001*x**3-.5*x+50 -100 100
```
results in a vase

#### Following a 2D shape along a curve
For example, following a circle along a curve gets a curved pipe.

Command:

```
stacky <function in x> <start x value> <end x value> <circumradius of shape> <shape> <rotation along curve>
```

Example:

```
stacky .001x**2 0 500 50 square 10
```
results in a curved screw-like shape


## Bugs

#### lex.py will not accept general function in x in string format

Unsuccessfully tried adjusting definition of TEXT in mdl.py, but regular expression is weird :'(

## Additions if time allows

#### Mirrors / Reflective surfaces

#### More primitive polygons and 3D solids
