# PowerBI_FillSVG
The git for the fillSVG visual custom

## Utilisation

For used the visual you need to create a data table where you put an SVG tag like this:
```
<svg xmlns="http://www.w3.org/2000/svg" viewBox="-40 -40 80 80">
  <circle r="39"/>
  <path fill="#fff" d="M0,38a38,38 0 0 1 0,-76a19,19 0 0 1 0,38a19,19 0 0 0 0,38"/>
  <circle r="5" cy="19" fill="#fff"/>
  <circle r="5" cy="-19"/>
</svg>
```
⚠️ **For a better used take an SVG tag where there is a viewBox (like in the first line of the example)**

Then put it in the SVG field.

In the measure field you need to put a value between 0 and 1, this value will be converted in percentage and then this percentage will be used to fill the svg with a color
