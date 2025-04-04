# Shapes HTML & CSS:


###HTML Code:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shapes Game</title> 
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="main">
        <div id="box">
            <div  id="square" class="shapes"><h1>1</h1></div>
        <div id="diamond" class="shapes"><h1>2</h1></div>
        </div>
        <div id="circle" class="shapes"><h1>3</h1></div>
    </div>
    
</body>
</html>

###CSS Code:-

*{
    margin:0%;
    padding:0%; 
    box-sizing:border-box; 
} 
html,body{
    height: 100%;
    width:100%;
}
#main{
    height: 100%;
    width:100%;
    justify-content: center;
    align-items: center;
    display: flex;
}
.shapes{
     margin:10px;
    height: 200px;
    width: 200px;
    border: 1px solid black; 
    justify-content: center;
    align-items: center;
    display: flex; 
    font-family: 'Gill Sans';
    font-weight: lighter;

}

#diamond{
    rotate: 45deg;
   margin-top: 50px;
}
#diamond h1{
    rotate: -45deg;
}



#circle{
    border-radius: 50%;
}
#square:hover{ 
    background-color: red;


}
#diamond:hover{
background-color:blue ;
}
#circle:hover{
    background-color: green;

}
