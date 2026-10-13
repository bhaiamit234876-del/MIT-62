

&#x20;

<!DOCTYPE html>

<html lang="en">

<head>

&#x20; <meta charset="UTF-8">

&#x20; <meta name="viewport" content="width=device-width, initial-scale=1.0">

&#x20; <meta name="description" content="Welcome to my personal website.">

&#x20; <title>My Website</title>



&#x20; <style>

&#x20;   \* {

&#x20;     box-sizing: border-box;

&#x20;     margin: 0;

&#x20;     padding: 0;

&#x20;   }



&#x20;   body {

&#x20;     font-family: Arial, sans-serif;

&#x20;     background: #f5f7fb;

&#x20;     color: #172033;

&#x20;     line-height: 1.6;

&#x20;   }



&#x20;   header {

&#x20;     background: #ffffff;

&#x20;     padding: 18px 8%;

&#x20;     display: flex;

&#x20;     justify-content: space-between;

&#x20;     align-items: center;

&#x20;     flex-wrap: wrap;

&#x20;     gap: 12px;

&#x20;     box-shadow: 0 2px 10px #0000000a;

&#x20;   }



&#x20;   header h2 {

&#x20;     color: #2563eb;

&#x20;   }



&#x20;   nav a {

&#x20;     color: #172033;

&#x20;     text-decoration: none;

&#x20;     margin-left: 18px;

&#x20;     font-size: 14px;

&#x20;   }



&#x20;   .hero {

&#x20;     text-align: center;

&#x20;     padding: 90px 20px;

&#x20;     background: linear-gradient(135deg, #dbeafe, #ffffff);

&#x20;   }



&#x20;   .hero h1 {

&#x20;     font-size: clamp(32px, 6vw, 54px);

&#x20;     margin-bottom: 16px;

&#x20;   }



&#x20;   .hero p {

&#x20;     max-width: 600px;

&#x20;     margin: 0 auto 26px;

&#x20;     color: #536078;

&#x20;   }



&#x20;   .button {

&#x20;     display: inline-block;

&#x20;     background: #2563eb;

&#x20;     color: white;

&#x20;     border: none;

&#x20;     padding: 13px 23px;

&#x20;     border-radius: 8px;

&#x20;     text-decoration: none;

&#x20;     cursor: pointer;

&#x20;     font-size: 16px;

&#x20;   }



&#x20;   section {

&#x20;     padding: 55px 8%;

&#x20;     text-align: center;

&#x20;   }



&#x20;   section h2 {

&#x20;     margin-bottom: 20px;

&#x20;   }



&#x20;   .cards {

&#x20;     display: grid;

&#x20;     grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));

&#x20;     gap: 20px;

&#x20;     margin-top: 25px;

&#x20;   }



&#x20;   .card {

&#x20;     background: white;

&#x20;     border-radius: 12px;

&#x20;     padding: 26px;

&#x20;     box-shadow: 0 4px 18px #1720330c;

&#x20;   }



&#x20;   .card h3 {

&#x20;     margin-bottom: 10px;

&#x20;     color: #2563eb;

&#x20;   }



&#x20;   #contact {

&#x20;     background: #eaf1ff;

&#x20;   }



&#x20;   footer {

&#x20;     padding: 22px;

&#x20;     text-align: center;

&#x20;     background: #172033;

&#x20;     color: white;

&#x20;   }



&#x20;   @media (max-width: 500px) {

&#x20;     header {

&#x20;       justify-content: center;

&#x20;     }



&#x20;     nav a {

&#x20;       margin: 0 7px;

&#x20;     }



&#x20;     .hero {

&#x20;       padding: 65px 18px;

&#x20;     }

&#x20;   }

&#x20; </style>

</head>



<body>

&#x20; <header>

&#x20;   <h2>My Website</h2>

&#x20;   <nav>

&#x20;     <a href="#home">Home</a>

&#x20;     <a href="#about">About</a>

&#x20;     <a href="#services">Services</a>

&#x20;     <a href="#contact">Contact</a>

&#x20;   </nav>

&#x20; </header>



&#x20; <main>

&#x20;   <section class="hero" id="home">

&#x20;     <h1>Welcome to My Website!</h1>

&#x20;     <p>

&#x20;       Discover my website, explore what I do,

&#x20;       and get in touch with me.

&#x20;     </p>

&#x20;     <a class="button" href="#about">Explore Now</a>

&#x20;   </section>



&#x20;   <section id="about">

&#x20;     <h2>About Us</h2>

&#x20;     <p>

&#x20;       Welcome! This is my website.

&#x20;       Replace this text with your own introduction,

&#x20;       story, or project information.

&#x20;     </p>

&#x20;   </section>



&#x20;   <section id="services">

&#x20;     <h2>What We Offer</h2>

&#x20;     <div class="cards">

&#x20;       <article class="card">

&#x20;         <h3>Our Projects</h3>

&#x20;         <p>Share your projects and ideas with visitors.</p>

&#x20;       </article>



&#x20;       <article class="card">

&#x20;         <h3>Our Information</h3>

&#x20;         <p>Publish useful information and announcements.</p>

&#x20;       </article>



&#x20;       <article class="card">

&#x20;         <h3>Our Community</h3>

&#x20;         <p>Connect with people and share your work.</p>

&#x20;       </article>

&#x20;     </div>

&#x20;   </section>



&#x20;   <section id="contact">

&#x20;     <h2>Contact Us</h2>

&#x20;     <p>Have a question? Get in touch by email.</p>

&#x20;     <br>

&#x20;     <a class="button"

&#x20;        href="mailto:you@example.com">

&#x20;       Send an Email

&#x20;     </a>

&#x20;   </section>

&#x20; </main>



&#x20; <footer>

&#x20;   <p>© <span id="year"></span> My Website. All rights reserved.</p>

&#x20; </footer>



&#x20; <script>

&#x20;   document.getElementById("year").textContent =

&#x20;     new Date().getFullYear();

&#x20; </script>

</body>

</html>

