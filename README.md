<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Page</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #f5f5f5;
        }

        .container {
            display: flex;
            align-items: center;
            gap: 20px;
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            max-width: 90%;
        }

        .welcome-image {
            border-radius: 10px;
            object-fit: cover;
            max-width: 100%;
            height: auto;
        }

        .welcome-text {
            font-size: 3rem;
            font-weight: bold;
            color: #333;
            margin: 0;
        }

        /* Responsividade para telas menores */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                text-align: center;
            }
            
            .welcome-text {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <img 
            src="https://i.pinimg.com/736x/02/9a/fe/029afebee0ae0f1d2cc99069746ec2fd.jpg" 
            alt="doll's house" 
            width="400" 
            height="700"
            class="welcome-image"
            onerror="this.src='https://via.placeholder.com/400x700?text=Casa+de+Bonecas'"
        />
        
        <h1 class="welcome-text">Welcome</h1>
    </div>

</body>
</html>
