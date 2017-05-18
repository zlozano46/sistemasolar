# sistemasolar
2nD
Zein Lozano<html>
    <head>
        <link rel="stylesheet" href="style.css" />
    </head>
    
    <body>
        <!-- Right below is an image of the sun -->
        <img id="sun" src="http://goo.gl/PmbqZa">
        <img id="earth" src="http://goo.gl/41IWnf">
        <!-- Insert the 'earth' on the next line -->
        <div id='earth-orbit'>
    <img id='earth' src="http://goo.gl/41IWnf">
</div>
        
    </body>
</html>
html, body {
    /* The universe takes up all available space */
    width: 100%;
    height: 100%;
    
    /* The universe is black */
    background-color: black;
}

#sun {
     position: absolute;
    top: 50%;
    left: 50%;

    height: 200px;
    width: 200px;
    margin-top: -100px; 
    margin-left: -100px;

    border-color: orange;
    border-width: 8px;
    border-style: solid;
    border-radius: 50%;

    box-shadow: 0 0 128px red;
}

#earth {
   /* Style your earth */
    position: absolute;
    top: 25%;
    left: 25%;
}
#earth-orbit {
    position: absolute;
    top: 50%;
    left: 50%;

    width: 500px;
    height: 500px;
    margin-top: -250px;
    margin-left: -250px;

    border-width: 2px;
    border-style: dotted;
    border-color: white;
    border-radius: 50%;
     -webkit-animation: spin-right 10s linear infinite;
     -moz-animation: spin-right 10s linear infinite;
      -ms-animation: spin-right 10s linear infinite;
       -o-animation: spin-right 10s linear infinite;
          animation: spin-right 10s linear infinite;
}
