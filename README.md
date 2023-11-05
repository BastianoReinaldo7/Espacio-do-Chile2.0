<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Espacio Do Chile</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <style>
        /* ROBOTOMONO-MEDIUM */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-Medium.ttf') format('truetype');
            font-weight: 500;
            /* Valor típico para medium */
            font-style: normal;
        }

        /* ROBOTOMONO-BOLD */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-Bold.ttf') format('truetype');
            font-weight: bold;
            font-style: normal;
        }

        /* ROBOTOMONO-BOLDITALIC */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-BoldItalic.ttf') format('truetype');
            font-weight: bold;
            font-style: italic;
        }

        /* ROBOTOMONO-EXTRALIGHT */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-ExtraLight.ttf') format('truetype');
            font-weight: 200;
            /* Valor típico para extralight */
            font-style: normal;
        }

        /* ROBOTOMONO-EXTRALIGHTITALIC */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-ExtraLightItalic.ttf') format('truetype');
            font-weight: 200;
            /* Valor típico para extralight */
            font-style: italic;
        }

        /* ROBOTOMONO-ITALIC */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-Italic.ttf') format('truetype');
            font-weight: normal;
            font-style: italic;
        }

        /* ROBOTOMONO-LIGHT */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-Light.ttf') format('truetype');
            font-weight: 300;
            /* Valor típico para light */
            font-style: normal;
        }

        /* ROBOTOMONO-LIGHTITALIC */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-LightItalic.ttf') format('truetype');
            font-weight: 300;
            /* Valor típico para light */
            font-style: italic;
        }

        /* ROBOTOMONO-MEDIUMITALIC */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-MediumItalic.ttf') format('truetype');
            font-weight: 500;
            /* Valor típico para medium */
            font-style: italic;
        }

        /* ROBOTOMONO-REGULAR */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-Regular.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        /* ROBOTOMONO-SEMIBOLD */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-SemiBold.ttf') format('truetype');
            font-weight: 600;
            /* Valor típico para semibold */
            font-style: normal;
        }

        /* ROBOTOMONO-SEMIBOLDITALIC */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-SemiBoldItalic.ttf') format('truetype');
            font-weight: 600;
            /* Valor típico para semibold */
            font-style: italic;
        }

        /* ROBOTOMONO-THIN */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-Thin.ttf') format('truetype');
            font-weight: 100;
            /* Valor típico para thin */
            font-style: normal;
        }

        /* ROBOTOMONO-THINITALIC */
        @font-face {
            font-family: 'Roboto Mono';
            src: url('./assets/fonts/Roboto_Mono/static/RobotoMono-ThinItalic.ttf') format('truetype');
            font-weight: 100;
            /* Valor típico para thin */
            font-style: italic;
        }
    </style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">

</head>

<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-dark px-3">

        <a class="navbar-brand p-0 d-flex" href="./LandingTurista.html">
            <img src="./assets/img/EspacioDoChile-Isotipo.png" alt="Logo" height="70">
            <span class="navbar-text mx-auto text-light w-100 text-center align-self-center" style="font-size: larger;">
                Lugares inolvidables, Alojamientos ideales.
            </span>
        </a>
        <div class="collapse navbar-collapse mr-auto d-flex justify-content-end" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">Registrarse</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">
                        <i class="fa fa-user-circle"></i> Usuario
                    </a>
                </li>
            </ul>
        </div>
    </nav>

    <div class="container mt-5">
        <div class="row justify-content-center">
            <div class="col-md-6">
                <div class="card">
                    <div class="card-header">
                        <img src="./assets/img/EspacioDoChile-Isotipo.png" alt="Logo" class="img-fluid" height="100">
                    </div>
                    <div class="card-body">
                        <form>
                            <div class="form-group">
                                <label for="usuario">Usuario</label>
                                <input type="text" class="form-control" id="usuario" placeholder="Ingresa tu usuario">
                            </div>
                            <div class="form-group">
                                <label for="contrasena">Contraseña</label>
                                <input type="password" class="form-control" id="contrasena"
                                    placeholder="Ingresa tu contraseña">
                            </div>
                            <a href="./LandingTurista.html"><button type="button" class="btn btn-primary">Iniciar
                                    Sesión</button></a>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Bootstrap JS y dependencias (jQuery, Popper.js) -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>
    <!-- Font Awesome (para el icono de usuario) -->
    <script src="https://kit.fontawesome.com/your-font-awesome-kit.js"></script>


</body>

</html>
