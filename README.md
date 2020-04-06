<!DOCTYPE html>
<html lang="es">

<head>
    <script>
        (function(i, s, o, g, r, a, m) {
            i['GoogleAnalyticsObject'] = r;
            i[r] = i[r] || function() {
                (i[r].q = i[r].q || []).push(arguments)
            }, i[r].l = 1 * new Date();
            a = s.createElement(o),
                m = s.getElementsByTagName(o)[0];
            a.async = 1;
            a.src = g;
            m.parentNode.insertBefore(a, m)
        })(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga');
        ga('create', 'UA-141534999-2', 'auto', 'instancia');
        ga('instancia.send', 'pageview');
    </script>

    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- CSRF Token -->
    <meta name="csrf-token" content="tBkk0b2ZDq8kJ1WkMbZynLdAAMG2Bjyp7MKCWVPq">

    <title>Comisaria Virtual</title>
    <meta name="description" content="Simple">
    <meta name="keywords" content="Simple">

    <!-- Styles -->
    <link href="https://comisariavirtual.cl/css/app.css " rel="stylesheet">

    <meta name="google" content="notranslate" />

    <!-- fav and touch icons -->
    <link rel="shortcut icon" href="https://comisariavirtual.cl/logos/logocarabineroschile.png">

    <style type="text/css">
        &quot;
        a.nav-link:hover {
            border-radius: 4px;
            color: #ffffff;
            background-color: #000000
        }
        
        .nav-item.login.btn-white a.nav-link {
            color: #ffffff;
            -webkit-transition: all .2s ease;
            transition: all .2s ease;
            background-color: #007328;
        }
        
        .card .card-header.draft {
            color: #000000;
            background: #ffffff;
        }
        
        .card a.card-footer {
            border: none;
            color: #0054abfont-size: 16px;
            text-align: left;
            background-color: #ffffff;
        }
        
        .simple-list-menu a.list-group-item.active,
        .simple-list-menu a.list-group-item:hover {
            background-color: #007328;
            color: #ffffff;
        }
        
        .btn-danger {
            color: #ffffff;
            background-color: #007328;
            border-color: #007328;
        }
        
        .btn-danger:hover {
            color: #ffffff;
            background-color: #000000;
            border-color: #000000;
        }
        
        .btn-light {
            color: #ffffff;
            background-color: #007328;
            border-color: #007328;
        }
        
        .btn-light:hover {
            color: #ffffff;
            background-color: #000000;
            border-color: #000000;
        }
        
        ul.steps li.active {
            border-bottom: 8px solid #007328;
        }
        
        &quot;
    </style>

</head>

<body>
    <div id="app">
        <nav class="navbar navbar-expand-lg navbar-light bgcarab">
            <div class="container">
                <a class="" href="https://comisariavirtual.cl">
                    <div class="media">
                        <img class="align-self-center mr-3 logo" src="https://comisariavirtual.cl/logos/logo28.png" alt="COMISARÍA VIRTUAL" />
                        <div class="media-body align-self-center name-institution" style="color: #007328;">
                            <!--Cambio Color nombre institucion-->
                            <h5 style="color: #007328;" class="mt-1">PROCESEMOS</h5>
                            <p></p>
                        </div>
                    </div>
                </a>

                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                    <ul class="navbar-nav mt-2">
                        <li class="nav-item login-default mr-3">
                            <a href="https://comisariavirtual.cl/login" class="nav-link">
                            Ingreso funcionarios
                        </a>
                        </li>
                        <li class="nav-item login">
                            <a href="https://comisariavirtual.cl/login/claveunica" class="nav-link">
                                <span class="icon-claveunica"></span> Ingresar con Claveúnica
                            </a>
                        </li>
                    </ul>

                    <ul class="simple-list-menu mt-1 list-group d-block d-sm-none">
                        <a class="list-group-item list-group-item-action  active" href="https://comisariavirtual.cl">
                            <i class="material-icons">insert_drive_file</i> Iniciar trámite
                        </a>

                    </ul>
                </div>

            </div>
        </nav>
        <div class="main-container container pb-5">
            <h1 class="title">Listado de trámites disponibles</h1>

            <hr>
            <br>

            <div class="row">
                <div class="col-sm-12">
                    <section id="simple-destacados">
                        <div class="section-header">
                            <h2>Trámites destacados</h2>
                        </div>
                        <div class="row">
                            <div class="col-md-4 item">
                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/file-1.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Información Importante: Salvoconducto Colectivo Empresas Básicas
                                                </p>
                                                <p></p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/42" class="card-footer ">
                                                    Iniciar
                                                <span>&#8594;</span>
                    </a>
                                </div>
                                <!-- fin div card -->
                            </div>
                            <div class="col-md-4 item">
                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/chat.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Iniciar Permisos temporales SIN ClaveÚnica
                                                </p>
                                                <p></p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/49" class="card-footer ">
                                                    Iniciar
                                                <span>&#8594;</span>
                    </a>
                                </div>
                                <!-- fin div card -->
                            </div>
                        </div>
                    </section>

                    <section id="simple-categorias">
                        <div class="section-header">
                            <h2>Categorías</h2>
                        </div>
                        <div class="row">
                            <div class="col-lg-3 col-md-6 item">
                                <a href="https://comisariavirtual.cl/home/procesos/2">
                                    <div class="card text-center">
                                        <div class="card-body">
                                            <div class="media">
                                                <i class="icon-archivo"></i>
                                                <div class="media-body">
                                                    <p class="card-text">
                                                        Constancias
                                                        <font size="3">
                                            <br/>Permite realizar una certificación de un hecho que afecta a una persona
                                        </font>
                                                    </p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </a>
                            </div>
                            <div class="col-lg-3 col-md-6 item">
                                <a href="https://comisariavirtual.cl/home/procesos/3">
                                    <div class="card text-center">
                                        <div class="card-body">
                                            <div class="media">
                                                <i class="icon-archivo"></i>
                                                <div class="media-body">
                                                    <p class="card-text">
                                                        Permisos Temporales y Salvoconductos
                                                        <font size="3">
                                            <br/>Autorización de circulación temporal por Estado de Excepción de Catástrofe
                                        </font>
                                                    </p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </section>

                    <section id="simple-destacados">
                        <div class="section-header">
                            <h2>Otros trámites</h2>
                        </div>
                        <div class="row">
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/heart.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    01 Permiso Temporal Individual - Asistencia a establecimientos de salud
                                                </p>
                                                <p>Autorizaciones temporales para asistencia a centros, servicios y establecimientos de Salud por hora concertada con anterioridad o para efectuar el proceso de vacunación. Podrá incorporar a un acompañante inscribiéndolo con nombre completo y RUT. Permiso con vigencia por 12 horas.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/71" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/shopping-cart.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    02 Permiso Temporal Individual - Compras insumos básicos
                                                </p>
                                                <p>Autorizaciones temporales para asistir a farmacias, supermercados, mercados y/o lugares de venta de insumos básicos, ya sea para la compra de alimentos, medicamentos y/o insumos básicos. Permiso con vigencia por 04 horas. Máximo 02 permisos a la semana. No válido en horario de toque de queda.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/68" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/favorites.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    03 Permiso Temporal Individual - Salida de personas con espectro autista u otra discapacidad mental
                                                </p>
                                                <p>Autorizaciones temporales para realizar salidas con personas que presentan trastornos del espectro autista u otra discapacidad mental. El cuidador o acompañante deberá solicitar el permiso. Será válido por 02 horas desde su emisión.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/75" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/map-location.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    04 Permiso Temporal Individual - Paseo de mascotas
                                                </p>
                                                <p>Autorizaciones temporales para pasear a mascotas o animales que estén bajo su cuidado, con desplazamiento reducidos dentro de las dos cuadras a la redonda del domicilio o residencia. Permiso con vigencia por 30 minutos, con un máximo de 02 veces al día. No será válido en horario de toque de queda.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/67" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/money.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    05 Permiso Temporal Individual - Pago de Servicios Básicos
                                                </p>
                                                <p>Autorizaciones temporales para realizar pagos, gestiones en Bancos, Cooperativas de Ahorro y Crédito u otras Instituciones Financieras, servicios básicos, gestiones en Notarías y/o cobros de pensiones. Permiso con vigencia por 04 horas, con un máximo de 02 permisos a la semana. No será válido en horario de toque de queda.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/65" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/house.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    06 Permiso Temporal Individual - Retorno a residencia habitual
                                                </p>
                                                <p>Autorizaciones temporales para retornar al lugar de residencia habitual. Este permiso tendrá una validez de 24 horas. Deberá realizar CUARENTENA OBLIGATORIA por 14 DÍAS al retornar.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/74" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/infinity.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    07 Permiso Temporal Individual - Asistencia a funeral familiar directo
                                                </p>
                                                <p>Autorización temporal para asistir a funerales de familiar directo. Permiso con vigencia por 05 horas si reside en la misma región del funeral y 24 horas si el funeral es en otra región.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/70" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/route.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    08 Permiso Temporal Individual - Retiro de alimentos desde organismos públicos
                                                </p>
                                                <p>Autorizaciones temporales para realizar el retiro de alimentos desde organismos públicos, tales como JUNAEB u otros. Este permiso tendrá una validez de 06 horas, con un máximo de 01 vez a la semana. No válido en horario de toque de queda.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/72" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/bookmark-1.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    09 Permiso Temporal Individual - Comparecencia a una citación en virtud de la Ley
                                                </p>
                                                <p>Autorizaciones temporales para comparecer a una citación a la que un abogado u otra persona deba concurrir en virtud de la Ley. Permiso con vigencia hasta que se cumpla la gestión.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/66" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/users.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    10 Permiso Temporal Individual - Entregar alimentos u otros insumos de primera necesidad a Adultos mayores
                                                </p>
                                                <p>Autorizaciones temporales para entregar alimentos u otros insumos de primera necesidad a adultos mayores. Permiso con vigencia por 02 horas. Un máximo de 02 permisos a la semana. No válido en horario de toque de queda.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/121" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/home.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    11 Permiso Temporal Individual - Cambio de domicilio
                                                </p>
                                                <p>Autorizaciones temporales para realizar cambios de domicilio. Permiso con vigencia por 24 horas. Se podrá solicitar solo una vez. No válido en horario de toque de queda.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/122" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/locked.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    12 Permiso Temporal Individual - Proporcionar alimentos o insumos de primera necesidad en Recinto Penitenciario
                                                </p>
                                                <p>Autorizaciones temporales para proporcionar alimentos u otros insumos de primera necesidad en Recintos Penitenciarios. Permiso con vigencia por 03 horas. Un máximo de 02 permisos a la semana. No válido en horario de toque de queda.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/123" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/home-2.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Abandono de Hogar
                                                </p>
                                                <p>Dejar constancia cuando usted o un tercero deja el lugar de residencia.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/16" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/bell.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Certificado de Bomberos Accidentados
                                                </p>
                                                <p>Dejar constancia de un accidente en acto de servicio, para ser presentada en la Comisión para el Mercado Financiero.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/19" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/file-1.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Contingencia Nacional: Información delitos y saqueos
                                                </p>
                                                <p></p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/26" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/users.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Fines Laborales
                                                </p>
                                                <p>Dejar constancia de la infracción de un contrato de trabajo o acuerdo laboral, por parte del empleador o trabajador.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/12" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/file-1.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Información Importante: Salvoconducto Colectivo Empresas Básicas
                                                </p>
                                                <p></p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/42" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/chat.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Iniciar Permisos temporales SIN ClaveÚnica
                                                </p>
                                                <p></p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/49" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/money.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Pensión de Alimentos
                                                </p>
                                                <p>Dejar constancia por incumplimiento del pago de pensión de alimentos acordada entre las partes.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/20" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/id-card-4.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Pérdida de Documentos
                                                </p>
                                                <p>Para dejar constancia por pérdida de documentos para ser presentada ante las entidades correspondientes.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/25" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/smartphone-1.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Pérdida de Teléfono Móvil
                                                </p>
                                                <p>Dejar constancia de la pérdida de su teléfono móvil para ser presentada ante la compañía telefónica y/o entidad solicitante.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/14" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/edit-1.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Reclamos al actuar policial
                                                </p>
                                                <p>Este módulo tiene por finalidad que usted pueda reportar conductas indebidas de parte de funcionarios de Carabineros.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/22" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/calendar-1.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Régimen de Visitas
                                                </p>
                                                <p>Dejar constancia por incumplimiento o entorpecimiento del régimen de visitas por alguna de las partes.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/15" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/folder-14.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Salvoconducto Colectivo - Empresas Básicas
                                                </p>
                                                <p>Herramienta que permitirá los desplazamientos necesarios para el cumplimiento de las funciones de los empleados y funcionarios de empresas de servicios públicos y utilidad pública (incluidos los traslados entre su lugar de residencia y el de trabajo) Para que puedan solicitar el documento se le pide al representante legal de las empresas/institución requerir el permiso, individualizando (nombre completo y RUT) a todos los empleados, el cuál tendrá una vigencia de 15 días. La solicitud debe acotarse únicamente al personal necesario para aquellas funciones, tareas, procesos o áreas de gestión o servicio de la organización que no pueden suspenderse por resultar imprescindibles para garantizar el servicio.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/38" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/infinity.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Salvoconducto individual - Trámites funerarios familiar directo
                                                </p>
                                                <p>Herramienta disponible para toda la ciudadanía, en la cual podrá solicitar autorización temporal para realizar trámites funerarios de familiares directos. Permiso con vigencia por 04 horas si reside en la misma región del funeral y 24 horas si el funeral es en otra región.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/37" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/photos.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Salvoconducto individual - Tratamientos médicos
                                                </p>
                                                <p>Herramienta disponible para toda la ciudadanía, en la cual podrá solicitar autorización temporal para asistir a centros, servicios y establecimientos de Salud por tratamiento médico.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/login/claveunica?redirect=https://comisariavirtual.cl/tramites/iniciar/36" class="card-footer claveunica">
                                        <i class="icon-claveunica"></i> Iniciar con Clave Única
                                        <span class="float-right">&#8594;</span>
                                    </a>
                                </div>

                            </div>
                            <div class="col-md-4 item">

                                <div class="card text-center">
                                    <div class="card-body">
                                        <div class="media">
                                            <img src="https://comisariavirtual.cl/img/icon/notepad-2.png" class="img-service">
                                            <div class="media-body">
                                                <p class="card-text">
                                                    Seguimiento reclamo
                                                </p>
                                                <p>Permite revisar el estado en que se encuentra tu reclamo.</p>
                                            </div>
                                        </div>
                                    </div>

                                    <a href="https://comisariavirtual.cl/tramites/iniciar/24" class="card-footer ">
                                                                            Iniciar trámite
                                                                        <span class="float-right">&#8594;</span>
                                </a>
                                </div>

                            </div>
                        </div>
                    </section>
                </div>
            </div>

        </div>
        <footer class="footer mt-auto py-3" style="background-color: #007328;">
            <div class="container">
                <div class="row">
                    <div class="col-6 mt-1">
                        <a href="http://www.carabineros.cl/" target="_blank">
                    Comisaría Virtual - Carabineros de Chile
                </a>
                        <br>
                        <a href="http://digital.gob.cl/" target="_blank">
                    Powered by División de Gobierno Digital
                </a>
                        <br>
                    </div>
                    <div class="col-6 mt-1 text-right">
                        <p style="font-size: 14px;line-height: 26px;">
                            Si el sistema presenta problemas comuníquese con nosotros escribiendo al siguiente correo comisaria.virtual@carabineros.cl
                        </p>
                    </div>
                </div>

                <div class="bicolor">
                    <span class="azul"></span>
                    <span class="rojo"></span>
                </div>
            </div>
        </footer>
    </div>

    <!-- Scripts -->
    <script src="https://comisariavirtual.cl/js/app.js"></script>
</body>

</html>
