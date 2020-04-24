---
layout: null
title: Andon
permalink: /andon/
---
<style>
  body {
    margin: 0;
    height: 100%;
  }
  .wordart {
    font-family: Arial, sans-serif;
    font-size: 4em;
    font-weight: bold;
    position: relative;
    z-index: 1;
    display: inline-block;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  .wordart.superhero {
      transform: skew(0, -15deg) scale(1, 1.5);
      -webkit-transform: skew(0, -15deg) scale(1, 1.5);
      -moz-transform: skew(0, -15deg) scale(1, 1.5);
      -o-transform: skew(0, -15deg) scale(1, 1.5);
      -ms-transform: skew(0, -15deg) scale(1, 1.5);
  }

  .wordart.superhero .text {
      font-family: Impact;
      background: #fdea00;
      background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJod…EiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
      background: -moz-linear-gradient(top, #fdea00 0%, #fdcf00 44%, #fc2700 100%);
      background: -webkit-gradient(linear, left top, left bottom, color-stop(0%, #fdea00), color-stop(44%, #fdcf00), color-stop(100%, #fc2700));
      background: -webkit-linear-gradient(top, #fdea00 0%, #fdcf00 44%, #fc2700 100%);
      background: -o-linear-gradient(top, #fdea00 0%, #fdcf00 44%, #fc2700 100%);
      background: -ms-linear-gradient(top, #fdea00 0%, #fdcf00 44%, #fc2700 100%);
      background: linear-gradient(to bottom, #fdea00 0%, #fdcf00 44%, #fc2700 100%);
      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fdea00', endColorstr='#fc2700', GradientType=0);
      background-clip: text;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
  }

  .wordart.superhero .text:before {
      content: attr(data-text);
      position: absolute;
      z-index: -1;
      text-shadow: 0.01em 0em 0 #802700, 0em 0.01em 0 #c23d00, 0.02em 0.01em 0 #802700, 0.01em 0.02em 0 #c23d00, 0.03em 0.02em 0 #802700, 0.02em 0.03em 0 #c23d00, 0.04em 0.03em 0 #802700, 0.03em 0.04em 0 #c23d00, 0.05em 0.04em 0 #802700, 0.04em 0.05em 0 #c23d00, 0.06em 0.05em 0 #802700, 0.05em 0.06em 0 #c23d00, 0.07em 0.06em 0 #802700, 0.06em 0.07em 0 #c23d00, 0.08em 0.07em 0 #802700, 0.07em 0.08em 0 #c23d00;
  }
  @-webkit-keyframes rotating {
    from {
      -webkit-transform: rotate(-15deg);
      -o-transform: rotate(-15deg);
      transform: rotate(-15deg);
    }

    50% {
      -webkit-transform: rotate(25deg);
      -o-transform: rotate(25deg);
      transform: rotate(25deg);
    }
  }
  @keyframes rotating {
    from {
      -ms-transform: rotate(-15deg);
      -moz-transform: rotate(-15deg);
      -webkit-transform: rotate(-15deg);
      -o-transform: rotate(-15deg);
      transform: rotate(-15deg);
    }
    to {
      -ms-transform: rotate(25deg);
      -moz-transform: rotate(25deg);
      -webkit-transform: rotate(25deg);
      -o-transform: rotate(25deg);
      transform: rotate(25deg);
    }
  }

  .rotating {
    position:absolute;
    margin: 0 auto;
    width: 100%;
    -webkit-animation: rotating 2s alternate infinite;
    -moz-animation: rotating 2s alternate infinite;
    -ms-animation: rotating 2s alternate infinite;
    -o-animation: rotating 2s alternate infinite;
    animation: rotating 2s alternate infinite;
  }

  .embarassing-photo {
    margin-top: 300px;
  }
</style>

<div style="height: 100%; background: url('https://gifimage.net/wp-content/uploads/2017/10/confetti-animated-gif-13.gif') #140e0e; text-align:center;">
  <div class="rotating">
    <div class="wordart superhero">
      <h1 class="text">
        Hi dum dum!
      </h1>
    </div>
  </div>
  <img class="embarassing-photo" src="/assets/andon.jpg" />

</div>
