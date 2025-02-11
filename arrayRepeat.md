<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Array JavaScript</title>
    <p id="numeros"></p>
    <p id="indices"></p>
</head>
<body>
    <script>
        const arrayNumbers = [5, 1, 0, 2, 3, 4, 5, 8, 9, 1, 0, 1, 2, 3, 4, 5, 6, 8, 8, 9, 1, 0 ,7 , 9];
        let aRef = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0];
        document.getElementById("numeros").innerHTML = arrayNumbers;

        for(j = 0; j <= 23; j++) {
        aRef[arrayNumbers[j]]++;
    } 
       for (j = 0; j <= 9; j++){
        if(aRef[arrayNumbers[j]] == undefined){
            aRef[arrayNumbers[j]] += 1;

        }
       }
       console.log(aRef);
    </script>
</body>
</html>
