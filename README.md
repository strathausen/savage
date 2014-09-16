# savage.js

Poor man's SVG library.

Less than 1k gzipped and minified.

Use it like this:

      var paper = new Savage('#svg', 400, 711);
      var circle = paper.draw('circle', {
        cx: 100, cy: 200, r: 50, fill: '#6baf7d'
      });
      var circle = paper.circle({
        cx: 50, cy: 200, r: 44, fill: '#abffdd'
      }).attr({
        'stroke-width': '6px'
      }).attr({
        stroke: '#6baf7d'
      });
