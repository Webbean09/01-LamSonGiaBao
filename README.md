<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            padding: 0px;
            margin: 0px auto;
        }
        
        .wrapper {
            height: 860px;
            width: 1089px;
            background-color: darkgray;
        }
        
        nav {
            height: 60px;
            width: 1089px;
            background-color: rgb(130, 252, 187);
        }
        
        header {
            height: 160px;
            width: 1089px;
            background-color: rgb(28, 104, 104);
        }
        
        .content {
            height: 500px;
            width: 1089px;
            background-color: rgb(36, 87, 196);
        }
        
        footer {
            height: 160px;
            width: 1089px;
            background-color: rgb(2, 32, 36);
        }
        
        .menu-left {
            height: 500px;
            width: 25%;
            background-color: rgb(85, 109, 109);
            float: left;
        }
        
        .content-left {
            height: 500px;
            width: 37.5%;
            background-color: rgb(59, 146, 226);
            float: left;
        }
        
        .content-right {
            height: 500px;
            width: 37.5%;
            background-color: rgb(75, 14, 55);
            float: left;
        }
        
        .top-menu li {
            float: left;
            width: 200px;
            background-color: cyan;
            line-height: 60px;
            text-align: center;
            list-style: none;
        }
        
        li a {
            text-decoration: none;
            font-weight: lighter;
        }
        
        .top-menu li:hover {
            background-color: darkblue;
        }
        
        li:hover>a {
            font-style: italic;
        }
    </style>
</head>

<body>
    <div class="wrapper">
        <nav>
            <ul class="top-menu">
                <li>
                    <a href="https://iuh.edu.vn/">TRANG CHỦ</a></li>
                <li>
                    <a href="http://fit.iuh.edu.vn">TIN TỨC</a></li>
                <li>
                    <a href="http://">DỊCH VỤ</a></li>
                <li>
                    <a href="http://">HỖ TRỢ</a></li>
                <li>
                    <a href="http://iuh.edu.vn/">LIÊN HỆ</a></li>
            </ul>
        </nav>
        <header></header>
        <div class="content">
            <div class="menu-left"></div>
            <div class="content-right"></div>
            <div class="content-left"></div>
        </div>
        <footer></footer>
    </div>

</body>

</html>