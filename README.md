<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="generator" content="Asciidoctor 2.0.8">
<meta name="author" content="Santa Tecla">
</head>
<body class="book">
<div id="header">
<h1>TicTacToe. <strong>Guión</strong></h1>
<div class="details">
<span id="author" class="author">Santa Tecla</span><br>
<span id="email" class="email"><a href="mailto:parqueNaturalSantaTecla@gmail.com">usantatecla@gmail.com</a></span><br>
<span id="revnumber">version 0.0.1</span>
</div>
</div>
<div id="content">
<div id="preamble">
<div class="sectionbody">
<h2 id="arquitectura">Modelo del dominio</h2>
<div class="sect2">
<h3 id="arquitectura">Vocabulario</h3>
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/estadoInicialTicTacToe.svg" alt="estadoInicialTicTacToe" width="1000" height="600">
</div>
</div>
</div>
<div class="sect2">
<h3 id="arquitectura">Estado Inicial</h3>
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/estadoInicialTicTacToe.svg" alt="estadoInicialTicTacToe" width="1000" height="600">
</div>
</div>
</div>
<div class="sect2">
<h3 id="arquitectura">Estado Final. Objetivo TicTacToe en 3ª fila</h3>
<div class="imageblock">
<div class="content">
<img src="build/docs/asciidoc/images/estadoFinalTicTacToe.svg" alt="estadoFinalTicTacToe" width="1000" height="600">
</div>
</div>
</div>
<table class="tableblock frame-all grid-all stretch">
<colgroup>
<col style="width: 20%;">
<col style="width: 20%;">
<col style="width: 60%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Tema</th>
<th class="tableblock halign-left valign-top">Requisitos</th>
<th class="tableblock halign-left valign-top">Incremento</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red"><strong>Modelo del Dominio</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">TicTacToe. Requisitos. Versión 1. <strong>Básica</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top" ><div class="content"><div class="paragraph">
<p><span class="red">Versión básica, con interfaz de texto desde la consola, distribución Standalone y sin persistencia de los datos de la aplicación</span></p>
</div></div></td>
</tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="blue"><strong>Diseño Modular y Orientado a Objetos</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="blue">TicTacToe. Requisitos. Versión 2. <strong>Gráficos</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">Se añade la interfaz gráfica. Con este requisito funcional se consigue que el usuario pueda tener una interfaz más agradable que una consola de texto</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top" rowspan="6"><div class="content"><div class="paragraph">
<p><strong>Patrones de Diseño</strong></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="green">TicTacToe. Requisitos. Versión 3. <strong>UndoRedo</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">Se implementa la nueva funcionalidad de undo/redo, que permite deshacer y rehacer los estados del programa</span></p>
</div></div></td>
</tr>
<tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="yellow">TicTacToe. Requisitos. Versión 4. <strong>ClienteServidor</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">Distribución de la aplicación en dos partes separadas y comunicadas. La parte de Cliente para la interfaz propia que usa el usuario y el Servidor dedicado al manejo y gestión de los datos</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="purple">TicTacToe. Requisitos. Versión 5. <strong>Ficheros</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">Poder guardar el estado del programa. Se usan ficheros para el almacenamiento de estos datos y su recuperación</span></p>
</div></div></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="lime">TicTacToe. Requisitos. Versión 6. <strong>BasesDatos</strong></span></p>
</div></div></td>
<td class="tableblock halign-left valign-top"><div class="content"><div class="paragraph">
<p><span class="red">Se agrega la posibilidad de guardado en base de datos del estado del programa</span></p>
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
Last updated 2020-07-27 23:15:00 +0200
</div>
</div>
</html>