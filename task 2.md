html -
.
.
.
<!DOCTYPE html>
<html>

<head>
  <title>CHINMAY LAKRA</title>

  <script src="https://kit.fontawesome.com/b3348ae33f.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <header id="body-header">
    <nav>
      <ul class="horizontal-list text-center nav-menu">
        <li>
          <a href="#"> Home </a>
        </li>
        <li>
          <a href="#about"> About </a>
        </li>
        <li>
          <a href="#skills"> Skills </a>
        </li>
        <li>
          <a href="#portfolio">Portfolio</a>
        </li>
        <li>
          <a href="#contact">Contact</a>
        </li>
      </ul>
    </nav>

    <div id="name-social-container">
      <div class="text-center">
        <h1 id="my-name">
            CHINMAY LAKRA
        </h1>
      </div>
      <div>
        <ul class="horizontal-list text-center social-icons">
          <li>
            <a href="#">
              <i class="fa-brands fa-linkedin"></i>
            </a>
          </li>
          <li>
            <a href="#">
              <i class="fa-brands fa-stack-overflow"></i>
            </a>
          </li>
          <li>
            <a href="#">
              <i class="fa-brands fa-google-plus-g"></i>
            </a>
          </li>
          <li>
            <a href="#">
              <i class="fa-brands fa-facebook"></i>
            </a>
          </li>
          <li>
            <a href="#">
              <i class="fa-brands fa-quora"></i>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </header>
  <main>
    <section id="about">
      <div id="my-image">
        <img src="chinmay2.jpg" />
      </div>

      <div id="about-para">
        <p>
            Hello! I'm Chinmay lakra, a 20-year-old tech enthusiast currently studying at
            <span class="text-highlight">Amity University, Noida</span> . 
            With a passion for coding and a knack for building websites, 
            I thrive on creating <span class="text-highlight">functional</span> and <span class="text-highlight">aesthetically</span> pleasing web solutions. 
            My journey into the world of programming began at a young age, and over the years, 
            I have honed my skills to become proficient in various web technologies.

          
        </p>
      </div>
    </section>
    <section id="skills">
         <h1 class="section-heading mb75px ">
            <span>
                <i class="fa-solid fa-chalkboard-user"></i>
            </span>
            <span>SKILLS</span>
        </h1>
        <div class="skills-display">
            
    
       
    <!-- HTML -->
         <div class="skills-progres">
            <div class="nighty-percent mb-blue">
                <div class="skill-name">
                    <span>HTML</span> 
                 </div>
            </div>
         </div>

    <!-- CSS -->
        <div class="skills-progres">
            <div class="eight-percent mb-blue">
                <div class="skill-name">
                    <span>CSS</span> 
                </div>
            </div>
        </div>

    <!-- JAVASCRIPT -->
        <div class="skills-progres">
            <div class="sixty-percent mb-blue">
                <div class="skill-name">
                    <span>Javascript</span> 
                </div>
            </div>
        </div>

    <!-- NODE JS -->
        <div class="skills-progres">
            <div class="fifty-percent mb-blue">
                <div class="skill-name">
                   <span>NodeJs</span> 
                </div>
            </div>
        </div>

   
        </div>
    </section>
      
      <section id="portfolio">
           <section id="experience">
        <h1 class="section-heading mb75px ">
            <span>
                <i class="fa-solid fa-list">               </i>
            </span>
            <span>Portfolio</span>
        </h1>
        
        <div class="portfolio-list">
            <div class="portfolio-list-content">
                <a href="$%^" ><img src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000000025_1550237330_codezen_2.png" alt=""></a>
            </div>
           <div class="portfolio-list-content">
                <a href="$%^" ><img src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000000025_1550237330_codezen_2.png" alt=""></a>
           </div>
           <div class="portfolio-list-content">
                <a href="$%^" ><img src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000000025_1550237330_codezen_2.png" alt=""></a>
           </div>

           <div class="portfolio-list-content">
               <a href="$%^" ><img src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000000024_1550237299_codezen.png" alt=""></a>
           </div>
           <div class="portfolio-list-content">
               <a href="$%^" ><img src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000000024_1550237299_codezen.png" alt=""></a>
           </div>
           <div class="portfolio-list-content">
               <a href="$%^" ><img src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000000024_1550237299_codezen.png" alt=""></a>
           </div>
        </div>
       </section>
      </section>
    <section id="contact"></section>
  </main>
</body>

</html>
.
.
.
.
.
.
.
.
.
 Css- 
 .
 .
 .
 body {
    margin: 0px;
    font-family: sans-serif;
    font-size: 30px;
}

/* Body Header */

#body-header {
    height: 65vh;
    opacity: 0.8;
    background-image:url(desk\ image.jpg);
    background-size: cover;
    background-position: unset;
    background-attachment: fixed;
    padding-top: 1.2rem;
}

/* Horizontal Lists */

.horizontal-list {
    list-style: none;
    padding-left: 0px;
    margin: 0px;
}

.horizontal-list li {
    display: inline-block;
    margin: 0px 8px 8px 0px;
    font-weight: 100;
    font-size: 0.9rem;
}


.horizontal-list li a {
    color: white;
    text-decoration: none;
}

.nav-menu li a {
    transition: color 0.5s, border-bottom 4s;
}

.nav-menu li a:hover {
    color: lightgrey;
    border-bottom: 1px solid black;
}

.text-center {
    text-align: center;
}

/* Name and Social Icons*/

#name-social-container {
    margin-top: 20vh;
}

#my-name {
    font-size: 3rem;
    letter-spacing: 0.1rem;
    color: white;
    font-weight: 700;
    margin-bottom: 0.5rem;
}


.social-icons li a i {
    /*color: red;*/
    padding: 10px;
    font-size: 1rem;
    border-radius: 50%;
}


.social-icons li a i:hover {
    box-shadow: 0px 0px 6px 4px rgba(230, 196, 196, 0.3);
}

section{
    width: 100%;
    height: 75vh;
    display: flex;
    flex-direction: column; 
    align-items: center;
}
section:nth-child(2n){
    background-color: rgb(239, 239, 239);
}
section:nth-child(2n + 1){
    background-color: #ffffff;
}

.section-heading{
     width: auto;
     padding: 20px 10px 10px;
     margin: 10px auto;
     font-weight: 400;
}
.section-heading span{
    font-size: 30px;
    color: #2857a4;
    display: inline-block;
    padding-top: 10px;
    margin-right: 0.5rem;
}

/*About Section*/

#about {
    height: auto;
    width: 100%;
    position: relative;
}

#my-image {
    height: 12rem;
    width: 12rem;
    margin: auto;
    margin-top: -17vh;
}

#my-image img {
    height: 110%;
    width: 100%;
    border-radius: 50%;
    border: 3px solid white;
    box-shadow: 1px 1px 10px 2px lightgrey;
}


#about-para {
    padding: 50px;
    width: 70%;
    text-align: justify;
    color: grey;
    line-height: 28px;
    font-size: 1.1rem;
    margin: auto;
}

.text-highlight {
    color: #2857a4;
    font-weight: 600;
}

/* Skills Section */

.skills-display {
    width: 70%;
    height: 100px;
    /* border: 2px solid black; 	 */
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
.skills-progres{
    height: 1.4rem;
    width: 7rem;
    background-color: lightgray;
    border-radius: 0.8rem;
}
.skills-progres>div{
    border-radius: 20px 0px 0px 20px;
}
.skills-progres span{
    color: white;
    font-size: 1rem;
   margin-left: 8px;
}
.skill-name{
    color: white;
    font-size: 1.2rem;
}

/* Portfolio section */

.portfolio-list{
    width: 70%;
    /* height: 80%; */
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
.portfolio-list-content{
    width: 30%;
}
.portfolio-list-content img{
   height: auto;
   width: 100%;
}


/* Common Margin Classes */
.mb75px {
    margin-bottom: 75px;
}

.text-highlight {
    color: #2857a4;
    font-weight: 600;
}

/* Percentage Classes */

.fifty-percent{
    width:50%;
    height: inherit;
    background-color: rgb(0, 19, 224);
}
.nighty-percent{
    width: 90%;
    height: inherit;
    background-color: #ff2323;
}
.eight-percent{
    width: 80%;
    height: inherit;
    background-color: #a86db9;
}
.sixty-percent{
    width: 60%;
    height: inherit;
    background-color: #05c54f;
}

 
