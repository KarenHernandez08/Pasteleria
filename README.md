# Está página esta creada en HTML

## HTML

HyperText Markun Languaje, es un lenguaje de hipertexto para poder hacer estructuras de                  páginas 

## Etiquetas básicas

```html
<p>Este es un parrafo </p>
<h1>TITULO MAS IMPORTANTE</h1>
<h6>Titulo menos importante</h6>
<p>Este es un parrafo </p>
<br> salto de línea
<!-- comentario -->
 <a href="Aquí.va.el.link" target="blank">Texto</a>

 <!-- width es la anchura y el height es la altura-->
 <img src="aquí va el link de la imagen" alt="Texto alternativo" width="350px" height="350px">

 <!-- tablas -->
<table>
        <tr>
            <th>Compañía</th>
            <th>Contacto</th>
            <th>País</th>
        </tr>
        <tr>
            <td>Alfreds Futterkiste</td>
            <td>Maria Anders</td>
            <td>Germany</td>
        </tr>
        <tr>
            <td>Centro comercial Moctezuma</td>
            <td>Francisco Chang</td>
            <td>Mexico</td>
        </tr>
    </table>
     
 <!-- Listas -->
  <ul>
        <li>Café</li>
        <li>Arroz</li>
        <li>leche</li>
        <li>huevos</li>
    </ul>

    <ol>
        <li>Alumno1</li>
        <li>Alumno2</li>
        <li>Alumno3</li>
    </ol>

    <dl>
        <dt>Enchiladas</dt>
        <dd>- Tortilla frita con salsa, rellena de pollo</dd>
        <dt>Molletes</dt>
        <dd>- Bolillo con frijoles y queso</dd>

    </dl>

```
![](https://github.com/KarenHernandez08/Pasteleria/blob/main/imagenes/tablas.PNG)

## Elementos compuestos 

```html
<!-- Labels / Etiquetas -->
    <label for="Input1"> Ejemplo de Input de Texto</label>
    <br>
    <!-- Entradas / Inputs -->
    <input type="text" id="Input1" name="Input1">
    <br><br>

    <hr>
    <!-- Tipos de Inputs -->
    <h2>Input De Texto</h2>
    <label for="correo1">Input de Correo</label><br>
    <input type="email" id="correo1" name="correo1"><br><br>
    
    <label for="numero1">Input de número</label><br>
    <input type="number" id="numero1" name="numero1"><br><br>
    
    <label for="psw1">Input de Password</label><br>
    <input type="password" id="psw1" name="psw1"><br><br>
    
    <label for="tel1">Input de Teléfono</label><br>
    <input type="tel" id="tel1" name="tel1" maxlength="10"><br><br>
    
    <label for="url1">Input de URL</label><br>
    <input type="url" id="url1" name="url1"><br><br>

    <hr>

    <h2>Input de selección multiple</h2><br>
    <input type="checkbox" id="topping1" name="topping1" value="Cebolla">
    <label for="topping1">Tacos con Cebolla</label><br>
    <input type="checkbox" id="topping2" name="topping2" value="Cilantro">
    <label for="topping2">Tacos con Cilantro</label><br>
    <input type="checkbox" id="topping3" name="topping3" value="Salsa">
    <label for="topping3">Tacos con Salsa</label><br><br>
    
    <h2>Input de selección única</h2><br>
    <input type="radio" id="roja" name="salsas" value="Roja">
    <label for="roja">Roja</label><br>
    <input type="radio" id="verde" name="salsas" value="Verde">
    <label for="verde">Verde</label><br>
    <input type="radio" id="guacamole" name="salsas" value="Guacamole">
    <label for="guacamole">Guacamole</label><br><br>

    <h2>Select</h2>
    <label for="tacos">De que la orden</label>
    <select id="tacos" name="tacos">
        <option value="suadero">Suadero</option>
        <option value="pastor">Pastor</option>
        <option value="campechanos">Campechanos</option>
        <option value="tripa">Tripa</option>
    </select>
    
    <h2>Select con Input</h2>
    <label for="refresco">Elige tu refresco favorito</label><br>
    <input list="refresco">
    <datalist id="refresco">
        <option value="Coca-Cola">
        <option value="Manzana">
        <option value="Naranja">
        <option value="Mango">
        <option value="Guayaba">
    </datalist>
    <br><br>

    <hr>
    
    <h2>Input de Fecha</h2><br>
    <input type="date" id="fecha1" name="fecha1"><br>
    <input type="datetime-local" id="fecha2" name="fecha2"><br>
    <input type="week" id="fecha3" name="fecha3"><br>
    <input type="time" id="fecha4" name="fecha4"><br>
    <input type="month" id="fecha5" name="fecha5"><br><br>
    
    <hr>

    <h2>Input de Fecha</h2><br>
    <input type="date" id="fecha1" name="fecha1"><br>
    <input type="datetime-local" id="fecha2" name="fecha2"><br>
    <input type="week" id="fecha3" name="fecha3"><br>
    <input type="time" id="fecha4" name="fecha4"><br>
    <input type="month" id="fecha5" name="fecha5"><br><br>
    
    <hr>
    
    <h2>Input de archivo</h2><br>
    <input type="file" id="archivo1" name="archivo1" multiple><br><br>
    
    <h2>Input de Color</h2><br>
    <input type="color" id="color1" name="color1"><br><br>
    
    <h2>Input de Rango</h2>
    <label for="vol">Volumen (entre 0 y 50):</label><br>
    <input type="range" id="vol" name="vol" min="0" max="50"><br>
    
    <hr>
    
    <h2>Input de botón</h2>
    <input type="reset"><br>
    <input type="submit"><br>
    <input type="button" id="boton1" name="boton1" value="Botón 1" onclick="alert('Bienvenidos');"><br><br>
    
    <hr>
    <!-- Formularios -->
    <h2>Ejemplo de Formulario</h2>
    <form action="/accion.js" id="form1" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre"><br><br>
        <input type="submit" value="Submit">
        <input type="reset">
    </form>
    
    <label for="apellido">Apellido:</label>
    <input type="text" id="apellido" name="apellido" form="form1">
```