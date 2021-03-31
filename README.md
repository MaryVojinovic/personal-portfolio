# personal-portfolio
<Doctype html>
    <html>
    <meta Charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">

    <head>
        <title>Designer portfolio</title>
        <link rel="stylesheet" type="text/css" href="style.css">

    </head>


    <body>
        <section>

            <header>

                <a href=# class="logo">Mary<span><hr>Design</span></a>



                <ul class="navigation">
                    <li><a href="file:///C:/Users/Lenovo/Desktop/Nova%20fascikla%20(2)/index.html">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Projects</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a href="#">Resume</a></li>
                    <li class="btn"><a href="#">keep in touch</a></li>
                </ul>

            </header>

            <img src="casual-life-3d-likes.png" class="picture"> </a>

            <div class="content">
                <div class="content-bx">


                    <h2>HI! My name is Marija and I am<br> a web designer</h2>

                    <!---
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Velit laboriosam quas repudiandae qui ipsum vero ex molestiae in, nisi quidem magni error placeat, accusamus unde totam facere, perspiciatis amet itaque.</p>
                     ----->
                    <a href="#">Let's get started!</a>

                </div>
            </div>

        </section>



        <!---about-->

        <section class="about" id="about">
            <div class="row">
                <div class="col50">
                    <h2 class="titleText"><span>A</span>bout me</h2>
                    <p> Hi there! My name is Marija Vojinovic. I am an ameteur web designer and my goal is to try and make your website unique. I was born in a small town in Serbia called Negotin which is famous for it's wine and chreeful people and
                        In the fields of grape ,rich history, grew passion to make web design that is beutiful, modern with just a hint of that folsky feel that we all sometimes miss. I hope you will enjoy my works and can't wait to work with you! <br><br>
                    </p>
                </div>
                <div class="col50">
                    <div class="imgBx">
                        <img src="lepa slika mene.jpeg">
                    </div>
                </div>
            </div>

        </section>


        <!--project--->

        <section class="projects" id="projects">
            <div class="title">
                <h2 class="titleText"><span>My</span>
                    <space>projects</h2>

                <div class="gallery">
                    <a target="_blank" href="project.jpg">
                        <img src="project.jpg" alt="Cinque Terre" width="600" height="400">
                    </a>
                    <div class="desc">project</div>
                </div>

                <div class="gallery">
                    <a target="_blank" href="project2.jpg">
                        <img src="project2.jpg" alt="Forest" width="600" height="400">
                    </a>
                    <div class="desc">project</div>
                </div>

                <div class="gallery">
                    <a target="_blank" href="project3.jpg">
                        <img src="project3.jpg" alt="Northern Lights" width="600" height="400">
                    </a>
                    <div class="desc">project 4</div>
                </div>

                <div class="gallery">
                    <a target="_blank" href="project4.jpg">
                        <img src="project4.jpg" alt="Mountains" width="600" height="400">
                    </a>
                    <div class="desc">project</div>
                </div>
            </div>
            <div class="text"></div>
        </section>
        <div class="row">
            <div class="column side">
                <h2>My <em>style</em></h2><br>

                <p>I steer clear from the modern techy look, I try to give my design a soul</p>
            </div>

            <div class="column middle">
                <h2><em>Why you should choose me</em></h2><br>
                <p>I work close with my clients , I like to get to know your likes and dislikes and choose the most appropriate design that will speak for you. eget luctus quam orci in velit. Praesent scelerisque tortor sed accumsan convallis.</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sit amet pretium urna. Vivamus venenatis velit nec neque ultricies, eget elementum magna tristique. Quisque vehicula, risus eget aliquam placerat, purus leo tincidunt eros,
                    eget luctus quam orci in velit. Praesent scelerisque tortor sed accumsan convallis.</p>
            </div>

            <div class="column side">
                <h2>Side</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit..</p>
            </div>
        </div>
        <div class="container">
            <div style="text-align:center">
                <h2>Contact me</h2>
                <p>Say hello or just comment on my work that would be nice</p>
            </div>
            <div class="row">
                <div class="column">
                    <img src="nebo.jpg" style="width:100%">
                </div>
                <div class="column">
                    <form action="/action_page.php">
                        <label for="fname">First Name</label>
                        <input type="text" id="fname" name="firstname" placeholder="Your name..">
                        <label for="lname">Last Name</label>
                        <input type="text" id="lname" name="lastname" placeholder="Your last name..">
                        <label for="country">Country</label>
                        <select id="country" name="country">
                    <option value="australia">Australia</option>
                    <option value="canada">Canada</option>
                    <option value="usa">USA</option>
                  </select>
                        <label for="subject">Subject</label>
                        <textarea id="subject" name="subject" placeholder="Write something.." style="height:170px"></textarea>
                        <input type="submit" value="Submit">
                    </form>
                </div>
            </div>
        </div>

        <div class="footer">
            <ul class="sci">
                <li>
                    <a href="https://www.facebook.com/marija.vojinovic3/"><img src="icons8-facebook-70.png"></a>
                </li>
                <li>
                    <a href="https://www.instagram.com/makicavojinovic/"><img src="icons8-instagram-70.png"></a>
                </li>
                <li>
                    <a href="https://github.com/MaryVojinovic"><img src="icons8-github-64.png"></a>
                </li>
            </ul>

        </div>




    </body>
    
    
   </html> 
   
   CSS
   
    @import url('https://fonts.googleapis.com/css2?family=Oranienbaum&display=swap');
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
    font-family: 'Oranienbaum', serif;
}

section {
    position: relative;
    width: 100%;
    min-height: 100vh;
    background-color: #f9d29d;
    background-image: linear-gradient(315deg, #f9d29d 0%, #ffd8cb 74%);
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    justify-content: center;
}

header {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    padding: 30px 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header.sticky {
    background: #fff;
    padding: 10px 100px;
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.05);
}

header .logo {
    position: relative;
    font-size: 2em;
    color: #fff;
    text-transform: uppercase;
    font-weight: 700;
    text-decoration: none;
}

header.sticky .logo {
    color: #111;
}

header .navigation {
    position: relative;
    display: flex;
}

header .navigation li {
    list-style: none;
}

header .navigation li a {
    display: inline-block;
    color: #fff;
    margin-right: 40px;
    text-decoration: none;
}

header.sticky .navigation li a {
    color: #111;
}

header .navigation li a:hover {
    color: #b35340;
}

.content {
    max-width: 600px;
}

.content .content-bx h2 {
    font-size: 2em;
    color: fff;
    line-height: 1em;
    position: relative;
    justify-content: center;
    position: center;
}




.content .content-bx a {
    display: inline-block;
    padding: 10px 30px;
    margin-top: 20px;
    display: inline-block;
    background: #5e5b59;
    opacity: 0.5;
    color: #ffff;
    text-decoration: none;
    font-weight: 500;
    letter-spacing: 1px;
    transition: .2s;
}

.content .content-bx a:hover {
    background-color: #913e2d;
    -ms-transform: scale(1.5);
    -webkit-transform: scale(1.5);
    transform: scale(1.5);
}

header.navigation {
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    background: #000;
    z-index: 10;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

@media (max-width:600px) {
    header {
        padding: 10px 12px;
    }
    section {
        padding: 30px;
    }
    .content .content-bx h2 {
        font-size: 1.5em;
    }
    .content .content-bx p {
        font-size: 1.5em;
    }
    header .navigation {
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: #000;
        z-index: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
}

.picture {
    max-width: 100%;
    height: auto;
    padding: 50px;
    display: flex;
}

img {
    width: 50%;
    height: 50%;
    object-fit: contain;
}

section {
    padding: 100px;
}

.about {
    background-color: #d3d3d3!important;
    border: 1px solid #fff;
    box-shadow: black;
}

#about {
    background-color: #f1dfd1;
    background-image: linear-gradient(315deg, #f1dfd1 0%, #f6f0ea 74%);
}

.row {
    position: relative;
    width: 110%;
    display: flex;
    justify-content: space-between;
}

.row .col50 {
    position: relative;
    width: 60%;
}

.titleText {
    font-size: 3em;
    font-weight: 300;
    padding-bottom: 5cm;
}

.titleText span {
    color: #913e2d;
    font-weight: 700;
    font-size: 1.5em;
    padding-left: 6cm;
    display: inline-block;
}

.row .col50 .imgBx {
    position: relative;
    width: 50%;
    height: 100%;
    margin-left: 5em;
}

.row .col50 .imgBx img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
}

.column {
    float: left;
    padding: 10px;
}


/* Left and right column */

.column.side {
    width: 20%;
}


/* Middle column */

.column.middle {
    width: 40%;
}




.row:after {
    content: "";
    display: table;
    clear: both;
}

.footer {
    position: relative;
    align-items: center;
    width: 100%;
    height: 90px;
    background-color: #913e2d;
    display: flex;
    flex-direction: row-reverse;
    justify-content: center;
    list-style: none;
}

.sci {
    position: absolute;
    bottom: 5px;
    display: flex;
}

.sci li {
    list-style: none;
    justify-content: center;
    align-items: center;
    display: flex;
}

.sci li a {
    position: relative;
    display: flexbox;
    margin-right: 50px;
    filter: invert(0);
}

@media screen and (max-width: 600px) {
    .column.side,
    .column.middle {
        width: 100%;
    }
}

div.gallery {
    margin: 5px;
    border: 1px solid #ccc;
    float: left;
    width: 180px;
}

div.gallery:hover {
    border: 1px solid #777;
}

div.gallery img {
    width: 100%;
    height: auto;
}

div.desc {
    padding: 15px;
    text-align: center;
}


/* Style inputs */

input[type=text],
select,
textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
}

input[type=submit] {
    background-color: #b35340;
    color: white;
    padding: 12px 20px;
    border: none;
    cursor: pointer;
}

input[type=submit]:hover {
    background-color: #913e2d;
}


/* contact section */

.container {
    border-radius: 5px;
    background-color: #f1dfd1;
    background-image: linear-gradient(315deg, #f1dfd1 0%, #f6f0ea 74%);
    padding: 10px;
}




.column {
    float: left;
    width: 30%;
    margin-top: 6px;
    padding: 20px;
}




.row:after {
    content: "";
    display: table;
    clear: both;
}


@media screen and (max-width: 600px) {
    .column,
    input[type=submit] {
        width: 100%;
        margin-top: 0;
    }
}
    
