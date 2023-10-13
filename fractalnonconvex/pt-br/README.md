<link rel="stylesheet" href="../../scripts/style.css">
<link rel="icon" type="image/png" href="../vr/salas/imagens/icone.png">
<h2>Visualização de poliedros com Realidade Aumentada (RA) e Realidade Virtual (RV) em A-frame</h2>
<b>autor:</b> Paulo Henrique Siqueira - Universidade Federal do Paraná
<br><b>contato:</b> <a href="#"> paulohscwb@gmail.com </a>
<br><a href="https://paulohscwb.github.io/polyhedra2/fractalnonconvex/">english version</a>
<form style="margin: 0 auto; float:right; text-align:right; width:100%; margin-bottom:15px;">
	<select id="url" onchange="urlHandler(this.value)" style="color:royalblue;">
		<option disabled selected>Mais poliedros:</option>
		<option value="../../archimedeancatalanhulls/pt-br/">Cascos convexos de Arquimedes e Catalan</option>
		<option value="../../fractalplatonic/pt-br/">Fractais dos poliedros de Platão</option>
		<option disabled value="../../fractalnonconvex/pt-br/">Fractais dos poliedros não convexos</option>
		<option value="../../fractalarchimedean/pt-br/">Fractais dos poliedros de Arquimedes</option>
	</select>
</form>
<script>
function urlHandler(value) {                               
    window.location.assign(`${value}`);
}
</script>

<p id="p1"></p>
  <h2 align="center"><img src="../vr/salas/imagens/icone.png" style="margin-bottom:-10px" width="45"> Fractais dos poliedros não convexos</h2>
  Utilizando o mesmo princípio da construção do triângulo de Sierpinski ou da curva de Koch, podemos construir fractais de outros polígonos regulares. Quando estes polígonos formam um poliedro, temos a construção de um poliedro fractal.
 <hr>
<!-- <p align="center"><a href="#ra">Realidade Aumentada</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="#m3d">Modelos 3D</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="../../pt-br/">Página Inicial</a></p>
  <hr>
  <h3 align="center">Sala imersiva</h3>
  <div class="embed-container"><iframe width="100%" src="../sala.htm" title="Sala Imersiva de fractais de poliedros" frameborder="0" loading="lazy"></iframe></div>
  <p align="center"><img align="middle" src="../../../geometria-descritiva/videos/fractalnonconvex.gif" style="max-width: 47%; border-radius:5px; margin-right:10px" loading="lazy" alt="Sala Imersiva de RV para fractais de poliedros"/><a href="../sala.htm" target="_blank">&#x1f517; link da sala</a></p>
<hr>
  <h3 id="ra" align="center">Realidade Aumentada</h3>
  Para visualizar os fractais de poliedros em RA, visite a página:
<p align="center"><a href="../ra.html" target="_blank">https://paulohscwb.github.io/polyhedra2/fractalnonconvex/ra.html</a></p> 
com qualquer navegador com um dispositivo de webcam (smartphone, tablet ou notebook).
<br>O acesso às páginas de RV é feito clicando no círculo azul que aparece em cima de cada marcador.
<p align="center"><img style="border-radius:7px;" alt="Realidade Aumentada para fractais de poliedros" src="../ar/example.jpg" width="85%"></p>
<p align="center"><img src="../ar/fractalnonconvex.gif" alt="Realidade Aumentada para fractais de poliedros" style="max-width: 92%; border-radius:5px;" loading="lazy"/></p>
<hr>
<h3 id="m3d" align="center">Modelos 3D</h3>
 <iframe width="560" height="315" style="max-width:100%" src="https://www.youtube.com/embed/videoseries?list=PLy0I_lGW8HxU-mneUmSsccpRAAwbErHFq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->
<h4>1. Fractal do sólido de Escher</h4>
<a href="../vr/FractalEscher.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/18A.png" class="foto" alt="Fractal do sólido de Escher"></a><img src="../ar/18.png" class="qr">
 <br><br>Aplicando-se o princípio de construção do triângulo de Sierpinski nas 48 faces do sólido de Escher, obtemos um fractal do sólido de Escher. Na primeira ordem de construção do fractal, construímos um novo sólido em 12 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>48</td>
		<td>72</td>
		<td>26</td>
	</tr>
	<tr>
		<td>1</td>
		<td>12</td>
		<td>576</td>
		<td>864</td>
		<td>312</td>
	</tr>
	<tr>
		<td>2</td>
		<td>144</td>
		<td>6912</td>
		<td>10368</td>
		<td>3744</td>
	</tr>
	<tr>
		<td>3</td>
		<td>1728</td>
		<td>82944</td>
		<td>124416</td>
		<td>44928</td>
	</tr>
 </table>
 <hr>
<h4>2. Fractal do pequeno dodecaedro estrelado</h4>
<a href="../vr/FractalSmallStellatedDodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/19A.png" class="foto" alt="Fractal do pequeno dodecaedro estrelado"></a><img src="../ar/19.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch nas 12 faces do pequeno dodecaedro estrelado, obtemos um fractal do pequeno dodecaedro estrelado. Na primeira ordem de construção do fractal, construímos um novo sólido em cada vértice do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>12</td>
		<td>30</td>
		<td>12</td>
	</tr>
	<tr>
		<td>1</td>
		<td>12</td>
		<td>144</td>
		<td>360</td>
		<td>144</td>
	</tr>
	<tr>
		<td>2</td>
		<td>144</td>
		<td>1728</td>
		<td>4320</td>
		<td>1728</td>
	</tr>
	<tr>
		<td>3</td>
		<td>1728</td>
		<td>20736</td>
		<td>51840</td>
		<td>20736</td>
	</tr>
 </table>
 <hr>
<h4>3. Fractal do grande icosaedro</h4>
<a href="../vr/FractalGreatIcosahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/20A.png" class="foto" alt="Fractal do grande icosaedro"></a><img src="../ar/20.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch nas 20 faces do grande icosaedro, obtemos um fractal do grande icosaedro. Na primeira ordem de construção do fractal, construímos um novo sólido em cada vértice do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>20</td>
		<td>30</td>
		<td>12</td>
	</tr>
	<tr>
		<td>1</td>
		<td>12</td>
		<td>240</td>
		<td>360</td>
		<td>144</td>
	</tr>
	<tr>
		<td>2</td>
		<td>144</td>
		<td>2880</td>
		<td>4320</td>
		<td>1728</td>
	</tr>
	<tr>
		<td>3</td>
		<td>1728</td>
		<td>34560</td>
		<td>51840</td>
		<td>20736</td>
	</tr>
 </table>
 <hr>
<h4>4. Fractal do grande dodecaedro</h4>
<a href="../vr/FractalGreatDodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/21A.png" class="foto" alt="Fractal do grande dodecaedro"></a><img src="../ar/21.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch nas 12 faces do grande dodecaedro, obtemos um fractal do grande dodecaedro. Na primeira ordem de construção do fractal, construímos um novo sólido em cada vértice do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>12</td>
		<td>30</td>
		<td>12</td>
	</tr>
	<tr>
		<td>1</td>
		<td>12</td>
		<td>144</td>
		<td>360</td>
		<td>144</td>
	</tr>
	<tr>
		<td>2</td>
		<td>144</td>
		<td>1728</td>
		<td>4320</td>
		<td>1728</td>
	</tr>
	<tr>
		<td>3</td>
		<td>1728</td>
		<td>20736</td>
		<td>51840</td>
		<td>20736</td>
	</tr>
 </table>
 <hr>
<h4>5. Fractal do grande dodecaedro estrelado</h4>
<a href="../vr/FractalGreatStellatedDodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/22A.png" class="foto" alt="Fractal do grande dodecaedro estrelado"></a><img src="../ar/22.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch nas 12 faces do grande dodecaedro estrelado, obtemos um fractal do grande dodecaedro estrelado. Na primeira ordem de construção do fractal, construímos um novo sólido em cada vértice do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>12</td>
		<td>30</td>
		<td>20</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>252</td>
		<td>630</td>
		<td>420</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>5292</td>
		<td>13230</td>
		<td>8820</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>111132</td>
		<td>277830</td>
		<td>185220</td>
	</tr>
 </table>
<hr>
<h4>6. Fractal da dipirâmide pentagrâmica</h4>
<a href="../vr/FractalPentagrammicDipyramid.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/23A.png" class="foto" alt="Fractal da dipirâmide pentagrâmica"></a><img src="../ar/23.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch nas arestas que formam o pentagrama da dipirâmide pentagrâmica, obtemos um fractal da dipirâmide pentagrâmica. Na primeira ordem de construção do fractal, construímos um novo sólido em 5 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2, 3 e 4.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>10</td>
		<td>15</td>
		<td>7</td>
	</tr>
	<tr>
		<td>1</td>
		<td>6</td>
		<td>60</td>
		<td>90</td>
		<td>42</td>
	</tr>
	<tr>
		<td>2</td>
		<td>36</td>
		<td>360</td>
		<td>540</td>
		<td>252</td>
	</tr>
	<tr>
		<td>3</td>
		<td>216</td>
		<td>2160</td>
		<td>3240</td>
		<td>1512</td>
	</tr>
	<tr>
		<td>4</td>
		<td>1296</td>
		<td>12960</td>
		<td>19440</td>
		<td>9072</td>
	</tr>
 </table>
 <hr>
<h4>7. Fractal do icosaedro triâmbico medial</h4>
<a href="../vr/FractalMedialTriambicIcosahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/24A.png" class="foto" alt="Fractal do icosaedro triâmbico medial"></a><img src="../ar/24.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch nas faces do icosaedro triâmbico medial, obtemos um fractal do icosaedro triâmbico medial. Na primeira ordem de construção do fractal, construímos um novo sólido em 12 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>20</td>
		<td>60</td>
		<td>24</td>
	</tr>
	<tr>
		<td>1</td>
		<td>13</td>
		<td>260</td>
		<td>780</td>
		<td>312</td>
	</tr>
	<tr>
		<td>2</td>
		<td>169</td>
		<td>3380</td>
		<td>10140</td>
		<td>4056</td>
	</tr>
	<tr>
		<td>3</td>
		<td>2197</td>
		<td>43940</td>
		<td>131820</td>
		<td>52728</td>
	</tr>
 </table>
 <hr>
<h4>8. Fractal do triacontaedro rômbico medial</h4>
<a href="../vr/FractalMedialRhombicTriacontahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/25A.png" class="foto" alt="Fractal do triacontaedro rômbico medial"></a><img src="../ar/25.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch em 12 faces do triacontaedro rômbico medial, obtemos um fractal do triacontaedro rômbico medial. Na primeira ordem de construção do fractal, construímos um novo sólido em 12 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>30</td>
		<td>60</td>
		<td>24</td>
	</tr>
	<tr>
		<td>1</td>
		<td>13</td>
		<td>390</td>
		<td>780</td>
		<td>312</td>
	</tr>
	<tr>
		<td>2</td>
		<td>169</td>
		<td>5070</td>
		<td>10140</td>
		<td>4056</td>
	</tr>
	<tr>
		<td>3</td>
		<td>2197</td>
		<td>65910</td>
		<td>131820</td>
		<td>52728</td>
	</tr>
 </table>
 <hr>
<h4>9. Fractal do pequeno hexecontaedro ditrigonal dodecacrônico</h4>
<a href="../vr/FractalSmallDitrigonalDodecacronicHexecontahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/26A.png" class="foto" alt="Fractal do pequeno hexecontaedro ditrigonal dodecacrônico"></a><img src="../ar/26.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch em 12 faces do pequeno hexecontaedro ditrigonal dodecacrônico, obtemos um fractal do pequeno hexecontaedro ditrigonal dodecacrônico. Na primeira ordem de construção do fractal, construímos um novo sólido em 12 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>60</td>
		<td>120</td>
		<td>44</td>
	</tr>
	<tr>
		<td>1</td>
		<td>13</td>
		<td>780</td>
		<td>1560</td>
		<td>572</td>
	</tr>
	<tr>
		<td>2</td>
		<td>169</td>
		<td>10140</td>
		<td>20280</td>
		<td>7436</td>
	</tr>
	<tr>
		<td>3</td>
		<td>2197</td>
		<td>131820</td>
		<td>263640</td>
		<td>96668</td>
	</tr>
 </table>
 <hr>
<h4>10. Fractal do pequeno icositetraedro hexacrônico</h4>
<a href="../vr/FractalSmallHexacronicIcositetrahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/27A.png" class="foto" alt="Fractal do pequeno icositetraedro hexacrônico"></a><img src="../ar/27.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch em 6 faces do pequeno icositetraedro hexacrônico, obtemos um fractal do pequeno icositetraedro hexacrônico. Na primeira ordem de construção do fractal, construímos um novo sólido em 6 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>24</td>
		<td>48</td>
		<td>20</td>
	</tr>
	<tr>
		<td>1</td>
		<td>7</td>
		<td>168</td>
		<td>336</td>
		<td>140</td>
	</tr>
	<tr>
		<td>2</td>
		<td>49</td>
		<td>1176</td>
		<td>2352</td>
		<td>980</td>
	</tr>
	<tr>
		<td>3</td>
		<td>343</td>
		<td>8232</td>
		<td>16464</td>
		<td>6860</td>
	</tr>
 </table>
 <p class="topop"><a href="#p1" class="topo">voltar ao topo</a></p>
 <hr>
<h4>11. Fractal do grande octaedro triakis</h4>
<a href="../vr/FractalGreatTriakisOctahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/28A.png" class="foto" alt="Fractal do grande octaedro triakis"></a><img src="../ar/28.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch em 8 faces do grande octaedro triakis, obtemos um fractal do grande octaedro triakis. Na primeira ordem de construção do fractal, construímos um novo sólido em 8 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>24</td>
		<td>36</td>
		<td>14</td>
	</tr>
	<tr>
		<td>1</td>
		<td>9</td>
		<td>216</td>
		<td>324</td>
		<td>126</td>
	</tr>
	<tr>
		<td>2</td>
		<td>81</td>
		<td>1944</td>
		<td>2916</td>
		<td>1134</td>
	</tr>
	<tr>
		<td>3</td>
		<td>729</td>
		<td>17496</td>
		<td>26244</td>
		<td>10216</td>
	</tr>
 </table>
 <hr>
<h4>12. Fractal do grande dodecaedro stellapentakis</h4>
<a href="../vr/FractalGreatStellapentakisDodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/29A.png" class="foto" alt="Fractal do grande dodecaedro stellapentakis"></a><img src="../ar/29.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch em 20 faces do grande dodecaedro stellapentakis, obtemos um fractal do grande dodecaedro stellapentakis. Na primeira ordem de construção do fractal, construímos um novo sólido em 20 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>60</td>
		<td>90</td>
		<td>32</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1260</td>
		<td>1890</td>
		<td>672</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>26460</td>
		<td>39690</td>
		<td>14112</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>555660</td>
		<td>833490</td>
		<td>296352</td>
	</tr>
 </table>
 <hr>
<h4>13. Fractal do grande dodecaedro disdyakis</h4>
<a href="../vr/FractalGreatDisdyakisDodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/30A.png" class="foto" alt="Fractal do grande dodecaedro disdyakis"></a><img src="../ar/30.png" class="qr">
 <br><br>Aplicando-se o princípio de construção da curva de Koch em 8 faces do grande dodecaedro disdyakis, obtemos um fractal do grande dodecaedro disdyakis. Na primeira ordem de construção do fractal, construímos um novo sólido em 8 vértices do poliedro original. Neste exemplo, temos as representações do sólido nas ordens 0, 1, 2 e 3.
 <table>
	<tr>
		<th>ordem</th>
		<th>poliedros</th>
		<th>faces</th>
		<th>arestas</th>
		<th>vértices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>48</td>
		<td>72</td>
		<td>20</td>
	</tr>
	<tr>
		<td>1</td>
		<td>9</td>
		<td>432</td>
		<td>648</td>
		<td>180</td>
	</tr>
	<tr>
		<td>2</td>
		<td>81</td>
		<td>3888</td>
		<td>5832</td>
		<td>1620</td>
	</tr>
	<tr>
		<td>3</td>
		<td>729</td>
		<td>34992</td>
		<td>52488</td>
		<td>14580</td>
	</tr>
 </table>
<p class="topop"><a href="#p1" class="topo">voltar ao topo</a></p>
<hr>

<br><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" loading="lazy"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Non convex polyhedra fractals - Visualization of polyhedra with Augmented Reality and Virtual Reality</span> de <a xmlns:cc="http://creativecommons.org/ns#" href="https://paulohscwb.github.io/polyhedra2/fractalnonconvex/" property="cc:attributionName" rel="cc:attributionURL">Paulo Henrique Siqueira</a> está licenciado com uma Licença <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Atribuição-NãoComercial-SemDerivações 4.0 Internacional</a>.

<h4>Como citar este trabalho:</h4> 
<p>Siqueira, P.H., "Non convex polyhedra fractals - Visualization of polyhedra with Augmented Reality and Virtual Reality". Disponível em: <https://paulohscwb.github.io/polyhedra2/fractalnonconvex/>, Outubro de 2023.</p>
<!--<a target="_blank" href="https://doi.org/10.5281/zenodo.8272770"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.8272770.svg" alt="DOI"></a>-->
<br><br><b>Referências:</b>
<br>Weisstein, Eric W. "Archimedean Solid" From MathWorld-A Wolfram Web Resource. <a href="http://mathworld.wolfram.com/ArchimedeanSolid.html" target="_blank">http://mathworld.wolfram.com/ArchimedeanSolid.html</a>
<br>Weisstein, Eric W. "Platonic Solid" From MathWorld-A Wolfram Web Resource. <a href="http://mathworld.wolfram.com/PlatonicSolid.html" target="_blank">http://mathworld.wolfram.com/PlatonicSolid.html</a>
<br>Weisstein, Eric W. "Archimedean Dual" From MathWorld-A Wolfram Web Resource. <a href="https://mathworld.wolfram.com/ArchimedeanDual.html" target="_blank">https://mathworld.wolfram.com/ArchimedeanDual.html</a>
<br>Weisstein, Eric W. "Uniform Polyhedron." From MathWorld--A Wolfram Web Resource. <a href="https://mathworld.wolfram.com/UniformPolyhedron.html" target="_blank">https://mathworld.wolfram.com/UniformPolyhedron.html</a>
<br>Wikipedia <a href="https://en.wikipedia.org/wiki/Archimedean_solid" target="_blank">https://en.wikipedia.org/wiki/Archimedean_solid</a>
<br>Wikipedia <a href="https://en.wikipedia.org/wiki/en.wikipedia.org/wiki/Platonic_solid" target="_blank">https://en.wikipedia.org/wiki/Platonic_solid</a>
<br>McCooey, David I. "Visual Polyhedra". <a href="http://dmccooey.com/polyhedra/" target="_blank">http://dmccooey.com/polyhedra/</a>