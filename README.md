<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="generator" content="Asciidoctor 2.0.8">
<meta name="author" content="Universo Santa Tecla">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:300,300italic,400,400italic,600,600italic%7CNoto+Serif:400,400italic,700,700italic%7CDroid+Sans+Mono:400,700">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body class="book">
<div id="header">
<h1>TicTacToe</h1>
<div class="details">
<span id="author" class="author">Universo Santa Tecla</span><br>
<span id="email" class="email"><a href="mailto:USantaTecla@gmail.com">USantaTecla@gmail.com</a></span><br>
<span id="revnumber">version 0.0.1</span>
</div>
<div id="toc" class="toc">
<div id="toctitle">Table of Contents</div>
<ul class="sectlevel1">
<li><a href="#modelo-del-dominio">Modelo del Dominio</a>
<ul class="sectlevel2">
<li><a href="#vocabulario">Vocabulario</a></li>
<li><a href="#estado-inicial">Estado Inicial</a></li>
<li><a href="#estado-final-objetivo-tictactoe-en-3ª-fila">Estado Final. Objetivo TicTacToe en 3ª fila</a></li>
<li><a href="#instrucciones">Instrucciones</a></li>
</ul>
</li>
<li><a href="#versión">Versión</a></li>
</ul>
</div>
</div>
<div id="content">
<div class="sect1">
<h2 id="modelo-del-dominio">Modelo del Dominio</h2>
<div class="sectionbody">
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/TicTacToe.png" alt="TicTacToe">
</div>
</div>
<div class="sect2">
<h3 id="vocabulario">Vocabulario</h3>
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/ticTacToeClases.svg" alt="ticTacToeClases" width="1130" height="963">
</div>
</div>
</div>
<div class="sect2">
<h3 id="estado-inicial">Estado Inicial</h3>
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/estadoInicialTicTacToe.svg" alt="estadoInicialTicTacToe" width="1094" height="492">
</div>
</div>
</div>
<div class="sect2">
<h3 id="estado-final-objetivo-tictactoe-en-3ª-fila">Estado Final. Objetivo TicTacToe en 3ª fila</h3>
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/estadoFinalTicTacToe.svg" alt="estadoFinalTicTacToe" width="1131" height="587">
</div>
</div>
</div>
<div class="sect2">
<h3 id="instrucciones">Instrucciones</h3>
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/instructions.svg" alt="instructions" width="371" height="764">
</div>
</div>
</div>
</div>
</div>
<div class="sect1">
<h2 id="versión">Versión</h2>
<div class="sectionbody">
<table class="tableblock frame-all grid-all stretch">
<colgroup>
<col style="width: 20%;">
<col style="width: 80%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Versión</th>
<th class="tableblock halign-left valign-top">Descripción</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">TicTacToe. Requisitos. Versión 1. <strong>Básica</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">Juego de las 3 en raya con interfaz de consola y con casos de uso: arrancar, jugar y continuar**</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="blue">TicTacToe. Requisitos. Versión 2. <strong>Gráficos</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">Añadiendo interfaz gráfica</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="green">TicTacToe. Requisitos. Versión 3. <strong>UndoRedo</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="green">Añadiendo funcionalidad con deshacer y rehacer jugadas</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="yellow">TicTacToe. Requisitos. Versión 4. <strong>ClienteServidor</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="yellow">Añadiendo distribución cliente/servidor</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="purple">TicTacToe. Requisitos. Versión 5. <strong>Ficheros</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="purple">Añadiendo funcionalidad con persistencia de ficheros</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="lime">TicTacToe. Requisitos. Versión 6. <strong>BasesDatos</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="lime">Adaptando persistencia con bases de datos</span></p>
</div></div></td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
<div id="footer">
<div id="footer-text">
Version 0.0.1<br>
Last updated 2020-10-04 18:05:40 +0200
</div>
</div>
</html>