# chartist-elements
Polymer elements for [Chartist](https://gionkunz.github.io/chartist-js).

Live demo:
[](http://ohanhi.github.io/chartist-elements/)

## Usage

```html
<!-- Import -->
<link rel="import" href="chartist-pie.html">
<link rel="import" href="chartist-line.html">
<link rel="import" href="chartist-bar.html">

<!-- Use elements -->
<chartist-pie
  series='[75, 25]'
  labels='["Pacman", "Not Pacman"]'>
  </chartist-pie>

<chartist-line
  series='[[25, 22, 18, 19, 24], [0, -2, 1, 3, -1]]'
  labels='["Mon", "Tue", "Wed", "Thu", "Fri"]'>
  </chartist-line>

<chartist-bar
  series='[623, 424, 1108, 190, 981]'
  labels='["A", "B", "C", "D", "E"]'>
  </chartist-bar>
```
