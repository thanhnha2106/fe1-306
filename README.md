<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor"
      crossorigin="anonymous">
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2"
      crossorigin="anonymous"></script>
    <link rel="stylesheet" href="./public/css/styles.css">

    <script src="https://kit.fontawesome.com/f6dce9b617.js"
      crossorigin="anonymous"></script>

    <title>Đề Án</title>


  </head>

  <body>
    <header>
      <div class="header-top">
        <nav class="navbar navbar-expand-lg navbar-dark bg-item">
          <div class="container-fluid">
            <img src="./public/image/logo.png" alt="">
            <button class="navbar-toggler" type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent" aria-expanded="false"
              aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                  <a class="nav-link active home-item" aria-current="page"
                    href="#"><span>Home</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">About
                  </a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">Services</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">Pricing</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">Clients</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">Team</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">Testimonials</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">Blog</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link menu-item" href="#">Contact</a>
                </li>


              </ul>

            </div>
          </div>
        </nav>
      </div>
      <div class="header-banner">
        <div id="carouselExampleCaptions" class="carousel slide"
          data-bs-ride="false">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="0" class="active" aria-current="true"
              aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="2" aria-label="Slide 3"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="public/image/banner1.jpg" class="img-banner d-block
                w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h2>Professional approach</h2>
                <p>We professionally support individual and business</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="public/image/banner2.jpg" class="img-banner d-block
                w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h2>Professional engineers</h2>
                <p>Our best expert will handle your issue</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="public/image/banner3.jpg" class="img-banner d-block
                w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h2>Happy customers</h2>
                <p>Hundred of happy customers that we helped</p>
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button"
            data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button"
            data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </header>
    <div class="content">
      <div class="container">
        <div class="h1-item"></div>
        <div class="row">
          <div class="col-md-6">
            <div class="h1-item"><h1>About</h1>

              <p>Our company has many years of experience in the IT industry,
                offering
                reliable services. We offer PC and laptop repair, data recovery,
                maintenance
                and more. We provide services to both individual and business
                clients.
              </p>
            </div>
            <div class="row">
              <div class="col-md-12 fix-flex">
                <div class="icon">
                  <i class="fa-solid fa-screwdriver-wrench"></i>
                </div>
                <div class="span-item">
                  <p><span>no fix no fee</span> <br>
                    We will not charge you if
                    we cannot find a solution to your problem</p>
                </div>
              </div>
              <div class="col-md-12 fix-flex">
                <div class="icon">
                  <i class="fa-solid fa-eye-slash"></i>
                </div>
                <div class="span-item">
                  <p><span>no hidden charges</span> <br>
                    We will explain everything in advance, there will be no
                    surprise</p>
                </div>
              </div>
              <div class="col-md-12 fix-flex">
                <div class="icon">
                  <i class="fa-regular fa-building"></i>
                </div>
                <div class="span-item">
                  <p><span>home and office visit</span> <br>
                    We can visit you at your home or office
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 img-item">
            <img src="./public/image/about.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="services">
        <h1>Services</h1>
        <div class="row bg-services">
          <div class="col-md-4 center-icon span-item">
            <i class="fa-solid fa-laptop icon-services"></i>
            <p><span>PC and laptops repair</span> <br>
              Whether your PC isn't working as expected or <br>
              won't turn on, our engineers will solve the <br>
              problem</p>

          </div>
          <div class="col-md-4 center-icon span-item">
            <i class="fa-brands fa-usb icon-services"></i>
            <p><span>data recovery</span> <br>
              Our experts can deal with any type of data <br>
              damage on your hard drive disk, both logical <br>
              and physical</p>

          </div>
          <div class="col-md-4 center-icon span-item">
            <i class="fa-solid fa-fingerprint icon-services"></i>
            <p><span>security & virus removal</span> <br>
              We offer PC security checks, network security <br>
              check and virus/malware/spyware removal <br>
              services</p>

          </div>
        </div>
      </div>
      <div class="Pricing">
        <h1>Pricing</h1>
        <div class="container">
          <div class="row">
            <div class="col-md-6">
              <div class="Hardware"><h3>Hardware issues</h3></div>
              <div class="row">
                <div class="col-9 money">
                  <p>
                    Repairs after spilling water <br>
                    Broken laptop screen, keyboard or other replacement <br>
                    parts <br>
                    Poor battery charging <br>
                    No battery charging <br>
                    Laptop doesn’t turn on <br>
                    Power socket replacement <br>
                    Repair of an overheating computer laptop <br>
                  </p>

                </div>
                <div class="col-3 money m-right">
                  <p style="font-weight: 600;">
                    80$ <br>
                    60$ <br> <br>
                    50$ <br>
                    50$ <br>
                    50$ <br>
                    60$ <br>
                    60$
                  </p>

                </div>

              </div>

            </div>
            <div class="col-md-6">
              <div class="Hardware"><h3>Software issues</h3></div>
              <div class="row">
                <div class="col-9 money">
                  <p>
                    Software installation <br>
                    Upgrade computer <br>
                    Viruses/malware/annoying software removal <br>
                    Speed up slow running computer <br>
                    password reset <br>
                    Lost data recovery <br>
                    Internet connection repair <br>
                  </p>
                </div>
                <div class="col-3 money m-right">
                  <p style="font-weight: 600;">
                    40$ <br>
                    60$ <br>
                    60$ <br>
                    50$ <br>
                    40$ <br>
                    300$ <br>
                    300$
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="OurClients">
        <h1>Our Clients</h1>
        <div class="container">
          <div class="row">
            <div class="col-lg-6 col-xl-3 img-our">
              <img class="img-fluid" src="./public/image/client1.png" alt="">
            </div>
            <div class="col-lg-6 col-xl-3 img-our">
              <img class="img-fluid client2" src="./public/image/client2.png"
                alt="">
            </div>
            <div class="col-lg-6 col-xl-3 img-our">
              <img class="img-fluid" src="./public/image/client3.png" alt="">
            </div>
            <div class="col-lg-6 col-xl-3 img-our">
              <img class="img-fluid" src="./public/image/client4.png" alt="">
            </div>

          </div>
        </div>


      </div>
      <div class="Meetourteam">
        <h1>Meet our team</h1>
        <div class="container">
          <div class="row">
            <div class="col-lg-6 col-xl-3 img-team">

              <div class="img-meet">
                <img class="img-fluid" src="./public/image/person1.jpg" alt="">
                <div class="name">
                  <div class="em"> <span>Peter Philips</span></div>
                  <div class="em"> <i>Team Leader</i></div>
                  <div class="em1">0 800 123 456 789</div>
                  <div class="em1">peter.philips@example.com</div>
                </div>
              </div>


            </div>
            <div class="col-lg-6 col-xl-3 img-team">
              <div class="img-meet">
                <img class="img-fluid" src="./public/image/person2.jpg" alt="">
                <div class="name">
                  <div class="em"> <span>David Brown</span></div>
                  <div class="em"> <i>Technician</i></div>
                  <div class="em1">0 800 123 456 789</div>
                  <div class="em1">david.brown@example.com</div>
                </div>
              </div>


            </div>
            <div class="col-lg-6 col-xl-3 img-team">
              <div class="img-meet">
                <img class="img-fluid" src="./public/image/person3.jpg" alt="">
                <div class="name">
                  <div class="em"> <span>Raphael Williams</span></div>
                  <div class="em"> <i>Technician</i></div>
                  <div class="em1">0 800 123 456 789</div>
                  <div class="em1">raphael.williams@example.com</div>
                </div>
              </div>

            </div>
            <div class="col-lg-6 col-xl-3 img-team">
              <div class="img-meet">
                <img class="img-fluid" src="./public/image/person4.jpg" alt="">
                <div class="name">
                  <div class="em"> <span>Thomas Wilson</span></div>
                  <div class="em"> <i>Technician</i></div>
                  <div class="em1">0 800 123 456 789</div>
                  <div class="em1">thomas.wilson@example.co</div>
                </div>
              </div>

            </div>

          </div>
        </div>


      </div>
      <div class="Whatpeoplesay">
        <h1>What people say</h1>
        <div class="container">
          <div class="row">
            <div class="col-lg-6 col-xl-3">
              <div class="border-what">
                <div class="img-small">
                  <img class="img-circle" src="./public/image/testimonials1.jpg"
                    alt="">
                  <div class="writing">
                    <div class="writ1">John Smith</div>
                    <div class="writ2"><i>Personal customer</i></div>
                    <div class="star">
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                    </div>

                  </div>
                </div>
                <p>These guys did a great job in fixing my laptop. I will refer
                  everyone I know.</p>
              </div>


            </div>
            <div class="col-lg-6 col-xl-3">
              <div class="border-what">
                <div class="img-small">
                  <img class="img-circle" src="./public/image/testimonials2.jpg"
                    alt="">
                  <div class="writing">
                    <div class="writ1">Scarlett Jackson</div>
                    <div class="writ2"><i>Business owner</i></div>
                    <div class="star">
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                    </div>

                  </div>
                </div>
                <p>A very polite, professional and a nice team of experts. I
                  STRONGLY recommend!</p>
              </div>


            </div>
            <div class="col-lg-6 col-xl-3">
              <div class="border-what">
                <div class="img-small">
                  <img class="img-circle" src="./public/image/testimonials3.jpg"
                    alt="">
                  <div class="writing">
                    <div class="writ1">Katherine Spencer</div>
                    <div class="writ2"><i>Personal customer</i></div>
                    <div class="star">
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                    </div>

                  </div>
                </div>
                <p>Very quick and great service, good communication. Helped me
                  find out what was wrong with my PC.</p>
              </div>

            </div>
            <div class="col-lg-6 col-xl-3">
              <div class="border-what">
                <div class="img-small">
                  <img class="img-circle" src="./public/image/testimonials4.jpg"
                    alt="">
                  <div class="writing">
                    <div class="writ1">Craig Cooper</div>
                    <div class="writ2"><i>Bussiness owner</i></div>
                    <div class="star">
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i>
                    </div>

                  </div>
                </div>
                <p>Absolutely great IT Support, couldn't ask for better.</p></div>
            </div>
          </div>
        </div>
      </div>
      <div class="Latestblogposts">
        <h1>Latest blog posts</h1>
        <div class="container">
          <div class="row" style="justify-content: center;">
            <div class="col-lg-6 col-xl-4">
              <div class="border-late">
                <div class="board">
                  <img class="img-big" src="./public/image/post1.jpg" alt="">
                  <div class="board1">
                    <p><i class="fa-regular fa-clock"></i><span>March 3, 2021</span>
                      <i class="fa-regular fa-comment"></i><span>3 comments</span></p>
                  </div>
                </div>
                <div class="board2">
                  <p><span>How to upgrade your laptop</span></p>
                  <p class="br">
                    Almost every laptop and portable computer allow a user to
                    upgrade the RAM memory and hard drive in the computer.
                    <br>
                  </p>
                  <a href="">read more</a>
                </div>
              </div>
            </div>
            <div class="col-lg-6 col-xl-4">
              <div class="border-late">
                <div class="board">
                  <img class="img-big" src="./public/image/post2.jpg" alt="">
                  <div class="board1">
                    <p><i class="fa-regular fa-clock"></i><span>March 3, 2021</span>
                      <i class="fa-regular fa-comment"></i><span>2 comments</span></p>
                  </div>
                </div>
                <div class="board2">
                  <p><span>Extend battery life</span></p>
                  <p class="br">
                    There are some valuable ways to improve or extend the
                    battery
                    life such as power saving mode, airplane mode, changing
                    screen
                    brightness etc. <br>
                  </p>
                  <a href="">read more</a>
                </div>
              </div>
            </div>

            <div class="col-lg-6 col-xl-4">
              <div class="border-late">
                <div class="board">
                  <img class="img-big" src="./public/image/post3.jpg" alt="">
                  <div class="board1">
                    <p><i class="fa-regular fa-clock"></i><span>March 3, 2021</span>
                      <i class="fa-regular fa-comment"></i> <span>5 comments</span></p>
                  </div>
                </div>
                <div class="board2">
                  <p><span>How to access phone with broken screen</span></p>
                  <p class="br">
                    Even if you broke your screen and can't use your
                    touchscreen,
                    there are still a couple of ways you can access and
                    recover
                    data from your device. <br>

                  </p>
                  <a href="">read more</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="map">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d22556.233955585394!2d-117.21505925996809!3d32.81865266947334!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xa2539b606d399b!2sMarshalls!5e0!3m2!1sen!2spl!4v1640362900920!5m2!1sen!2spl"
          style="border:0;" allowfullscreen="" class="mt-4 tmp-map"
          title="google map" loading="lazy">
        </iframe>
      </div>

      <div class="get">
        <div class="container">
          <div class="row">
            <div class="col-md-6">
              <h5>Get social</h5>
              <div class="row">

                <div class="col-md icon-get">
                  <i class="fa-brands fa-youtube"></i>
                  <i class="fa-brands fa-linkedin"></i>
                  <i class="fa-brands fa-twitter"></i>
                  <i class="fa-brands fa-facebook"></i>
                  <i class="fa-brands fa-instagram"></i>
                </div>

              </div>


              <h5>Phone</h5>
              <div class="row">
                <div class="icon-get">
                  <i class="fa-solid fa-phone"></i><p>+1 123-456-7890</p>
                </div>
              </div>


              <h5>E-mail</h5>
              <div class="row">
                <div class="icon-get">
                  <i class="fa-solid fa-envelope"></i><p>offline@example.com</p>
                </div>
              </div>


              <h5>Address</h5>
              <div class="row">
                <div class="icon-get">
                  <i class="fa-solid fa-location-dot"></i><p>4209 Genesee Ave,
                    San Diego, USA</p>
                </div>
              </div>


              <div class="Workinghours">
                <h3 class="wh">Working hours</h3>
                <div class="row">
                  <div class="col-6 down">
                    <p>
                      Monday <br>
                      Tuesday <br>
                      Wednesday <br>
                      Thursday <br>
                      Friday <br>
                      Saturday <br>
                      Sunday <br>

                    </p>
                  </div>
                  <div class="col-6 down">
                    <p>
                      08:00 - 20:00 <br>
                      08:00 - 20:00 <br>
                      08:00 - 20:00 <br>
                      08:00 - 20:00 <br>
                      08:00 - 20:00 <br>
                      08:00 - 20:00 <br>
                      08:00 - 20:00 <br>
                    </p>

                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="Getintouch">
                <h3 class="wh">Get in touch</h3>
                <p>We are available 24/7 by e-mail or telephone. You can also
                  use our quick contact form to get in touch with us.
                </p>
              </div>
              <div class="form">
                <form class="color-form" action="#" method="post">
                  <label>Phone<br>
                    <input type="text" name="phone" id="phone"
                      placeholder="  +1 111 111 11111">
                  </label>
                  <br>

                  <label>Email address<br>
                    <input type="text" name="email" id="email"
                      placeholder="  name@example.com">
                  </label>
                  <br>

                  <label>Content <br>
                    <textarea name="content" id="content"></textarea>
                  </label>
                  <br>

                  <button type="submit" class="btn btn-primary" id="send">Send</button>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>

</html>
