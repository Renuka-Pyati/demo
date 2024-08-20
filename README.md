<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>Basic Landing page</title>
    <style>
        /*basic styline for the page*/
        body{
            font-family: Arial,  sans-serif;
            margin: 0;
            padding: 0;
        }
        /*header*/
        header{
            background-color: blue;
            color: white;
            padding: 20px;
            text-align: center;
        }
        /*navigation bar*/
        nav{
            background-color: #333;
            overflow: hidden;
        }
        nav ul{
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            float: left;

        }
        nav ul li a{
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav ul li a:hover{
            background-color: #111;
        }
        /*content*/
        .content{
            padding: 20px;
            text-align: center;
        }
        .content img{
            max-width: 100%;
            height: auto;
            margin-bottom: 20px;
        }
        .content p{
            font-size: 18px;
            line-height: 1.6;
            max-width: 600px;
            margin:0 auto;
            text-align: left;
        }
        /*footer*/
        footer{
            background-color: blue;
            color: white;
            text-align: center;
            padding: fixed;
            width: 100%;
            bottom: 0;
        }

</style>
</head>
<body>
    <header>
        <h1>Welcome to LeranOnline</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="=Content">
        <img src="online-education-home-schooling-free-vector.jpg" alt="Eduction img">
        <p>Welcome to our Website.our platform provides access to world-class Eductional resources,expert instructors and a community of learners.</p>
        <p>whether youu are looking to advance your career,learn something new ,or enhance your skills,our Courses are tailoerd to meet you need. </p>

    </div>
    <footer>
        <p>&copy;2024 LeranOnline.</p>
    </footer>

 
</body>
</html>
