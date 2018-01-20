---
layout: page
title: Visualization & Design
subtitle: ###
---
 
function resizeViewbox() {
    var targetWidth = $('#canvas').width();

    if (targetWidth > frameWidth) {
      targetWidth = frameWidth;
    }

    chart.attr("width", targetWidth);
    chart.attr("height", targetWidth / aspect);
}

### Famine Forecasting Framework (D3.js)

<iframe src="http://bl.ocks.org/aish-venkat/f0d85e296cecc5a9ba97288a06b6f797" width="100%" height="340" seamless frameBorder="0" scrolling="no"></iframe>
