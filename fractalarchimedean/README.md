<link rel="stylesheet" href="../scripts/style.css">
<link rel="icon" type="image/png" href="vr/salas/imagens/icone.png">
<h2>Visualization of polyhedra with Augmented Reality (AR) and Virtual Reality (VR) in A-frame</h2>
 <b>author:</b> Paulo Henrique Siqueira - Universidade Federal do Paraná
 <br><b>contact:</b> <a href="#">paulohscwb@gmail.com</a>
 <br><a href="https://paulohscwb.github.io/polyhedra2/fractalarchimedean/pt-br/">versão em português</a>
 <form style="margin: 0 auto; float:right; text-align:right; width:100%; margin-bottom:15px;">
	<select id="url" onchange="urlHandler(this.value)" style="color:royalblue;">
		<option disabled selected value>More polyhedra:</option>
		<option value="../archimedeancatalanhulls/pt-br/">Archimedean and Catalan convex hulls</option>
		<option value="../fractalplatonic/pt-br/">Platonic polyhedra fractals</option>
		<option value="../fractalnonconvex/pt-br/">Non convex polyhedra fractals</option>
		<option disabled value="../fractalarchimedean/pt-br/">Archimedean polyhedra fractals</option>
	</select>
</form>
<script>
function urlHandler(value) {                               
    window.location.assign(`${value}`);
}
</script>

<p id="p1"></p>
  <h2 align="center"><img src="vr/salas/imagens/icone.png" style="margin-bottom:-10px" width="45"> Archimedean polyhedra fractals</h2>
Using the same principle as the construction of the Sierpinski triangle or the Koch curve, we can construct fractals from other regular polygons. When these polygons form a polyhedron, we have the construction of a fractal polyhedron.
<hr> 
<!--<p align="center"><a href="#ra">Augmented Reality</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="#m3d">3D Models</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="../">Home</a></p>
  <hr>
  <h3 align="center">Immersive room</h3>
  <div class="embed-container"><iframe width="100%" src="sala.htm" title="Sala Imersiva de Fractais de poliedros" frameborder="0" loading="lazy"></iframe></div>
  <p align="center"><img align="middle" src="../../geometria-descritiva/videos/fractalarchimedean.gif" style="max-width: 47%; border-radius:5px; margin-right:10px" loading="lazy" alt="VR immersive room to fractal polyhedra"/><a href="sala.htm" target="_blank">&#x1f517; room link</a></p>
 <hr>
  <h3 id="ra" align="center">Augmented Reality</h3>
To view fractal polyhedra in AR, simply visit:
<p align="center"><a href="ra.html" target="_blank">https://paulohscwb.github.io/polyhedra2/fractalarchimedean/ra.html</a></p> 
with any browser with a webcam device (smartphone, tablet or notebook). 
<br>Access to the VR sites is done by clicking on the blue circle that appears on top of the marker.
<p align="center"><img style="border-radius:7px;" alt="Augmented Reality to fractal polyhedra" src="ar/example.jpg" width="85%"></p>
<p align="center"><img src="ar/fractalarchimedean.gif" alt="Augmented Reality to fractal polyhedra" style="max-width: 92%; border-radius:5px;" loading="lazy"/></p>
<hr>
<h3 id="m3d" align="center">3D models</h3>
<iframe width="560" height="315" style="max-width:100%" src="https://www.youtube.com/embed/videoseries?list=PLy0I_lGW8HxU-mneUmSsccpRAAwbErHFq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->
<h4>1. Fractal tetrahedron</h4>
<a href="vr/FractalTetrahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/31A.png" class="foto" alt="Fractal Tetrahedron"></a><img src="ar/31.png" class="qr">
 <br><br>Applying the construction principle of the Sierpinski triangle to the 4 faces of the regular tetrahedron, we obtain a regular fractal tetrahedron. In the first order of fractal construction, we construct a new solid at each vertex of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2, 3 and 4.
 <table>
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>4</td>
		<td>6</td>
		<td>4</td>
	</tr>
	<tr>
		<td>1</td>
		<td>4</td>
		<td>16</td>
		<td>24</td>
		<td>16</td>
	</tr>
	<tr>
		<td>2</td>
		<td>16</td>
		<td>64</td>
		<td>96</td>
		<td>64</td>
	</tr>
	<tr>
		<td>3</td>
		<td>64</td>
		<td>256</td>
		<td>384</td>
		<td>256</td>
	</tr>
	<tr>
		<td>4</td>
		<td>256</td>
		<td>1024</td>
		<td>1536</td>
		<td>1024</td>
	</tr>
 </table>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<hr>

<br><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" loading="lazy"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Archimedean polyhedra fractals - Visualization of polyhedra with Augmented Reality and Virtual Reality</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://paulohscwb.github.io/polyhedra2/fractalarchimedean/pt-br/" property="cc:attributionName" rel="cc:attributionURL">Paulo Henrique Siqueira</a> is licensed with a license <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International</a>.

<h4>How to cite this work:</h4> 
<p>Siqueira, P.H., "Archimedean polyhedra fractals - Visualization of polyhedra with Augmented Reality and Virtual Reality". Available in: <https://paulohscwb.github.io/polyhedra2/fractalarchimedean/pt-br/>, October 2023.</p>
<!--<a target="_blank" href="https://doi.org/10.5281/zenodo.8272770"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.8272770.svg" alt="DOI"></a>-->
<br><br><b>References:</b>
<br>Weisstein, Eric W. "Archimedean Solid" From MathWorld-A Wolfram Web Resource. <a href="http://mathworld.wolfram.com/ArchimedeanSolid.html" target="_blank">http://mathworld.wolfram.com/ArchimedeanSolid.html</a>
<br>Weisstein, Eric W. "Platonic Solid" From MathWorld-A Wolfram Web Resource. <a href="http://mathworld.wolfram.com/PlatonicSolid.html" target="_blank">http://mathworld.wolfram.com/PlatonicSolid.html</a>
<br>Weisstein, Eric W. "Archimedean Dual" From MathWorld-A Wolfram Web Resource. <a href="https://mathworld.wolfram.com/ArchimedeanDual.html" target="_blank">https://mathworld.wolfram.com/ArchimedeanDual.html</a>
<br>Weisstein, Eric W. "Uniform Polyhedron." From MathWorld--A Wolfram Web Resource. <a href="https://mathworld.wolfram.com/UniformPolyhedron.html" target="_blank">https://mathworld.wolfram.com/UniformPolyhedron.html</a>
<br>Wikipedia <a href="https://en.wikipedia.org/wiki/Archimedean_solid" target="_blank">https://en.wikipedia.org/wiki/Archimedean_solid</a>
<br>Wikipedia <a href="https://en.wikipedia.org/wiki/en.wikipedia.org/wiki/Platonic_solid" target="_blank">https://en.wikipedia.org/wiki/Platonic_solid</a>
<br>McCooey, David I. "Visual Polyhedra". <a href="http://dmccooey.com/polyhedra/" target="_blank">http://dmccooey.com/polyhedra/</a>