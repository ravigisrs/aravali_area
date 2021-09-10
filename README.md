<!DOCTYPE html>
<html>

<head>
    <title>Aravali_Notified area</title>
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=0">
    <link rel="stylesheet" href="./images/juxtapose.css">
    <!-- favicons -->
    <!-- <link rel="apple-touch-icon" sizes="180x180" href="https://cdn.knightlab.com/libs/orangeline/latest/assets/favicons/apple-touch-icon.png"> -->
    <!-- <link rel="icon" type="image/png" href="https://cdn.knightlab.com/libs/orangeline/latest/assets/favicons/favicon-32x32.png" sizes="32x32"> -->
    <!-- <link rel="icon" type="image/png" href="https://cdn.knightlab.com/libs/orangeline/latest/assets/favicons/favicon-16x16.png" sizes="16x16"> -->
    <link rel="manifest" href="https://cdn.knightlab.com/libs/orangeline/latest/assets/favicons/manifest.json">
    <link rel="mask-icon" href="https://cdn.knightlab.com/libs/orangeline/latest/assets/favicons/safari-pinned-tab.svg" color="#5bbad5">
    <meta name="theme-color" content="#ffffff">
    <!-- /favicons -->

    <style>
        .juxtapose {
            max-width: 1300px;
			margin-left: 300px;			
        }        
        .jx-slider {
            margin-top: 2em;
		border: 3px solid black;			
         }
</style>
<h1 style="text-align: center">Compare Two Historical Images in Ansal retreat raisina Area,Gurugram(2005 and 2021)</h1>
<h3 style="text-align: center">Click and slide the White slider to compare two images:</h3>
</head>

<body>

    <div class="juxtapose" id="horizontal-demo">

    </div>

    <div class="juxtapose" id="vertical-demo">

    </div>


    <script src='./images/juxtapose.js'></script>
</body>


<script>
    <!-- slider_vertical = new juxtapose.JXSlider('#vertical-demo', [{ -->
        <!-- src: './images/Sochi_11April2005.jpg', -->
        <!-- label: '2009', -->
        <!-- credit: 'Image Credit' -->
    <!-- }, { -->
        <!-- src: './images/Sochi_22Nov2013.jpg', -->
        <!-- label: '2014', -->
        <!-- credit: "Image Credit" -->
    <!-- }], { -->
        <!-- animate: true, -->
        <!-- showLabels: true, -->
        <!-- showCredits: true, -->
        <!-- startingPosition: "25%", -->
        <!-- makeResponsive: true, -->
        <!-- mode: "vertical" -->
    <!-- }); -->

    slider_horizontal = new juxtapose.JXSlider('#horizontal-demo', [{
        src: './images/2005.jpg',
        label: '',
        credit: ''
    }, {
        src: './images/2021.jpg',
        label: '',
        credit: ""
    }], {
        animate: true,
        showLabels: true,
        showCredits: true,
        startingPosition: "25%",
        makeResponsive: true
    });
</script>
</html>
