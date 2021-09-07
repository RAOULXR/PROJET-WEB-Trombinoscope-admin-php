# PROJET-WEB-Trombinoscope-admin-php
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        
        
        <!--<link href="./bootstrap/css/bootstrap.min.css" rel="stylesheet">-->
         <link href="./bootstrap/css/bootstrap.css" rel="stylesheet"> 
        <link href="./style/style.css" rel="stylesheet">

        <title>RSMA - DWEB</title>
        <script src="./bootstrap/js/popper.min.js"></script>
        <script src="./bootstrap/js/jquery-slim.min.js"></script>
        <script src="./bootstrap/js/bootstrap.min.js"></script>
        <!-- <script src="./bootstrap/js/bootstrap.js"></script> -->
        <script src="./bootstrap/js/util.js"></script>
    </head>
    <body>
      <!-- CAROUSEL  -->
         <div class="container-fluid" > 
          <div id="carousel" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carousel" data-slide-to="0" class="active"></li>
              <li data-target="#carousel" data-slide-to="1"></li>
              <li data-target="#carousel" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item  active" >
                <img class="d-block w-100" src="./img/carousel/bg_1.jpg" alt="First slide" style="height: 900px;" id="carousel_header">
                <div class="carousel-caption d-md-block">
                  <h5>Filière D-WEB</h5>
                  <!-- MENU -->
                  <div id="navbar">
                    <a class="menu"  href="index.html">
                        <div>
                            <h6>ACCUEIL</h6>
                        </div>
                    </a>
                    <a class="menu"  href="#pres">
                        <div>
                            <h6>PRESENTATION</h6>
                        </div>
                    </a>
                    <a class="menu"  href="#tromb">
                        <div>
                            <h6>TROMBINOSCOPE</h6>
                        </div>
                    </a>
                </div>
                </div>
              </div>
              <!-- CAROUSEL  -->
              <div class="carousel-item" >
                <img class="d-block w-100" src="./img/carousel/bg_2.jpg" alt="Second slide" style="height: 900px;" id="carousel_header">
                <div class="carousel-caption d-md-block">
                  <h5>PROMOTION OCTOBRE 2020</h5>
                  <!-- MENU -->
                  <div id="navbar">
                    <a class="menu"  href="index.html">
                      <div>
                          <h6>ACCUEIL</h6>
                      </div>
                  </a>
                  <a class="menu"  href="#pres">
                      <div>
                          <h6>PRESENTATION</h6>
                      </div>
                  </a>
                  <a class="menu"  href="#tromb">
                      <div>
                          <h6>TROMBINOSCOPE</h6>
                      </div>
                  </a>
                </div>
                </div>
              </div>
              <!-- CAROUSEL  -->
              <div class="carousel-item">
                <img class="d-block w-100" src="./img/carousel/bg_3.jpg" alt="Third slide" style="height: 900px;" id="carousel_header">
                <div class="carousel-caption d-md-block">
                  <h5>SECTION SERGENT-CHEF BLANCHARD</h5>
                  <!-- MENU -->
                  <div id="navbar">
                    <a class="menu"  href="index.html">
                      <div>
                          <h6>ACCUEIL</h6>
                      </div>
                  </a>
                  <a class="menu"  href="#pres">
                      <div>
                          <h6>PRESENTATION</h6>
                      </div>
                  </a>
                  <a class="menu"  href="#tromb">
                      <div>
                          <h6>TROMBINOSCOPE</h6>
                      </div>
                  </a>
                </div>
                </div>
              </div>
            </div>
            <a class="carousel-control-prev" href="#carousel" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carousel" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>


         </div> 
         <div class="container-fluid">
          <div id="pres">
              <h1 style="color: rgb(92, 134, 173);">Présentation</h1>
              <br>
              <p> Je vous présente la filière DevWeb du <b> RSMA-pf de Arue</b> </p>
              <p>La formation est assurée par <a>Simplon.co</a>, un organisme qui se charge de former dans les métiers du numérique.</p>
              <p>Nous somme la 2ème promotion de la filière D-Web incorporé en Octobre 2020.</p>
              <p>La filière est composées de 12 stagiaires (10 garçons et 2 filles).</p>
              
          </div>
          </div>

          <!-- TROMBINOSCOPE -->
          <div class="tromb_box">
            <div id="tromb">
                <h1 style="color: rgb(92, 134, 173);">Trombinoscope</h1>
                <br>
                <div class="container">
                  <div class="row">
                    <!-- MRS CHARPENTIER -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/charpentier.jpg" alt="Card image cap">
                        <div class="card-body">
                            <div id="accordion">
                              <div class="card">
                                <div class="card-header" id="headingOne">
                                  <h5 class="mb-0">
                                    <button class="btn btn-link" data-toggle="collapse" data-target="#charpentier" aria-expanded="true" aria-controls="charpentier">
                                      MRS CHARPENTIER
                                    </button>  
                                  </h5>
                                </div>
                              </div>
                              <div id="charpentier" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                                <div class="card-body">
                                  <div class="mrs_desc" align="left">
                                    <p><b><u>Nom</u></b> : CHARPENTIER</p>
                                    <p><b><u>Prénom</u></b> : Nato</p>
                                    <p><b><u>Age</u></b> : 19 ans</p>
                                    <p><b><u>Domicile</u></b> : ARUE </p>
                                    <p><b><u>@Mail</u></b> : ncharp14@gmail.com</p>
                                    <div class="container">
                                      <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                      <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                    </div>
                                    
                                  </div>
                                </div>
                              </div>
                            </div>
                        </div>
                      </div>
                    </div>

                    <!-- MRS FAATAU -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/faatau.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#faatau" aria-expanded="true" aria-controls="faatau">
                                    MRS FAATAU
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="faatau" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : FAATAU</p>
                                  <p><b><u>Prénom</u></b> : Ismael</p>
                                  <p><b><u>Age</u></b> : 24 ans</p>
                                  <p><b><u>Domicile</u></b> : PAPARA</p>
                                  <p><b><u>@Mail</u></b> : faatauismael83@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>

                    <!-- MRS HAUATA -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/hauata.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#hauata" aria-expanded="true" aria-controls="hauata">
                                    MRS HAUATA
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="hauata" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : HAUATA</p>
                                  <p><b><u>Prénom</u></b> : Hotutahi</p>
                                  <p><b><u>Age</u></b> : 19 ans</p>
                                  <p><b><u>Domicile</u></b> : PAEA</p>
                                  <p><b><u>@Mail</u></b> : hotutahih@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>

                    <!-- MRS IE -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/ie.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#ie" aria-expanded="true" aria-controls="ie">
                                    MRS IE
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="ie" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : IE</p>
                                  <p><b><u>Prénom</u></b> : Manutahi</p>
                                  <p><b><u>Age</u></b> : 20 ans</p>
                                  <p><b><u>Domicile</u></b> : PAPEETE</p>
                                  <p><b><u>@Mail</u></b> : haroie98@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>  
                    </div>

                    <!-- MRS MAHATIA -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/mahatia.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#mahatia" aria-expanded="true" aria-controls="mahatia">
                                    MRS MAHATIA
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="mahatia" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : MAHATIA</p>
                                  <p><b><u>Prénom</u></b> : Oarii</p>
                                  <p><b><u>Age</u></b> : 19 ans</p>
                                  <p><b><u>Domicile</u></b> : PAEA</p>
                                  <p><b><u>@Mail</u></b> : omahatia0210@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                        </div>
                      </div>
  
                    <!-- MRS PETERANO -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/peterano.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#peterano" aria-expanded="true" aria-controls="peterano">
                                    MRS PETERANO
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="peterano" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : PETERANO</p>
                                  <p><b><u>Prénom</u></b> : Terehaunui</p>
                                  <p><b><u>Age</u></b> : 22 ans</p>
                                  <p><b><u>Domicile</u></b> : PAPEARI</p>
                                  <p><b><u>@Mail</u></b> : terehau.peterano@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                                <script>
                                  $('#btn-link').mouseover(function(){                                  
                                  // $(this) c'est ici comme $('#truc')
                                  
                                  });
                                </script>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>  
                    </div>
                    
                    <!-- MRS POETAI -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/poetai.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#poetai" aria-expanded="true" aria-controls="poetai">
                                    MRS POETAI
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="poetai" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : POETAI</p>
                                  <p><b><u>Prénom</u></b> : Teriimana</p>
                                  <p><b><u>Age</u></b> : 19 ans</p>
                                  <p><b><u>Domicile</u></b> : FAAA</p>
                                  <p><b><u>@Mail</u></b> : fireofstyle06@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>

                    <!-- MRS RAOULX -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/raoulx.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#raoulx" aria-expanded="true" aria-controls="raoulx">
                                    MRS RAOULX
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="raoulx" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : RAOULX</p>
                                  <p><b><u>Prénom</u></b> : Ranihei</p>
                                  <p><b><u>Age</u></b> : 23 ans</p>
                                  <p><b><u>Domicile</u></b> : PUUNAUIA</p>
                                  <p><b><u>@Mail</u></b> : raoulxranihei@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>  
                    </div>

                    <!-- MRS TAUTU -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/tautu.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#tautu" aria-expanded="true" aria-controls="tautu">
                                    MRS TAUTU
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="tautu" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : TAUTU</p>
                                  <p><b><u>Prénom</u></b> : Vaimiti</p>
                                  <p><b><u>Age</u></b> : 22 ans</p>
                                  <p><b><u>Domicile</u></b> : PIRAE</p>
                                  <p><b><u>@Mail</u></b> : vaimiti.tautu1998@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>  
                    </div>

                    <!-- MRS TUAHU -->
                    <div class="col-md-4">  
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/tuahou.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#tuahu" aria-expanded="true" aria-controls="tuahu">
                                    MRS TUAHU
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="tuahu" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : TUAHU</p>
                                  <p><b><u>Prénom</u></b> : Wilfred</p>
                                  <p><b><u>Age</u></b> : 20 ans</p>
                                  <p><b><u>Domicile</u></b> : PUUNAUIA</p>
                                  <p><b><u>@Mail</u></b> : yurisolsagara60@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>

                    <!-- MRS VANAA -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/vanaa.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#vanaa" aria-expanded="true" aria-controls="vanaa">
                                    MRS VANAA
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="vanaa" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : VANAA</p>
                                  <p><b><u>Prénom</u></b> : Jubilé</p>
                                  <p><b><u>Age</u></b> : 20 ans</p>
                                  <p><b><u>Domicile</u></b> : FAAA</p>
                                  <p><b><u>@Mail</u></b> : jubile.vanaa1@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>  
                    </div>

                    <!-- MRS MU -->
                    <div class="col-md-4">
                      <div class="card">
                        <img class="card-img-top" src="./img/pax/mu.jpg" alt="Card image cap">
                        <div class="card-body">
                          <div id="accordion">
                            <div class="card">
                              <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                  <button class="btn btn-link" data-toggle="collapse" data-target="#mu" aria-expanded="true" aria-controls="mu" >
                                    MRS MU
                                  </button>  
                                </h5>
                              </div>
                            </div>
                            <div id="mu" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                              <div class="card-body">
                                <div class="mrs_desc" align="left">
                                  <p><b><u>Nom</u></b> : MU</p>
                                  <p><b><u>Prénom</u></b> : Mahinui</p>
                                  <p><b><u>Age</u></b> : 26 ans</p>
                                  <p><b><u>Domicile</u></b> : TAUTIRA</p>
                                  <p><b><u>@Mail</u></b> : mahinui.mu96@gmail.com</p>
                                  <div class="container">
                                    <p><input type="submit" Value="Portfolio" onClick="window.location.href='https://www.google.com';"></input></p>
                                    <p><input type="submit" Value="Trombinoscope" onClick="window.location.href='https://www.google.com';"></input></p>
                                  </div>
                                  
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>  
                    </div>
                  </div> <!-- FIN CLASS ROW -->
                </div> <!-- FIN CLASS CONTAINER -->
              </div>  <!-- FIN CLASS TROMB -->
            </div> <!-- FIN CLASS TROMB_BOX -->
      <!-- CAROUSEL  -->
      <div class="row d-flex justify-content-center"> 
          <div class="col-md-12" style="background-color: black; height:10vh ;padding-top: 2%; color: white">
            <p align="center">
              &copy;Site Trombinoscope de la filière Dev-Web Promo Octobre 2020 - PETERANO - POETAI - RAOULX
            </p>
          </div>
      </div>
    </body>
</html>
