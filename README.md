<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Naser Jafari | Portfolio</title>
    <link rel="stylesheet" href="css eindproject 2/eindproject 2.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Dongle&family=Source+Sans+Pro&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Dongle&family=Poppins:ital,wght@1,200&family=Source+Sans+Pro&display=swap"
      rel="stylesheet"
    />
    <script src="https://kit.fontawesome.com/0bcdb7bdd8.js" crossorigin="anonymous"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Dongle&family=Lato:ital@1&family=Poppins:ital,wght@1,200&family=Source+Sans+Pro&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>
    <header>
      <div class="navbar">
        <a href="#home"><i class="fas fa-home"></i>Home</a>
        <a href="#about"><i class="far fa-address-card"></i>About</a>
        <a href="#tools"><i class="fas fa-tools"></i>Tools</a>
        <a href="#contact"><i class="far fa-comments"></i>Contact</a>
        <a href="http://127.0.0.1:5500/extra.html"><i class="fas fa-plus"></i>Extra</a>
      </div>
    </header>
    <main id="home">
      <div class="background-eerstedeel">
        <span class="Begin-tekst"> Mijn naam is Naser Jafari</span>
        <p class="Midden-tekst">en ben een opkomende</p>
        <span class="Einde-tekst">Software Developer.</span>
      </div>
      <div class="about" id="about">
        <div class="Wie ben ik">
          <h1>Wie ben ik?</h1>
        </div>
        <div class="jake">
          <img src="afbeeldingen/jake adventure time.gif" alt="jake dancing" />
        </div>
        <div class="monkey">
          <img src="afbeeldingen/monkey.gif" alt="monkey meme" />
        </div>
        <div class="about-tekst">
          <p class="informeren">
            Mijn naam is Naser Jafari en ik ben een student die op
            <a href="https://www.roc-nijmegen.nl/" target="_blank"
              >ROC Nijmegen</a
            >
            zit in leerjaar 1.
          </p>
          <p class="meer-informatie">
            Ik heb voor deze opleiding gekozen omdat dit wel een leuke opleiding
            leek, wat blijkt?
          </p>
          <p class="mening-informatie">
            Het is een leuke opleiding, maar wel een beetje moeilijk als je het
            nooit gehad had zoals ik.
          </p>
        </div>
        <div class="school">
          <img src="afbeeldingen/school.png" alt="mijn school" />
        </div>
        <div class="skills">
          <p class="Mijn-skills">Dit zijn mijn skills.</p>
          <p class="skills-tekst">
            Ik spreek Nederlands en Engels. Ook kan ik goed samenwerken in een project bijvoorbeeld, ook kan
            ik zelfstandig zijn.
          </p>
          <p class="hobbies">
            Mijn hobby's zijn gamen, voetballen en sindskort programmeren.
          </p>
          <p class="diploma">
            Ook heb ik mijn VMBO diploma gehaald op
            <a href="https://www.liemerscollege.nl/" target="_blank"
              >Liemers College Zonegge</a
            >
            2021.
          </p>
        </div>
        <div class="tools" id="tools">
          <div class="tools-tekst">
            <h2>
              Tools, skills en websites die ik gebruikt voor programmeren.
            </h2>
          </div>
          <div class="icons-container">
            <div class="HTML-icon">
              <i class="fab fa-html5" title="HTML"></i>
              <p class="html-tekst">HTML</p>
            </div>
            <div class="CSS-icon">
              <i class="fab fa-css3-alt" title="CSS"></i>
              <p class="css-tekst">CSS</p>
            </div>
            <div class="JS-icon">
              <i class="fab fa-js-square" title="JavaScript"></i>
              <p class="js-tekst">JavaScript</p>
            </div>
            <div class="inspiratie">
              <a
                href="https://anniebombanie.com/#home"
                class="fab fa-chrome"
                target="_blank"
                title="Inspiratie"
              ></a>
              <p class="icons-tekst">Inspiratie</p>
            </div>
          </div>
              <div class="back-to-top">
                <i
                  class="fas fa-arrow-circle-up"
                  class="back-to-top"
                  onclick="topFunction()"
                  id="myBtn"
                  title="Go to top"
                ></i>
              </div>
                <div class="bezig">
                  Waar ik nu mee bezig ben: aan het oefenen voor andere
                  programmeertalen zoals Java en Python. En om mijn skills te vergroten voor mijn toekomst.
                </div>
                <div class="contact-pagina">
                  <h3 id="contact">Contact</h3>
                  <p>Neem contact met op als je wilt</p>
                  <form action="https://www.dafk.net/what/" target="_blank" >
                    <label for="fname">Voornaam
                      <img class="peter-griffin" src="afbeeldingen/peter griffin dancing.gif" alt="peter griffin dancing">
                    </label>
                    <input type="text" id="fname" name="firstname" placeholder="Peter..">
                    <label for="lname">Achternaam</label>
                    <input type="text" id="lname" name="lastname" placeholder="Griffin..">
                    <label for="country">Land</label>
                    <select id="country" name="country">
                      <option value="nederland">Nederland</option>
                      <option value="belgie">Belgie</option>
                      <option value="luxemberg">Luxemberg</option>
                    </select>
                    <label for="subject">Subject</label>
                    <textarea id="subject" name="subject" placeholder="Bird is the word.." style="height:200px"></textarea>
                    <input type="submit" value="Versturen">
                  </form>
                  </div>
                  <h4>Socials, dit zijn mijn sociale linkjes</h4>
                  <div class="icon-contacts-container">
                    <div class="github-icon">
                      <a
                      href="https://github.com/NASIdude"
                      class="fab fa-github"
                      target="_blank"
                      title="Github"
                    ></a>
                    </div>
                    <div class="facebook-icon">
                      <a href="https://www.facebook.com/RickAstley"
                      class="fab fa-facebook"
                      target="_blank"
                      title="Facebook"
                    ></a>
                    </div>
                    <div class="twitter-icon">
                      <a href="https://twitter.com/rickastley"
                        class="fab fa-twitter"
                        target="_blank"
                        title="Twitter"
                    ></a>
                    </div>
                    <div class="instagram-icon">
                      <a href="https://www.instagram.com/officialrickastley/?hl=nl"
                        class="fab fa-instagram"
                        target="_blank"
                        title="Instagram"
                    ></a>
                    </div>
                </div>
            </div>
          </div>
        </div>
      </div>
    </main>
    <footer>
      <div class="footbar">
        <p>© 2022 | Gemaakt door Naser Jafari <span> met bloed, zweet en tranen</span>.</p>
      </div>
    </footer>
    <script src="js/alles.js"></script>
  </body>
</html>
