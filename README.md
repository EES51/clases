<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clases - Escuela Secundaria N°51 Azucena Villaflor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        h1 {
            color: #0056b3;
            text-align: center;
            margin-bottom: 30px;
        }
        .school-menu {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 20px 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .year-section {
            margin-bottom: 25px;
            border-bottom: 1px solid #eee;
            padding-bottom: 15px;
        }
        .year-section:last-child {
            border-bottom: none;
        }
        .year-section h2 {
            color: #007bff;
            margin-top: 0;
            margin-bottom: 15px;
            font-size: 1.8em;
            cursor: pointer; /* Para indicar que es clickeable si luego se usa JS */
            display: flex; /* Para alinear el icono y el texto */
            align-items: center;
        }
        .year-section h2::before {
            content: "▶"; /* Icono de flecha para expandir/contraer si se usa JS */
            display: inline-block;
            transition: transform 0.2s;
            margin-right: 10px;
        }
        .year-section h2.expanded::before {
            transform: rotate(90deg);
        }
        .subject-list {
            list-style: none;
            padding-left: 0;
            display: none; /* Oculto por defecto, se mostrará con JS */
        }
        .year-section h2.expanded + .subject-list {
            display: block; /* Mostrar cuando el año está expandido */
        }

        .subject-list li {
            margin-bottom: 10px;
        }
        .subject-list li strong {
            color: #555;
            display: block;
            margin-bottom: 5px;
            font-size: 1.1em;
        }
        .class-list {
            list-style: none;
            padding-left: 20px;
        }
        .class-list li {
            margin-bottom: 3px;
        }
        .class-list a {
            text-decoration: none;
            color: #28a745;
            transition: color 0.2s;
        }
        .class-list a:hover {
            color: #1e7e34;
            text-decoration: underline;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            body {
                margin: 10px;
            }
            .school-menu {
                padding: 15px;
            }
            h1 {
                font-size: 1.5em;
            }
            .year-section h2 {
                font-size: 1.4em;
            }
            .subject-list li strong {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

    <h1>ESCUELA SECUNDARIA N°51 AZUCENA VILLAFLOR</h1>

    <div class="school-menu">
        <div class="year-section">
            <h2 id="year1">1° Año</h2>
            <ul class="subject-list" aria-labelledby="year1">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Ciencias Sociales</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/cs_sociales/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/cs_sociales/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Ciencias Naturales</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/cs_naturales/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/cs_naturales/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Artística</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/artistica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/artistica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/artistica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/artistica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/artistica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/artistica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/artistica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/artistica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/artistica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/artistica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/ed_fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/ed_fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Tecnología</strong>
                    <ul class="class-list">
                        <li><a href="clases/1ro/tecnologia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/1ro/tecnologia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/1ro/tecnologia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/1ro/tecnologia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/1ro/tecnologia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/1ro/tecnologia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/1ro/tecnologia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/1ro/tecnologia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/1ro/tecnologia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/1ro/tecnologia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year2">2° Año</h2>
            <ul class="subject-list" aria-labelledby="year2">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Historia</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/historia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/historia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/historia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/historia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/historia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/historia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/historia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/historia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/historia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/historia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Geografía</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/geografia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/geografia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/geografia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/geografia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/geografia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/geografia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/geografia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/geografia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/geografia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/geografia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Artística</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/artistica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/artistica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/artistica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/artistica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/artistica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/artistica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/artistica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/artistica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/artistica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/artistica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/ed_fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/ed_fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/ed_fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/ed_fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/ed_fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/ed_fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/ed_fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/ed_fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/ed_fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/ed_fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Tecnología</strong>
                    <ul class="class-list">
                        <li><a href="clases/2do/tecnologia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/2do/tecnologia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/2do/tecnologia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/2do/tecnologia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/2do/tecnologia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/2do/tecnologia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/2do/tecnologia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/2do/tecnologia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/2do/tecnologia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/2do/tecnologia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year3">3° Año</h2>
            <ul class="subject-list" aria-labelledby="year3">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Historia</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/historia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/historia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/historia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/historia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/historia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/historia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/historia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/historia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/historia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/historia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Geografía</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/geografia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/geografia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/geografia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/geografia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/geografia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/geografia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/geografia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/geografia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/geografia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/geografia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Cívica</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/civica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/civica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/civica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/civica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/civica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/civica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/civica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/civica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/civica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/civica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Artística</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/artistica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/artistica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/artistica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/artistica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/artistica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/artistica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/artistica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/artistica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/artistica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/artistica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/ed_fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/ed_fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/3ro/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/3ro/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/3ro/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/3ro/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/3ro/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/3ro/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/3ro/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/3ro/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/3ro/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/3ro/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year4n">4° Año (Noche)</h2>
            <ul class="subject-list" aria-labelledby="year4n">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Química</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/quimica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/quimica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/quimica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/quimica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/quimica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/quimica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/quimica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/quimica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/quimica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/quimica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Biología</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/biologia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/biologia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/biologia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/biologia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/biologia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/biologia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/biologia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/biologia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/biologia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/biologia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Historia</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/historia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/historia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/historia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/historia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/historia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/historia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/historia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/historia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/historia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/historia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Geografía</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/geografia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/geografia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/geografia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/geografia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/geografia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/geografia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/geografia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/geografia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/geografia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/geografia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/4n/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4n/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4n/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4n/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4n/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4n/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4n/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4n/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4n/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4n/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year4s">4° Año (Sur)</h2>
            <ul class="subject-list" aria-labelledby="year4s">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Química</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/quimica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/quimica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/quimica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/quimica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/quimica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/quimica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/quimica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/quimica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/quimica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/quimica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Biología</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/biologia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/biologia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/biologia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/biologia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/biologia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/biologia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/biologia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/biologia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/biologia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/biologia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Historia</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/historia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/historia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/historia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/historia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/historia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/historia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/historia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/historia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/historia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/historia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Geografía</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/geografia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/geografia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/geografia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/geografia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/geografia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/geografia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/geografia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/geografia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/geografia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/geografia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/4s/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/4s/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/4s/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/4s/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/4s/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/4s/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/4s/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/4s/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/4s/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/4s/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year5n">5° Año (Noche)</h2>
            <ul class="subject-list" aria-labelledby="year5n">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Filosofía</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/filosofia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/filosofia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/filosofia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/filosofia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/filosofia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/filosofia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/filosofia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/filosofia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/filosofia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/filosofia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Ciudadanía y Trabajo</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/ciudadania/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/ciudadania/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/ciudadania/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/ciudadania/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/ciudadania/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/ciudadania/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/ciudadania/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/ciudadania/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/ciudadania/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/ciudadania/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Artística</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/artistica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/artistica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/artistica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/artistica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/artistica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/artistica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/artistica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/artistica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/artistica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/artistica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/ed_fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/ed_fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/ed_fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/ed_fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/ed_fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/ed_fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/ed_fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/ed_fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/ed_fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/ed_fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Economía</strong>
                    <ul class="class-list">
                        <li><a href="clases/5n/economia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5n/economia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5n/economia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5n/economia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5n/economia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5n/economia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5n/economia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5n/economia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5n/economia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5n/economia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year5s">5° Año (Sur)</h2>
            <ul class="subject-list" aria-labelledby="year5s">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Filosofía</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/filosofia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/filosofia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/filosofia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/filosofia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/filosofia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/filosofia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/filosofia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/filosofia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/filosofia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/filosofia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Ciudadanía y Trabajo</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/ciudadania/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/ciudadania/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/ciudadania/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/ciudadania/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/ciudadania/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/ciudadania/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/ciudadania/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/ciudadania/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/ciudadania/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/ciudadania/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Artística</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/artistica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/artistica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/artistica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/artistica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/artistica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/artistica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/artistica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/artistica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/artistica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/artistica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/ed_fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/ed_fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/ed_fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/ed_fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/ed_fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/ed_fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/ed_fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/ed_fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/ed_fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/ed_fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Economía</strong>
                    <ul class="class-list">
                        <li><a href="clases/5s/economia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/5s/economia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/5s/economia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/5s/economia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/5s/economia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/5s/economia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/5s/economia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/5s/economia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/5s/economia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/5s/economia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year6n">6° Año (Noche)</h2>
            <ul class="subject-list" aria-labelledby="year6n">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Historia</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/historia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/historia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/historia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/historia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/historia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/historia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/historia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/historia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/historia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/historia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Geografía</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/geografia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/geografia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/geografia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/geografia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/geografia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/geografia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/geografia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/geografia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/geografia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/geografia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Cívica</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/civica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/civica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/civica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/civica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/civica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/civica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/civica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/civica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/civica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/civica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Artística</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/artistica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/artistica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/artistica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/artistica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/artistica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/artistica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/artistica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/artistica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/artistica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/artistica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/ed_fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/ed_fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/ed_fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/ed_fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/ed_fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/ed_fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/ed_fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/ed_fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/ed_fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/ed_fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/6n/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6n/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6n/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6n/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6n/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6n/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6n/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6n/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6n/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6n/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="year-section">
            <h2 id="year6s">6° Año (Sur)</h2>
            <ul class="subject-list" aria-labelledby="year6s">
                <li>
                    <strong>Matemática</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/matematica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/matematica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/matematica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/matematica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/matematica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/matematica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/matematica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/matematica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/matematica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/matematica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Lengua y Literatura</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/lengua/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/lengua/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/lengua/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/lengua/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/lengua/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/lengua/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/lengua/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/lengua/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/lengua/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/lengua/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Historia</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/historia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/historia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/historia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/historia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/historia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/historia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/historia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/historia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/historia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/historia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Geografía</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/geografia/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/geografia/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/geografia/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/geografia/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/geografia/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/geografia/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/geografia/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/geografia/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/geografia/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/geografia/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Cívica</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/civica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/civica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/civica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/civica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/civica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/civica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/civica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/civica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/civica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/civica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Artística</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/artistica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/artistica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/artistica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/artistica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/artistica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/artistica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/artistica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/artistica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/artistica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/artistica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Educación Física</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/ed_fisica/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/ed_fisica/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/ed_fisica/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/ed_fisica/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/ed_fisica/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/ed_fisica/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/ed_fisica/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/ed_fisica/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/ed_fisica/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/ed_fisica/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
                <li>
                    <strong>Inglés</strong>
                    <ul class="class-list">
                        <li><a href="clases/6s/ingles/clase1.html">Clase 1</a></li>
                        <li><a href="clases/6s/ingles/clase2.html">Clase 2</a></li>
                        <li><a href="clases/6s/ingles/clase3.html">Clase 3</a></li>
                        <li><a href="clases/6s/ingles/clase4.html">Clase 4</a></li>
                        <li><a href="clases/6s/ingles/clase5.html">Clase 5</a></li>
                        <li><a href="clases/6s/ingles/clase6.html">Clase 6</a></li>
                        <li><a href="clases/6s/ingles/clase7.html">Clase 7</a></li>
                        <li><a href="clases/6s/ingles/clase8.html">Clase 8</a></li>
                        <li><a href="clases/6s/ingles/clase9.html">Clase 9</a></li>
                        <li><a href="clases/6s/ingles/clase10.html">Clase 10</a></li>
                    </ul>
                </li>
            </ul>
        </div>
    </div>

    <script>
        // JavaScript para expandir/contraer las secciones de cada año
        document.querySelectorAll('.year-section h2').forEach(header => {
            header.addEventListener('click', () => {
                header.classList.toggle('expanded');
                const subjectList = header.nextElementSibling;
                if (subjectList.style.display === "block") {
                    subjectList.style.display = "none";
                } else {
                    subjectList.style.display = "block";
                }
            });
        });
    </script>

</body>
</html>
