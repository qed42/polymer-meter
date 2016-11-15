# \<polymer-meter\>

This is a polymer element to indicate the amount of article still left for reading. 

## Using **polymer-meter** Element in your Project

Install this using bower

```
$ bower install polymer-bg --save-dev
```

Add the element element using html imports

```
<link rel="import" href="../polymer-bg.html">
```

Example:
```    
<polymer-meter></polymer-meter>
```

Place this element at the top your page, it will watch the length of the page and at the top it will display a indicator show how much of the page you have already covered.

You may not insert any custom DOM inside of this indicator element.

### Styling
You can control the color of the indicator using css property '--progress-meter-color'

Example:
```
polymer-meter{
  --progress-meter-color: red;
}
```

Custom property | Description | Default
----------------|-------------|----------
`--progress-meter-color` | Background color of the progress indicator | `green`



