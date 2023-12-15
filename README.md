# Akkaproject
Top 10 loading capacity airbuses
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>heart beat</title>
    <style>
      body{
        background-color: pink;
        text-align: center;
        
      }
        .heart{
            background-color: red;
             height: 200px;
             width: 200px; 
             margin-top:200px; ;
             margin-bottom: 150px;
             margin-left: 620px;
             animation: beat 5s infinite alternate;  
             
        }
        .heart:after,
        .heart:before{
             content: " ";
             align-content: center;
            background-color:red;
            height: 200px;
            position:absolute;
            width:200px;
            border-radius: 50%;    
        }
            .heart:before{
                left:0;
                top: -100px;
            }
            .heart:after{
               left: 100px;
               top:0;
            } 
            @keyframes beat {
                0%{
                transform:scale(1) rotate(-45deg);
            }
            100%{
                transform:scale(1.5) rotate(-45deg);
            }
                
            }
          
    </style>
</head>
<body >
   <h1>Ankit</h1>
    <div class="heart">
    </div>
    <h1></h1>
</body>
</html>
