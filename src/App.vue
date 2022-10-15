<template>
  <svg xmlns="http://www.w3.org/2000/svg" style="background-color: rgb(255, 255, 255); width:100%;max-width:500px;"
       xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 500 500">
    <defs>

      <linearGradient id="liquid-gradient" bx:pinned="true" x1="0" x2="0" y1="0" y2="1">
        <title>liquid-gradient</title>
        <stop class="stop-liquid-dark" offset="0"></stop>
        <stop class="stop-liquid" offset="1"></stop>
      </linearGradient>
      <marker id="marker-arrowhead" viewBox="0 0 10 10" overflow="visible" orient="auto" refX="2" refY="5" markerWidth="2" markerHeight="2" xlink:href="#marker-arrowhead">
        <title>arrowhead</title>
        <path class="liquid-arrowhead" d="M 10.92 8.378 Q 11.217 7.863 11.514 8.378 L 15.867 15.93 Q 16.164 16.445 15.57 16.445 L 6.864 16.445 Q 6.27 16.445 6.567 15.93 Z" transform="matrix(-0.000078, 1, -1, -0.000078, 17.746244, -6.216717)"></path>
      </marker>
      <marker id="marker-arrowhead-large" viewBox="0 0 10 10" overflow="visible" orient="auto" refX="2" refY="5" markerWidth="4" markerHeight="4" xlink:href="#marker-arrowhead">
        <title>arrowhead</title>
        <path class="tax-arrowhead" d="M 10.92 8.378 Q 11.217 7.863 11.514 8.378 L 15.867 15.93 Q 16.164 16.445 15.57 16.445 L 6.864 16.445 Q 6.27 16.445 6.567 15.93 Z" transform="matrix(-0.000078, 1, -1, -0.000078, 17.746244, -6.216717)"></path>
      </marker>
      <path id="mypath" d="M 0,50 C 0 15 15 0 50 0" class="flow-liquid" pointer-events="stroke"/>

    </defs>
    <g>
      <g transform="translate(190,20)">
        <rect x="0" y="0" class="svg-textbox"/>
        <switch>
        <foreignObject class="svg-textbox" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility">
          <div xmlns="http://www.w3.org/1999/xhtml">
              <div class="svg-textbox" style="padding-top: 15px">
                Products and Services Market
              </div>
          </div>
        </foreignObject>
        <text class="svg-textbox">Products and Services Market</text>
        </switch>
      </g>
      <path d="M 80,220 C 80 50 80 50 180 50" id="consuming" class="flow-liquid"/>
      <g transform="translate(360,220)">
        <rect x="0" y="0" class="svg-textbox entity"/>
        <switch>
          <foreignObject class="svg-textbox" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility">
            <div xmlns="http://www.w3.org/1999/xhtml">
              <div class="svg-textbox" style="padding-top: 22px">
                Business
              </div>
            </div>
          </foreignObject>
          <text class="svg-textbox">Business</text>
        </switch>
      </g>
      <path d="M 310,40 C 430 40 430 40 430 210" id="producing" class="flow-liquid"/>
      <path d="M 310,60 C 410 60 410 60 410 210" id="utilizing" fill="none" stroke="none"/>
      <path d="M 410,220 C 410 60 410 60 320 60" class="flow-liquid"/>
      <g transform="translate(190,420)">
        <rect x="0" y="0" class="svg-textbox"/>
        <switch>
          <foreignObject class="svg-textbox" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility">
            <div xmlns="http://www.w3.org/1999/xhtml">
              <div class="svg-textbox" style="padding-top: 22px">
                Labor Market
              </div>
            </div>
          </foreignObject>
          <text class="svg-textbox">Labor Market</text>
        </switch>
      </g>
      <path d="M 420,280 C 420 450 420 450 320 450" id="employing" class="flow-liquid"/>
      <g transform="translate(20,220)">
        <rect x="0" y="0" class="svg-textbox entity human"/>
        <switch>
          <foreignObject class="svg-textbox" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility">
            <div xmlns="http://www.w3.org/1999/xhtml">
              <div class="svg-textbox" style="padding-top: 22px">
                Human
              </div>
            </div>
          </foreignObject>
          <text class="svg-textbox">Human</text>
        </switch>
      </g>
      <path d="M 190,450 C 80 450 80 450 80 290" id="working" class="flow-liquid"/>
      <path d="M 140,240 C 190 220 300 220 350 240" id="investing" class="flow-liquid"/>
      <path id="investing-hover" class="flow-liquid-hover" d="M 140,240 C 190 220 300 220 350 240"></path>
      <path d="M 360,260 C 300 280 190 280 150 260" class="flow-liquid"/>
      <path d="M 140,260 C 190 280 300 280 350 260" id="returns" fill="none" stroke="none" />

      <text >
        <textPath href="#investing" class="flow-label" startOffset="50%">Investing</textPath>
        <textPath href="#returns" class="flow-label" startOffset="50%">Returning profit</textPath>
      </text>
      <text>
        <textPath href="#consuming" class="flow-label" startOffset="50%">Consuming</textPath>
        <textPath href="#producing" class="flow-label" startOffset="50%">Producing</textPath>
        <textPath href="#utilizing" class="flow-label" startOffset="50%">Utilizing</textPath>
      </text>
      <text>
        <textPath href="#employing" class="flow-label" startOffset="50%">Employing</textPath>
        <textPath href="#working" class="flow-label" startOffset="50%">Working</textPath>
      </text>
      <path display="none" class="flow-tax" d="M 246.959 19.209 C 422.606 19.209 532.386 209.353 444.562 361.467 C 356.739 513.582 137.18 513.582 49.357 361.467 C -27.451 228.433 46.487 59.044 196.262 24.913" transform="matrix(0.104528, -0.994522, 0.994522, 0.104528, -24.797894, 467.221399)"></path>


    </g>
    <switch>
      <g requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"/>
      <a transform="translate(0,-5)" xlink:href="https://www.diagrams.net/doc/faq/svg-export-text-problems"
         target="_blank">
        <text text-anchor="middle" font-size="10px" x="50%" y="100%">Text is not SVG - cannot display</text>
      </a></switch>
  </svg>
</template>

<script>
export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
:root{
  --color-liquid: rgb(137, 225, 245);
  --color-liquid-dark: rgb(63, 173, 200);
  --color-tax: rgba(255, 0, 0, 0.51);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.svg-textbox {
  width: 120px;
  height: 60px;
  fill: white;
  stroke: black;
  display: inline-block;
  font-size: 12px;
  pointer-events: all;
}
.entity {
  rx: 10px;
}
.human {
  fill: #FF7F7FFF;
}
.stop-liquid{
  stop-color: var(--color-liquid);
}
.stop-liquid-dark{
  stop-color: var(--color-liquid-dark);
}
.tax-arrowhead{
  stroke-width: 0px;
  stroke: none;
  fill: var(--color-tax);
}
.liquid-arrowhead{
  stroke-width: 0px;
  stroke: none;
  fill: url(#liquid-gradient);
}
.flow-liquid {
  stroke-dashoffset: 0px;
  marker-end: url("#marker-arrowhead");
  stroke-miterlimit: 1;
  fill: none;
  stroke: rgb(137, 225, 245);
  paint-order: stroke;
  stroke-width: 12px;
}
.flow-liquid-hover {
  display: none;
  fill: none;
  stroke: rgb(255, 234, 0);
  stroke-dashoffset: 0%;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 8;
  stroke-width: 4px;
  animation: draw 30s linear infinite;
}
@keyframes draw {
  0% {
    stroke-dashoffset: 100%;
  }
  100% {
    stroke-dashoffset: 0%;
  }
}
.flow-liquid:hover ~ #investing-hover, .flow-liquid-hover:hover {
  display: block;
}
.flow-tax {
  stroke-dashoffset: 0px;
  marker-end: url("#marker-arrowhead-large");
  stroke-miterlimit: 1;
  fill: none;
  stroke: var(--color-tax);
  paint-order: stroke;
  stroke-width: 5px;
}
.flow-label {
  font-size: 12px;
  text-anchor: middle;
  dominant-baseline: middle;
}

</style>
