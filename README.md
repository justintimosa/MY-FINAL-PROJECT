# MY-FINAL-PROJECT
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f8f9fa;
    }

    .left-column {
      width: 100%;
      background-color: #f0f0f0;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      margin-bottom: 20px;
    }

    .image-container img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }

    .tagline,
    .fun-facts {
      margin-top: 20px;
    }

    .header {
      background-color: #808080;
      text-align: center;
      color: #fff;
    }

    .container-fluid {
      padding: 20px;
    }

    .right-column {
      width: 100%;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
    }

    .about-me-header {
      text-align: center;
    }

    .about-me-content {
      margin-top: 20px;
    }

    .about-me-content p {
      margin-bottom: 10px;
    }

    .social-icons {
      margin-top: 20px;
      text-align: center;
    }

    .social-link {
      display: inline-block;
      margin-right: 15px;
      text-decoration: none;
    }

    .social-link img {
      max-width: 40px;
    }

    .programming-portfolio-header {
      background-color: #808080;
      text-align: center;
      color: #fff;
    }

    .project-card {
      margin-top: 20px;
      border: 1px solid #ddd;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .project-card img {
      max-width: 100%;
      height: 120px;
      object-fit: contain;
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
      margin: 0 auto;
    }

    .project-card-body {
      padding: 15px;
      text-align: center;
      min-height: 160px;
    }

    .view-project-link {
      display: inline-block;
      margin-top: 10px;
    }
  </style>
  <title>My Portfolio</title>
</head>
<body>

  <div class="header">
    <h1>GITHUB - About Me Page</h1>
  </div>

  <div class="container-fluid">

    <div class="row">

      <div class="col-md-4">
        <div class="left-column">
          <div class="image-container">
            <img src="Myself.jpg" alt="Justin Paul Ibus Timosa">
          </div>
          <h2>THE ONE AND ONLY</h2>
          <div class="social-cards">
            <button class="btn btn-primary">Anime</button>
            <button class="btn btn-primary">Playing</button>
            <button class="btn btn-primary">Sleeping</button>
            <button class="btn btn-primary">Eating</button>
          </div>
          <p>Social Media Accounts:</p>
          <div class="social-icons">
            <a href="https://www.facebook.com/justinpaul.timosa?mibextid=ZbWKwL" class="social-link"><img src="facebook.png" alt="Facebook"></a>
            <a href="https://github.com/justintimosa" class="social-link"><img src="github.jpg" alt="Github"></a>
          </div>
          <div class="tagline">
            <p>Hello There This is my Portfolio 🚀</p>
          </div>
          <div class="fun-facts">
            <h3>Facts about me</h3>
            <p>Loves playing online games, playing badminton, sleeping, and learning new things.</p>
          </div>
        </div>
      </div>

      <div class="col-md-8">
        <div class="right-column">
          <div class="about-me-header">
            <h2>About Me</h2>
          </div>
          <div class="about-me-content">
            <p>HI! I am Justin Paul I. Timosa, I'm an IT student and  a gamer.</p>
            <p><strong>Likes:</strong></p>
            <ul>
              <li>Watching anime</li>
              <li>Playing Badminton</li>
              <li>Playing Online games</li>
              <li>Eating</li>
              <li>Going outside</li>
              <li>Sleeping</li>
              <li>Reading Manga</li>
            </ul>
            <hr>
            <p>"Go confidently in the direction of your dreams. Live the life you have imagined.
              - Henry David Thoreau"</p>
          </div>

          <div class="programming-portfolio-header">
            <h3>&lt;Programming_Portfolio&gt;</h3>
          </div>

          <!-- Display projects -->
          <div class="row">
            <div class="col-md-6">
              <div class="project-card">
                <!-- Project 1 -->
                <div class="card-body project-card-body">
                  <h3 class="card-title">Project 1</h3>
                  <p class="card-text">Jquery+Bootstrap+Midterm exam</p>
                  <img class="card-img-top" src="TIMOSA_BootstrapJS_Act1.png" alt="Progress-Bar">
                  <a href="file:///C:/Users/User/Desktop/MYportfolio/TIMOSA_BootstrapJS_Act1.html" class="btn btn-primary view-project-link">View Project</a>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="project-card">
                <!-- Project 2 -->
                <div class="card-body project-card-body">
                  <h3 class="card-title">Project 2</h3>
                  <p class="card-text">Progress bar</p>
                  <img class="card-img-top" src="TIMOSA_BootstrapJS_Act1.png" alt="Register">
                  <a href="file:///C:/Users/User/Desktop/MYportfolio/TIMOSA_BootstrapJS_Act1.html" class="btn btn-primary view-project-link">View Project</a>
                </div>
              </div>
            </div>
          </div>

          <div class="row">
            <div class="col-md-6">
              <div class="project-card">
                <!-- Project 3 -->
                <div class="card-body project-card-body">
                  <h3 class="card-title">Project 3</h3>
                  <p class="card-text">Register</p>
                  <img class="card-img-top" src="REGISTER.png" alt="Records">
                  <a href="file:///C:/Users/User/Downloads/Perez,%20Estayan,%20Timosa_BootStrap-JavaScript_Act2-2.html" class="btn btn-primary view-project-link">View Project</a>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="project-card">
                <!-- Project 4 -->
                <div class="card-body project-card-body">
                  <h3 class="card-title">Project 4</h3>
                  <p class="card-text">Record</p>
                  <img class="card-img-top" src="RECORD.png" alt="Chinese Zodiacs">
                  <a href="file:///C:/Users/User/Downloads/Estayan,%20Perez,%20Timosa_BootstrapAct3.html" class="btn btn-primary view-project-link">View Project</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>

  </div>

</body>
</html>
