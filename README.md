# CIROGOVERNMENTPROJET-WiseCity-
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width=device-width">
    <title></title>

    <link rel="stylesheet" href="fonts/montserrat/css/fonts.css">
    
    <script src="lib/ionic/js/ionic.bundle.js"></script>

    <!-- cordova script (this will be a 404 during development) -->
    <script src="cordova.js"></script>

    <!-- IF using Sass (run gulp sass first), then uncomment below and remove the CSS includes above
    <link href="css/ionic.app.css" rel="stylesheet">
    -->

    <link href="css/ionic.app.css" rel="stylesheet">

    <style type="text/css">
      .platform-ios .manual-ios-statusbar-padding{
        padding-top:20px;
      }
      .manual-remove-top-padding{
        padding-top:0px; 
      }
      .manual-remove-top-padding .scroll{
        padding-top:0px !important;
      }
      ion-list.manual-list-fullwidth div.list, .list.card.manual-card-fullwidth {
        margin-left:-10px;
        margin-right:-10px;
      }
      ion-list.manual-list-fullwidth div.list > .item, .list.card.manual-card-fullwidth > .item {
        border-radius:0px;
        border-left:0px;
        border-right: 0px;
      }
      .show-list-numbers-and-dots ul{
        list-style-type: disc;
        padding-left:40px;
      }
      .show-list-numbers-and-dots ol{
        list-style-type: decimal;
        padding-left:40px;
      }
    </style>

    <script src="js/app.js"></script>
    <script src="js/controllers.js"></script>
    <script src="js/routes.js"></script>
    
    <script src="js/directives.js"></script>
    <script src="js/services.js"></script>

    
    <script src="lib/ionicuirouter/ionicUIRouter.js"></script>
    

  </head>
  <body ng-app="app" animation="slide-left-right-ios7">
  <div>
  <ion-side-menus enable-menu-with-back-views="false" data-componentid="side-menu21">
    <ion-side-menu-content>
      <ion-nav-bar class="bar-dark">
        <ion-nav-back-button></ion-nav-back-button>
        <ion-nav-buttons side="left">
          <button class="button button-icon button-clear ion-navicon" menu-toggle="left"></button>
        </ion-nav-buttons>
      </ion-nav-bar>
      <ion-nav-view></ion-nav-view>
    </ion-side-menu-content>
    <ion-side-menu side="left" id="side-menu21">
      <ion-header-bar class="bar-dark">
        <div class="title">Menu</div>
      </ion-header-bar>
      <ion-content ng-controller="menuCtrl" padding="false" class="side-menu-left has-header ">
        <ion-list id="menu-list1" data-componentid="list1">
          <ion-item class="item-thumbnail-left" id="menu-list-item1" data-componentid="list-item1">
            <img src="img/HFwU6pP8RsqYYv2vcQR5_JensenAcklespic.jpg">
            <h2>Rafael M.</h2>
            <p style="white-space:normal;">Segurança-ON Luzes-On </p>
          </ion-item>
          <ion-item class="item-icon-left dark" id="menu-list-item8" data-componentid="list-item8">
            <i class="icon ion-ios-settings-strong"></i>Configurações</ion-item>
          <ion-item class="item-icon-left" id="menu-list-item9" data-componentid="list-item9">
            <i class="icon ion-eye"></i>Leitor de Retina
            <span class="item-note">Ativado</span>
          </ion-item>
          <ion-item class="item-icon-left" id="menu-list-item10" data-componentid="list-item10">
            <i class="icon ion-android-hand"></i>Leitor de Digital
            <span class="item-note">Ativado</span>
          </ion-item>
          <ion-item class="item-icon-left" id="menu-list-item11" data-componentid="list-item11">
            <i class="icon ion-ios-time"></i>Timer da Luzes
            <span class="item-note">Ativado</span>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right" id="menu-list-item16" data-componentid="list-item16">
            <i class="icon ion-ios-people"></i>Cadastrar Família
            <span class="item-note">Esposa Filho 1, 2 e 3 </span>
            <i class="icon ion-android-add-circle icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left" id="menu-list-item12" data-componentid="list-item12">
            <i class="icon ion-card"></i>Carteira
            <span class="item-note">R$ 9.566,56</span>
          </ion-item>
          <ion-item class="item-icon-left" id="menu-list-item13" data-componentid="list-item13">
            <i class="icon ion-calculator"></i>Contas
            <span class="item-note">- R$ 429,56</span>
          </ion-item>
          <ion-item class="item-icon-left" id="menu-list-item17" data-componentid="list-item17">
            <i class="icon ion-qr-scanner"></i>Pagar com QR code</ion-item>
          <ion-item class="item-icon-left" id="menu-list-item15" data-componentid="list-item15">
            <i class="icon ion-clipboard"></i>Relatórios</ion-item>
          <ion-item class="item-icon-left" id="menu-list-item14" data-componentid="list-item14">
            <i class="icon ion-alert-circled"></i>Relatar Problema</ion-item>
        </ion-list>
      </ion-content>
    </ion-side-menu>
  </ion-side-menus>
</div>
  </body>
</html>
