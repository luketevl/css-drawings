# EXAMPLES
 - http://codepen.io/luketevl/pen/XMaxrE

# SIZES
- 3 methods to define size:
  - Using **width** and **height** [Example](http://codepen.io/luketevl/pen/MpvPyr)
  - Using **padding** and **inline-block** [Example](http://codepen.io/luketevl/pen/bqrmwB)
  - Using **border** and **inline-block** [Example](http://codepen.io/luketevl/pen/QpMZGv)

# SQUARE

- Using **width** and **height**
```css
.square{
  width: 200px;
  height: 200px;	
}
```
  - Using **padding**
```css
.square{
  padding: 100px;
  display: inline-block;
}
```
  - Using **border**
```css
.square{
  border: 100px solid #000;
  display: inline-block;
}
```
> [Example](http://codepen.io/luketevl/pen/XMaxrE/)


# RECTANGLE

- Using **width** and **height**
```css
.square{
  width: 200px;
  height: 100px;	
}
```
  - Using **padding**
```css
.square{
  padding: 100px 50px;
  display: inline-block;
}
```
  - Using **border**
```css
.square{
  border-style: solid;
	border-color: #000;
	border-top-width: 50px;
	border-bottom-width: 50px;
	border-left-width: 100px;
	border-right-width: 100px;

  display: inline-block;
}
```
> [Example](http://codepen.io/luketevl/pen/zZdMrg)



# CIRCLE

- Using **width** and **height**
```css
.circle{
  width: 200px;
  height: 200px;
  border-radius: 50%;
}
```
  - Using **padding**
```css
.circle{
  padding: 100px;
  display: inline-block;
  border-radius: 50%;
}
```
  - Using **border**
```css
.circle{
  border: 100px solid #000;
  display: inline-block;
  border-radius: 50%;
}
```
> [Example](http://codepen.io/luketevl/pen/xqLyba/)


# SEMICIRCLE

- Using **width** and **height**
```css
.semicircle{
  width: 400px;
	height: 200px;
  border-top-left-radius: 400px;
  border-top-right-radius: 400px;
}
```
  - Using **padding**
```css
.semicircle{
  padding: 100px 200px;
  display: inline-block;
  border-top-left-radius: 400px;
  border-top-right-radius: 400px;
}
```
  - Using **border**
```css
.semicircle{
  display: inline-block;
  border-top-left-radius: 400px;
  border-top-right-radius: 400px;
  border-style: solid;
	border-color: #000;
	border-bottom-width: 100px;
	border-top-width: 100px;
	border-left-width: 200px;
	border-right-width: 200px;
}
```
> [Example](http://codepen.io/luketevl/pen/BWdGQY)



# OVAL

- Using **width** and **height**
```css
.oval{
  width: 400px;
	height: 200px;
  border-radius: 50%;
```
  - Using **padding**
```css
.oval{
  padding: 100px 200px;
  display: inline-block;
  border-radius: 50%;
}
```
  - Using **border**
```css
.oval{
  display: inline-block;
  border-radius: 50%;
  border-style: solid;
	border-color: #000;
	border-bottom-width: 100px;
	border-top-width: 100px;
	border-left-width: 200px;
	border-right-width: 200px;
}
```
> [Example](http://codepen.io/luketevl/pen/YZxREQ)


# TRIANGLE
- Using **border**
```css
.triangles{
  display: inline-block;
  border: 100px solid;
	border-bottom-color: #f00;
	border-top-color: #0f0;
	border-left-color: #0ff;
	border-right-color: #00f;
}
```

> [Example](http://codepen.io/luketevl/pen/BWdGrP)


## POLYGONS
# HEXAGON
- Using **border** with **::after** and **::before**
```css
.hexagon {
  position: relative;
  width: 500px;
  height: 250px;
  margin: 144px auto;
  background-color: #ffcc29;
}
.hexagon::before, .hexagon::after {
  content: "";
  position: absolute;
  border-left: 250px solid transparent;
  border-right: 250px solid transparent;
}
.hexagon::before {
  bottom: 100%;
  border-bottom: 144.34px solid #ffcc29;
}
.hexagon::after {
  top: 100%;
  border-top: 144.34px solid #ffcc29;
}

```
> [Example](http://codepen.io/luketevl/pen/bqMevV)
