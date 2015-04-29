<!DOCTYPE HTML>
<html>
<head>
	<meta http-equiv="content-type" content="text/html" />
	<meta name="author" content="lolkittens" />

	<title>Untitled 1</title>
    
 <style type="text/css">
html {
    background-color: #151e45;
    background-image: url("test.png");
    background-position: center bottom;
    background-repeat: no-repeat;
    background-size: contain;
    height: 100%;
}

#test {
    position:absolute;
    top:0; 
    right:0;
    bottom:0; 
    left:0;
    background: red;
}
 </style>
 
 <script type="text/javascript">
 
 $(function() {

    function abso() {

        $('#test').css({
            position: 'absolute',
            width: $(window).width(),
            height: $(window).height()
        });

    }

    $(window).resize(function() {
        abso();         
    });

    abso();

});
 
 </script>
 
</head>

<body>
<a href="https://www.google.co.in/" id="test"></a>
</body>
</html>
