Fourier transforms are a tool used in a whole bunch of different things. This is an explanation of what a Fourier transform does, and some different ways it can be useful. And how you can make pretty things with it, like this thing:

<canvas id="self-draw" class="sketch" width=500 height=500></canvas>

<div class="multi-container">
<div class="sketch" >
    <canvas id="draw-zone" class="sketch-child" width=500 height=500></canvas>
    <p id="draw-zone-instruction" class="instruction">Draw here!</p>
    <button id="draw-zone-undo-button" class="button embedded-button">Undo</button>
</div>
<div class="sketch">
	<canvas id="circle-zone" class="sketch-child" width=500 height=500></canvas>
	<a id="download-elem" style="all: revert;">
		<button id="circle-zone-download-button" class="button embedded-button">Download</button>
	</a>
</div>
</div>
<input id="circle-zone-slider" type="range" min="0" max="1" value="1" step="any">

*Use the slider to control how many circles are used for your drawing*


<div class="multi-container">
<div class="sketch" >
    <canvas id="wave-draw" class="sketch-child" width=500 height=300></canvas>
    <p id="wave-draw-instruction" class="instruction wave-instruction">Draw here!</p>
</div>
<canvas id="wave-draw-split" class="sketch" width=500 height=500></canvas>
</div>
<input id="wave-draw-slider" type="range" min="0" max="1" value="1" step="any">
<button id="wave-draw-button" class="button">Play Wave</button>

*Move the slider to see how as we add more sine waves, it gets closer and closer to your drawing*
<div class="container">
<p class="codepen" data-height="500" data-theme-id="light" data-default-tab="js,result" data-user="MuLx10" data-slug-hash="bGGwKpr" style="height: 500px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Fourier">
  <span>See the Pen <a href="https://codepen.io/MuLx10/pen/bGGwKpr">
  Fourier</a> by Mehul Kumar Nirala (<a href="https://codepen.io/MuLx10">@MuLx10</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>
</div>
