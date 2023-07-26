# Webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <title>header and nav and footer</title>
    <style>
        body{
            padding: 0;
            margin: 0;
        }
        header{
            padding: 15px;
            background-image: url("https://1.bp.blogspot.com/-TXkzt9dQUwU/W3UegiD9-6I/AAAAAAAABD8/91hy0tl8kBcIOSjZfeCI2zG4wPMOsUeTACLcBGAs/s1600/hd-nature-background.jpg");
        }
        h1{
            color: ghostwhite;
            font-style: italic;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            text-shadow: 0 0 15px red;
        }
        nav{
            background: linear-gradient(45deg,grey,black);
            text-align: center;
            height: 40px;

        }
        a{
            position: relative;
            top: 10px;
            padding: 15px;
            text-decoration: none;
            color: white;
            text-shadow: 0 0 15px blue;
            font-style: italic;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;  
        }
        a:hover{
            background-color: black;
            color: ghostwhite;
            border-radius: 50px;
            margin: 20px;
        }
        footer{
            color: ghostwhite;
            text-align: center;
            padding: 15px;
            background-image: url("https://1.bp.blogspot.com/-TXkzt9dQUwU/W3UegiD9-6I/AAAAAAAABD8/91hy0tl8kBcIOSjZfeCI2zG4wPMOsUeTACLcBGAs/s1600/hd-nature-background.jpg");
        }
section{
    background: linear-gradient(45deg,grey,black);
        display: flex;
        justify-content: center;
        border: 2px solid black;
    }
    article{
       margin: 15px;
       padding: 10px;
       border-radius: 50px;
    }
    img{
        width: 300px;
        height: 200px;
        border-radius: 50px;
    }
    h4{
        color: white;
        text-align: center;
    }
    #java{
       text-shadow: 0 0 15px red;
    }
    #py{
       text-shadow: 0 0 15px blue;
    }
    #mern{
        text-shadow: 0 0 15px green;
    }
    #j{
        border: 2px solid red;
    }
    #p{
        border: 2px sol0id blue;
    }
    #m{
        border: 2px solid green;
    }
    </style>
</head>
<body>
    <!-- header -->
    <header>
        <h1>Travel Trip</h1>
    </header>
    <!-- nav bar -->
    <nav>
        <a href="">Home</a>
        <a href="">About</a>
        <a href="">Carrer</a>
        <a href="">Courses</a>
        <a href="">Contact</a>
    </nav>
    <section>
        <article id="j">
            <img src="https://besthqwallpapers.com/Uploads/2-3-2020/123438/java-fiery-logo-programming-language-orange-stone-background-creative-java-logo.jpg" alt="">
            <h4 id="java">JAVA FULL-STACK DEVELOPMENT</h4>
            <ul type="none">
                <li>CORE JAVA</li>
                <li>ADVANCE JAVA</li>
                <li>SPRING AND HIBERNATE</li>
                <li>WEB-TECHNOLOGY</li>
                <li>SQL</li>
            </ul>
        </article>
        <article id="p">
            <img src="https://img.besthqwallpapers.com/Uploads/12-2-2020/121316/python-golden-logo-programming-language-brown-metal-background-creative-python-logo.jpg" alt="">
            <h4 id="py">PYTHON FULL-STACK DEVELOPMENT</h4>
            <ul type="none">
                <li>CORE PYTHON</li>
                <li>ADVANCE PYTHON</li>
                <li>DJANGO</li>
                <li>WEB-TECHNOLOGY</li>
                <li>SQL</li>
        </article>
        <article id="m">
            <img src="https://wallpapercave.com/wp/wp8903900.png" alt="">
            <h4 id="mern">MERN FULL-STACK DEVELOPMENT</h4>
            <ul type="none">
                <li>MONGO DB</li>
                <li>NODE JS</li>
                <li>EXPRESS JS</li>
                <li>WEB-TECHNOLOGY</li>
                <li>REACT</li>
        </article>
    </section>
    <!-- footer -->
    <footer>
        <h3>CopyRights&copy 2022</h3>
        <p>Address: 761/1, 3rd Floor, Dr Puneeth Rajkumar Rd, next to Chaitanya Techno School, near KLM Mall, Marathahalli, Bengaluru, Karnataka 560037</p>
        <button>
            Home
        </button>
    </footer>
</body>
</html>
