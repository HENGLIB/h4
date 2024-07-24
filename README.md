<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        .container {
            width: 1200px;
            margin: auto;
        }
        
        .d-flex {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        body {
            font-family: "Poppins", sans-serif;
        }
        
        .navbar {
            background-color: #12863e;
        }
        
        .navbar .nav-brand img {
            height: 100px;
            border-radius: 50%;
            width: 100px;
            object-fit: cover;
        }
        
        .navbar .nav-navbar {
            list-style-type: none;
            display: flex;
            gap: 6px;
        }
        
        .navbar .nav-navbar .nav-item .nav-link {
            font-weight: 700;
            text-transform: uppercase;
            text-decoration: none;
            color: wheat;
            background-color: #12863e;
            padding: 30px 40px;
            display: inline-block;
            transition: 0.3s ease-in-out;
            border: #12863e 6px solid;
        }
        
        .navbar .nav-navbar .nav-item .nav-link:hover {
            border-bottom: 3px solid #b6e08e;
            color: #ff7200;
        }
    </style>
</head>

<body>
    <header>
        <nav class=" navbar ">
            <div class="container d-flex ">
                <a class="nav-brand " href="# ">
                    <img src="https://th.bing.com/th/id/R.83a028e386974cd8ce4307cdc28386cb?rik=G0e82wMwrxhVUw&pid=ImgRaw&r=0 " alt="logo ">
                </a>
                <ul class=" nav-navbar ">
                    <li class="nav-item ">
                        <a href="# " class="nav-link ">new</a>
                    </li>
                    <li class="nav-item ">
                        <a href="# " class="nav-link ">sport</a>
                    </li>
                    <li class="nav-item ">
                        <a href="# " class="nav-link ">About us</a>
                    </li>
                    <li class="nav-item ">
                        <a href="# " class="nav-link ">contack</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</body>

</html>
