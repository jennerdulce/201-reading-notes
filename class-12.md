## Chart JS Notes

- Develop a basic layout
1. Create a `<canvas id="" height="600" width="150">Fall Back Message</canvas>`
2. Add the script tag for Chart.js in your head tag. Similar to google fonts
3. target the canvas element
  - ```
  var canvasEl = document.getElementById('chart');
  canvasEl.getContext('2d');
  ```
4. Create a new object with the targeted element
```
var chartName = new Chart(canvasEl, {
  type: (type of graph you want),
  data: {
    labels: [A, B, C ,D],
    datasets: [{
      label: 'Name of Legend',
      backgroundColo: [
        blue,
        green,
        yellow,
        red
      ],
      borderColor: black,
      data: [#, #, #, #, #]
    }]
  }
  options: {

  }
})
```

- Use for large graphs that would typically slow website down use these options:
- removes animations what would otherwise make your website slower
```
options: {
  animation: {
    duration:0
  },
  hover: {
    animationDuration: 0
  },
  responsiveAnimationDuration: 0,
}
```

- list of all settings and their descriptions.
  - all setting are pretty self explainatory
  
REF: https://www.chartjs.org/docs/latest/