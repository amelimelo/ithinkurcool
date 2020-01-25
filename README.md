# ithinkurcool
yeehaw 4 love 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <style>
    
    body{
        font-size: 100px;
        text-align: center;
        font-family: helvetica, arial, sans-serif;
        background-color: antiquewhite;
        color:cadetblue;
        
        
    }
    
    </style>
    <title>Document</title>
</head>


<body>
    <script>
    let texte = 'this is just to say i love you and i\'m sorry we didn\'t get to hang out this weekend - i wish we could have seen grizzly man together, i always enjoy watching movies with u. see you soon <3';
    let separation = texte.split(' ');
    let longueur = separation.length;
    console.log(separation.length);

    for(i=0; i<longueur; i++){
        let ligne =document.createElement('p');
            console.log(separation[i]);
        ligne.innerHTML=separation[i];
        document.body.append(ligne);
        ligne.style.fontSize=`${200/(i+1)}px`;
    }
     
    </script>
    
</body>
</html>
