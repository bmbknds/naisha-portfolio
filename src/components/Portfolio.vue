<template>
  <div>
    <div class="body">
      <header id="header"
              class="header-floating "
              data-plugin-options="{'stickyEnabled': false, 'stickyEnableOnBoxed': false, 'stickyEnableOnMobile': false, 'stickyStartAt': 0, 'stickySetTop': '60px', 'stickyChangeLogo': false}">
        <div class="header-body">
          <div class="header-container container">
            <div class="header-row">
              <div class="header-column">
                <div class="header-row">
                  <div class="header-nav pt-xs">
                    <button class="btn header-btn-collapse-nav"
                            data-toggle="collapse"
                            data-target=".header-nav-main">
                      <i class="fa fa-bars"></i>
                    </button>
                    <div class="header-nav-main collapse">
                      <nav class="wrapper-spy">
                        <ul class="nav"
                            id="mainNav">
                          <li>
                            <a data-hash
                               href="#about-me"
                               class="text-color-dark background-color-primary">
                              <i class="icon-home icons"></i>
                              <span class="custom-tooltip">About Me</span>
                            </a>
                          </li>
                          <li>
                            <a data-hash
                               href="#experience"
                               class="text-color-dark background-color-primary">
                              <i class="icon-eye icons"></i>
                              <span class="custom-tooltip">Experience</span>
                            </a>
                          </li>
                          <li>
                            <a data-hash
                               href="#education"
                               class="text-color-dark background-color-primary">
                              <i class="icon-briefcase icons"></i>
                              <span class="custom-tooltip">Education</span>
                            </a>
                          </li>
                          <li>
                            <a data-hash
                               href="#skills"
                               class="text-color-dark background-color-primary">
                              <i class="icon-graduation icons"></i>
                              <span class="custom-tooltip">Skills</span>
                            </a>
                          </li>
                          <li>
                            <a data-hash
                               href="#portfolio"
                               class="text-color-dark background-color-primary">
                              <i class="icon-diamond icons"></i>
                              <span class="custom-tooltip">Portfolio</span>
                            </a>
                          </li>
                          <li>
                            <a data-hash
                               href="#recommendations"
                               class="text-color-dark background-color-primary">
                              <i class="icon-pencil icons"></i>
                              <span class="custom-tooltip">Recommendations</span>
                            </a>
                          </li>
                          <li>
                            <a data-hash
                               href="#blog"
                               class="text-color-dark background-color-primary">
                              <i class="icon-bubbles icons"></i>
                              <span class="custom-tooltip">Blog</span>
                            </a>
                          </li>
                          <li>
                            <a data-hash
                               href="#say-hello"
                               class="text-color-dark background-color-primary">
                              <i class="icon-envelope-open icons"></i>
                              <span class="custom-tooltip">Say Hello</span>
                            </a>
                          </li>
                        </ul>
                      </nav>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </header>
      <div role="main"
           class="main">

        <section id="about-me"
                 class="section section-no-border section-parallax custom-section-padding-1 custom-position-1 custom-xs-bg-size-cover m-none"
      
                 data-plugin-parallax
                 data-plugin-options="{'speed': 1.5}"
                 data-image-src="https://scontent.fhan5-5.fna.fbcdn.net/v/t1.0-9/13726629_378618865831021_6801776781224046837_n.jpg?_nc_cat=0&oh=331785e5c639821e3583ae494f986596&oe=5BA8631F">
          <div class="container">
            <div class="row">
              <div class="col-md-4 col-sm-4 col-xs-10 col-sm-offset-0 col-xs-offset-1 custom-sm-margin-bottom-1">
                <img src="https://scontent.fhan5-5.fna.fbcdn.net/v/t1.0-9/18671130_445947035764870_4718051534662975243_n.jpg?_nc_cat=0&oh=c5861d1ed582e07d753f77f0f33291ff&oe=5BE0C2DC"
              
                     class="img-responsive custom-border custom-image-position-2 custom-box-shadow-4"
              
                     alt />
              </div>
              <div class="col-md-5 col-sm-8">
                <h1 class="text-color-primary custom-font-size-1">Adam Doe</h1>
                <p class="text-color-light font-weight-normal custom-font-size-2 custom-margin-bottom-1">Chief Product Officer at Okler Themes</p>
                <span class="custom-about-me-infos">
                  <span class="custom-text-color-1 text-uppercase">Greater New York area</span>
                  <span class="custom-text-color-1 text-uppercase mb-md">Information Technology &amp; Services</span>
                  <span class="custom-text-color-1 text-uppercase">
                    <strong class="text-color-light">Previous: </strong>
                    Front-End Developer at Porto
                    <a data-hash
                       href="#experience"
                       class="btn btn-tertiary text-uppercase custom-btn-style-1 text-xs ml-sm">View More</a>
                  </span>
                  <span class="custom-text-color-1 text-uppercase">
                    <strong class="text-color-light">Education: </strong>
                    Porto School
                    <a data-hash
                       href="#education"
                       class="btn btn-tertiary text-uppercase custom-btn-style-1 text-xs ml-sm">View More</a>
                  </span>
                </span>
              </div>
              <div class="col-md-3 hidden-sm hidden-xs">
                <img src="img/demos/resume/about-me/mouse.png"
                     custom-anim
                     class="img-responsive"
                     alt />
              </div>
            </div>
          </div>
          <ul class="social-icons custom-social-icons">
            <li class="social-icons-facebook">
              <a href="http://www.facebook.com/"
                 target="_blank"
                 title="Facebook">
                <i class="fa fa-facebook"></i>
              </a>
            </li>
            <li class="social-icons-twitter">
              <a href="http://www.twitter.com/"
                 target="_blank"
                 title="Twitter">
                <i class="fa fa-twitter"></i>
              </a>
            </li>
            <li class="social-icons-youtube">
              <a href="http://www.youtube.com/"
                 target="_blank"
                 title="Youtube">
                <i class="fa fa-youtube"></i>
              </a>
            </li>
          </ul>
        </section>
        <div class="custom-about-me-links">
          <div class="container">
            <div class="row">
              <div class="col-md-3 col-md-offset-4 col-sm-4 center custom-xs-border-bottom p-none">
                <a data-hash
                   href="#say-hello"
                   class="text-decoration-none">
                  <span class="custom-nav-button text-color-dark">
                    <i class="icon-earphones-alt icons text-color-primary"></i>
                    Contact Information
                  </span>
                </a>
              </div>
              <div class="col-md-2 col-sm-4 center custom-xs-border-bottom p-none">
                <a data-hash
                   href="#say-hello"
                   class="text-decoration-none">
                  <span class="custom-nav-button custom-divisors text-color-dark">
                    <i class="icon-envelope-open icons text-color-primary"></i>
                    Send Message
                  </span>
                </a>
              </div>
              <div class="col-md-3 col-sm-4 center p-none">
                <a href="#"
                   class="text-decoration-none">
                  <span class="custom-nav-button text-color-dark">
                    <i class="icon-cloud-download icons text-color-primary"></i>
                    Download Resume
                  </span>
                </a>
              </div>
            </div>
          </div>
        </div>
        <section class="section section-no-border background-color-light m-none">
          <div class="container">
            <div class="row">
              <div class="col-md-12">

                <div class="custom-box-details background-color-light custom-box-shadow-1 col-md-6 ml-xlg mb-xlg pull-right clearfix">
                  <h4>Personal Details</h4>
                  <div class="col-md-6 col-sm-6 p-none">
                    <ul class="custom-list-style-1 p-none">
                      <li>
                        <span class="text-color-dark">Birthday:</span>
                        <span class="custom-text-color-2">1990 October 2</span>
                      </li>
                      <li>
                        <span class="text-color-dark">Marital:</span>
                        <span class="custom-text-color-2">Single</span>
                      </li>
                      <li>
                        <span class="text-color-dark">Nationality:</span>
                        <span class="custom-text-color-2">American</span>
                      </li>
                    </ul>
                  </div>
                  <div class="col-md-6 col-sm-6 p-none">
                    <ul class="custom-list-style-1 p-none">
                      <li>
                        <span class="text-color-dark">Skype:</span>
                        <span class="custom-text-color-2">
                          <a class="custom-text-color-2"
                             href="skype:yourskype?chat">yourskype</a>
                        </span>
                      </li>
                      <li>
                        <span class="text-color-dark">PHONE:</span>
                        <span class="custom-text-color-2">
                          <a class="custom-text-color-2"
                             href="tel:123456789">123-456-789</a>
                        </span>
                      </li>
                      <li>
                        <span class="text-color-dark">EMAIL:</span>
                        <span class="custom-text-color-2">
                          <a class="custom-text-color-2"
                             href="mailto:info@domain.com">info@domain.com</a>
                        </span>
                      </li>
                    </ul>
                  </div>
                </div>

                <h2 class="text-color-quaternary font-weight-extra-bold text-uppercase">About Me</h2>

                <p class="custom-text-color-2">Donec id elit non mi porta gravida at eget metus. Fusce dapibus,
                  tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum
                  massa justo sit amet risus. Etiam porta sem malesuada magna mollis
                  euismod. Donec sed odio dui.</p>

                <div class="about-me-more"
                     id="aboutMeMore">
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam
                    tincidunt nulla tortor, a imperdiet enim tristique nec. Nulla
                    lobortis leo eget metus dapibus sodales. Sed placerat vitae dui
                    vitae vehicula. Quisque in tincidunt ligula, nec dignissim arcu.
                    Praesent aliquam velit vel libero dictum, non sollicitudin lectus
                    mollis. Morbi sollicitudin auctor gravida. Vivamus vitae dui
                    non lorem euismod pretium. Morbi congue sem sed ex iaculis, nec
                    mattis felis pretium. Nullam molestie libero id odio blandit
                    sodales. Suspendisse non mauris et felis molestie placerat aliquet
                    a risus. Aliquam ac leo tempus, hendrerit eros mollis, gravida
                    est.
                  </p>

                  <p>Proin euismod ipsum a tellus condimentum dapibus. Integer porttitor
                    felis elit, eget rutrum ligula commodo quis. Praesent ultricies
                    neque eu mi congue blandit. Nulla feugiat feugiat aliquet. Morbi
                    sed mattis erat. Nullam scelerisque molestie eros, id tristique
                    felis iaculis non. Duis pellentesque neque eget iaculis varius.
                    Donec at nisl semper, aliquam est id, tincidunt lacus. Donec
                    at erat purus.</p>

                  <p>Morbi tincidunt nunc non diam porta, at fermentum orci bibendum.
                    Donec arcu nisi, ornare nec commodo vitae, sollicitudin sed magna.
                    Cras sit amet justo et nulla pulvinar laoreet. Phasellus scelerisque,
                    metus id posuere vulputate, diam tellus iaculis sapien, eget
                    scelerisque ipsum libero convallis velit. Duis lorem ligula,
                    faucibus quis tellus nec, fringilla ultricies leo. Etiam tempus
                    congue magna. Suspendisse porta dictum tortor, eu volutpat ipsum
                    eleifend nec. Aliquam dapibus lorem luctus, cursus libero imperdiet,
                    mattis nunc. Sed in ipsum diam. Quisque efficitur metus purus,
                    vitae fermentum lacus venenatis id.</p>
                </div>

                <a id="aboutMeMoreBtn"
                   class="btn btn-tertiary text-uppercase custom-btn-style-1 text-xs">View More</a>

              </div>
            </div>
          </div>
        </section>
        <section id="experience"
                 class="section section-secondary section-no-border m-none">
          <div class="container">
            <div class="row">
              <div class="col-md-12">
                <h2 class="text-color-quaternary text-uppercase font-weight-extra-bold">Experience</h2>
                <section class="timeline custom-timeline"
                         id="timeline">
                  <div class="timeline-body">
                    <article class="timeline-box right custom-box-shadow-2">
                      <div class="experience-info col-md-3 col-sm-5 match-height background-color-primary">
                        <span class="from text-color-dark text-uppercase">
                          From
                          <span class="font-weight-semibold">Sep 2012</span>
                        </span>
                        <span class="to text-color-dark text-uppercase">
                          To
                          <span class="font-weight-semibold">Present</span>
                        </span>
                        <p class="text-color-dark">(3 Years 9 Months)</p>
                        <span class="company text-color-dark font-weight-semibold">
                          Okler Themes
                          <span class="company-location text-color-dark font-weight-normal text-uppercase">Greater New York</span>
                        </span>
                      </div>
                      <div class="experience-description col-md-9 col-sm-7 match-height background-color-light">
                        <h4 class="text-color-dark font-weight-semibold">Chief Product Officer</h4>
                        <p class="custom-text-color-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                          Etiam tincidunt nulla tortor, a imperdiet enim tristique
                          nec. Nulla lobortis leo eget metus dapibus sodales. Sed
                          placerat vitae dui vitae vehicula. Quisque in tincidunt
                          ligula, nec dignissim arcu.</p>
                      </div>
                    </article>
                    <article class="timeline-box right custom-box-shadow-2">
                      <div class="experience-info col-md-3 col-sm-5 match-height background-color-primary">
                        <span class="from text-color-dark text-uppercase">
                          From
                          <span class="font-weight-semibold">Sep 2012</span>
                        </span>
                        <span class="to text-color-dark text-uppercase">
                          To
                          <span class="font-weight-semibold">Present</span>
                        </span>
                        <p class="text-color-dark">(3 Years 9 Months)</p>
                        <span class="company text-color-dark font-weight-semibold">
                          Okler Themes
                          <span class="company-location text-color-dark font-weight-normal text-uppercase">Greater New York</span>
                        </span>
                      </div>
                      <div class="experience-description col-md-9 col-sm-7 match-height background-color-light">
                        <h4 class="text-color-dark font-weight-semibold">Chief Product Officer</h4>
                        <p class="custom-text-color-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                          Etiam tincidunt nulla tortor, a imperdiet enim tristique
                          nec. Nulla lobortis leo eget metus dapibus sodales. Sed
                          placerat vitae dui vitae vehicula. Quisque in tincidunt
                          ligula, nec dignissim arcu.</p>
                      </div>
                    </article>
                    <article class="timeline-box right custom-box-shadow-2">
                      <div class="experience-info col-md-3 col-sm-5 match-height background-color-primary">
                        <span class="from text-color-dark text-uppercase">
                          From
                          <span class="font-weight-semibold">Sep 2012</span>
                        </span>
                        <span class="to text-color-dark text-uppercase">
                          To
                          <span class="font-weight-semibold">Present</span>
                        </span>
                        <p class="text-color-dark">(3 Years 9 Months)</p>
                        <span class="company text-color-dark font-weight-semibold">
                          Okler Themes
                          <span class="company-location text-color-dark font-weight-normal text-uppercase">Greater New York</span>
                        </span>
                      </div>
                      <div class="experience-description col-md-9 col-sm-7 match-height background-color-light">
                        <h4 class="text-color-dark font-weight-semibold">Chief Product Officer</h4>
                        <p class="custom-text-color-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                          Etiam tincidunt nulla tortor, a imperdiet enim tristique
                          nec. Nulla lobortis leo eget metus dapibus sodales. Sed
                          placerat vitae dui vitae vehicula. Quisque in tincidunt
                          ligula, nec dignissim arcu.</p>
                      </div>

                    </article>
                    <article class="timeline-box right custom-box-shadow-2">
                      <div class="experience-info col-md-3 col-sm-5 match-height background-color-primary">
                        <span class="from text-color-dark text-uppercase">
                          From
                          <span class="font-weight-semibold">Sep 2012</span>
                        </span>
                        <span class="to text-color-dark text-uppercase">
                          To
                          <span class="font-weight-semibold">Present</span>
                        </span>
                        <p class="text-color-dark">(3 Years 9 Months)</p>
                        <span class="company text-color-dark font-weight-semibold">
                          Okler Themes
                          <span class="company-location text-color-dark font-weight-normal text-uppercase">Greater New York</span>
                        </span>
                      </div>
                      <div class="experience-description col-md-9 col-sm-7 match-height background-color-light">
                        <h4 class="text-color-dark font-weight-semibold">Chief Product Officer</h4>
                        <p class="custom-text-color-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                          Etiam tincidunt nulla tortor, a imperdiet enim tristique
                          nec. Nulla lobortis leo eget metus dapibus sodales. Sed
                          placerat vitae dui vitae vehicula. Quisque in tincidunt
                          ligula, nec dignissim arcu.</p>
                      </div>

                    </article>
                    <article class="timeline-box right custom-box-shadow-2">
                      <div class="experience-info col-md-3 col-sm-5 match-height background-color-primary">
                        <span class="from text-color-dark text-uppercase">
                          From
                          <span class="font-weight-semibold">Sep 2012</span>
                        </span>
                        <span class="to text-color-dark text-uppercase">
                          To
                          <span class="font-weight-semibold">Present</span>
                        </span>
                        <p class="text-color-dark">(3 Years 9 Months)</p>
                        <span class="company text-color-dark font-weight-semibold">
                          Okler Themes
                          <span class="company-location text-color-dark font-weight-normal text-uppercase">Greater New York</span>
                        </span>
                      </div>
                      <div class="experience-description col-md-9 col-sm-7 match-height background-color-light">
                        <h4 class="text-color-dark font-weight-semibold">Chief Product Officer</h4>
                        <p class="custom-text-color-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                          Etiam tincidunt nulla tortor, a imperdiet enim tristique
                          nec. Nulla lobortis leo eget metus dapibus sodales. Sed
                          placerat vitae dui vitae vehicula. Quisque in tincidunt
                          ligula, nec dignissim arcu.</p>
                      </div>

                    </article>
                    <div class="timeline-bar"></div>
                  </div>
                </section>
              </div>
            </div>
          </div>
        </section>
        <section id="education"
                 class="section section-no-border custom-background-color-1 m-none">
          <div class="container">
            <div class="row">
              <div class="col-md-12">
                <h2 class="text-color-quaternary text-uppercase font-weight-extra-bold m-none">Education</h2>
                <div class="owl-carousel nav-bottom custom-carousel-style-1 custom-item-padding custom-dots-style-1"
              
                     data-plugin-options="{'items': 1, 'loop': false, 'dots': true, 'nav': false}">
                  <div>
                    <div class="col-md-6 col-sm-6">
                      <div class="custom-box-details-2 background-color-light custom-box-shadow-3">
                        <i class="icon-graduation icons text-color-primary"></i>
                        <h4 class="font-weight-semibold text-color-dark m-none">Porto University</h4>
                        <p class="custom-text-color-2 mb-xs">Master of Information Technology</p>
                        <strong class="text-color-primary">2001-2015</strong>
                      </div>
                    </div>
                    <div class="col-md-6 col-sm-6">
                      <div class="custom-box-details-2 background-color-light custom-box-shadow-3">
                        <i class="icon-graduation icons text-color-primary"></i>
                        <h4 class="font-weight-semibold text-color-dark m-none">Porto University</h4>
                        <p class="custom-text-color-2 mb-xs">Master of Information Technology</p>
                        <strong class="text-color-primary">2001-2015</strong>
                      </div>
                    </div>
                  </div>
                  <div>
                    <div class="col-md-6 col-sm-6">
                      <div class="custom-box-details-2 background-color-light custom-box-shadow-3">
                        <i class="icon-graduation icons text-color-primary"></i>
                        <h4 class="font-weight-semibold text-color-dark m-none">Porto University</h4>
                        <p class="custom-text-color-2 mb-xs">Master of Information Technology</p>
                        <strong class="text-color-primary">2001-2015</strong>
                      </div>
                    </div>
                    <div class="col-md-6 col-sm-6">
                      <div class="custom-box-details-2 background-color-light custom-box-shadow-3">
                        <i class="icon-graduation icons text-color-primary"></i>
                        <h4 class="font-weight-semibold text-color-dark m-none">Porto University</h4>
                        <p class="custom-text-color-2 mb-xs">Master of Information Technology</p>
                        <strong class="text-color-primary">2001-2015</strong>
                      </div>
                    </div>
                  </div>
                  <div>
                    <div class="col-md-6 col-sm-6">
                      <div class="custom-box-details-2 background-color-light custom-box-shadow-3">
                        <i class="icon-graduation icons text-color-primary"></i>
                        <h4 class="font-weight-semibold text-color-dark m-none">Porto University</h4>
                        <p class="custom-text-color-2 mb-xs">Master of Information Technology</p>
                        <strong class="text-color-primary">2001-2015</strong>
                      </div>
                    </div>
                    <div class="col-md-6 col-sm-6">
                      <div class="custom-box-details-2 background-color-light custom-box-shadow-3">
                        <i class="icon-graduation icons text-color-primary"></i>
                        <h4 class="font-weight-semibold text-color-dark m-none">Porto University</h4>
                        <p class="custom-text-color-2 mb-xs">Master of Information Technology</p>
                        <strong class="text-color-primary">2001-2015</strong>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section id="skills"
                 class="section section-no-border background-color-light m-none">
          <div class="container">
            <div class="row custom-sm-flex-order">
              <div class="col-md-4 col-sm-6 col-xs-12">
                <h2 class="text-color-quaternary text-uppercase font-weight-extra-bold">Skills & Language</h2>
                <div class="progress-bars custom-progress-bars">
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>Start Up</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         :data-appear-progress-animation="test"></div>
                  </div>
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>Innovation</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         :data-appear-progress-animation="test"
                         data-appear-animation-delay="300"></div>
                  </div>
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>Products</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         data-appear-progress-animation="70%"
                         data-appear-animation-delay="600"></div>
                  </div>
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>CSS</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         data-appear-progress-animation="90%"
                         data-appear-animation-delay="900"></div>
                  </div>
                </div>
              </div>
              <div class="col-md-4 col-sm-6 col-xs-12">
                <div class="progress-bars custom-progress-bars custom-md-margin-top-1">
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>Javascript</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         data-appear-progress-animation="60%"></div>
                  </div>
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>Business</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         data-appear-progress-animation="80%"
                         data-appear-animation-delay="300"></div>
                  </div>
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>E-commerce</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         data-appear-progress-animation="70%"
                         data-appear-animation-delay="600"></div>
                  </div>
                  <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm">
                    <span>Creative</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar"
                         data-appear-progress-animation="90%"
                         data-appear-animation-delay="900"></div>
                  </div>
                </div>
              </div>
              <div class="col-md-4 col-sm-6 col-xs-12">
                <div class="custom-box-details background-color-light custom-box-shadow-1">
                  <h4 class="text-color-dark">Languages</h4>
                  <ul class="custom-list-style-1 p-none">
                    <li>
                      <span class="font-weight-semibold custom-max-width-1 text-color-dark"><img src="img/blank.gif"
                             class="flag flag-us mr-xs"
                             alt="English">English:</span>
                      <span class="custom-text-color-2">Advanced</span>
                    </li>
                    <li>
                      <span class="font-weight-semibold custom-max-width-1 text-color-dark"><img src="img/blank.gif"
                             class="flag flag-es mr-xs"
                             alt="Spanish">Spanish:</span>
                      <span class="custom-text-color-2">Advanced</span>
                    </li>
                    <li>
                      <span class="font-weight-semibold custom-max-width-1 text-color-dark"><img src="img/blank.gif"
                             class="flag flag-fr mr-xs"
                             alt="Française">French:</span>
                      <span class="custom-text-color-2">Basic</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section id="portfolio"
                 class="section section-no-border background-color-secondary m-none">
          <div class="container">
            <div class="row">
              <div class="col-md-12">
                <h2 class="text-color-quaternary font-weight-extra-bold text-uppercase">Portfolio</h2>
                <ul class="nav nav-pills sort-source custom-nav-sort mb-xlg"
                    data-sort-id="portfolio"
                    data-option-key="filter">
                  <li data-option-value="*"
                      class="active">
                    <a href="#">Show All</a>
                  </li>
                  <li data-option-value=".websites">
                    <a href="#">Websites</a>
                  </li>
                  <li data-option-value=".logos">
                    <a href="#">Logos</a>
                  </li>
                  <li data-option-value=".brands">
                    <a href="#">Brands</a>
                  </li>
                </ul>
                <div class="row">
                  <div class="sort-destination-loader sort-destination-loader-showing">
                    <ul class="image-gallery sort-destination lightbox"
                        data-sort-id="portfolio"
                        data-plugin-options="{'delegate': 'a.lightbox-portfolio', 'type': 'image', 'gallery': {'enabled': true}}">
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-1.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-1.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item logos">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-2.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-2.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item brands">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-3.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-3.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-4.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-4.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-5.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-5.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-6.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-6.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-7.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-7.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                      <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                        <div class="image-gallery-item">
                          <a href="img/demos/resume/portfolio/portfolio-8.jpg"
                             class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="img/demos/resume/portfolio/portfolio-8.jpg"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                        </div>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section id="recommendations"
                 class="section section-no-border background-color-primary m-none">
          <div class="container">
            <div class="row">
              <div class="col-md-12">
                <h2 class="text-color-quaternary font-weight-extra-bold text-uppercase">Recommendations</h2>
              </div>
              <div class="col-md-12 p-none">
                <div class="owl-carousel custom-dots-style-1 custom-dots-color-1 custom-dots-position-1 mb-none"
              
                     data-plugin-options="{'items': 1, 'autoHeight': true, 'loop': false, 'nav': false, 'dots': true}">
                  <div>
                    <div class="col-md-12">
                      <div class="testimonial custom-testimonial-style-1 testimonial-with-quotes mb-none">
                        <blockquote class="pb-sm">
                          <p class="custom-text-color-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                            Etiam tincidunt nulla tortor, a imperdiet enim tristique
                            nec. Nulla lobortis leo eget metus dapibus sodales. Sed
                            placerat vitae dui vitae vehicula. Quisque in tincidunt
                            ligula, nec dignissim arcu. Praesent aliquam velit vel
                            libero dictum, non sollicitudin lectus mollis. Morbi
                            sollicitudin auctor gravida.</p>
                        </blockquote>
                        <div class="testimonial-author pull-left">
                          <p>
                            <strong class="text-uppercase">Bob Doe</strong>
                            <span class="custom-text-color-3">Director of Engineering</span>
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div>
                    <div class="col-md-12">
                      <div class="testimonial custom-testimonial-style-1 testimonial-with-quotes mb-none">
                        <blockquote class="pb-sm">
                          <p class="custom-text-color-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                            Etiam tincidunt nulla tortor, a imperdiet enim tristique
                            nec. Nulla lobortis leo eget metus dapibus sodales. Sed
                            placerat vitae dui vitae vehicula. Quisque in tincidunt
                            ligula, nec dignissim arcu. Praesent aliquam velit vel
                            libero dictum, non sollicitudin lectus mollis. Morbi
                            sollicitudin auctor gravida.</p>
                        </blockquote>
                        <div class="testimonial-author pull-left">
                          <p>
                            <strong class="text-uppercase">Bob Doe</strong>
                            <span class="custom-text-color-3">Director of Engineering</span>
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section id="blog"
                 class="section section-no-border background-color-light m-none">
          <div class="container">
            <div class="row">
              <div class="col-md-12">
                <h2 class="text-color-quaternary font-weight-extra-bold text-uppercase">My Blog</h2>
              </div>
              <div class="col-md-6 col-sm-10 col-sm-offset-1 col-md-offset-0 custom-sm-margin-bottom-1">
                <article class="thumb-info custom-thumb-info-2 custom-box-shadow-1 appear-animation"
              
                         data-appear-animation="fadeIn"
                         data-appear-animation-delay="0"
                         data-appear-animation-duration="1s">
                  <span class="thumb-info-wrapper">
                    <a href="#">
                      <img src="img/demos/resume/blog/blog-1.jpg"
                           alt
                           class="img-responsive" />
                    </a>
                  </span>
                  <span class="thumb-info-caption">
                    <span class="thumb-info-caption-text">
                      <h4 class="mb-sm">
                        <a href="#"
                           class="text-decoration-none text-color-dark font-weight-semibold">
                          Design Driven
                        </a>
                      </h4>
                      <p class="custom-text-color-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam
                        tincidunt nulla tortor, a imperdiet enim tristique nec. Nulla
                        lobortis leo eget metus dapib...</p>
                    </span>
                    <hr class="solid m-none mt-xlg mb-sm">
                    <span class="custom-blog-post-date text-uppercase font-weight-semibold text-color-dark">
                      July 12-2017
                    </span>
                    <span class="custom-blog-post-share text-uppercase font-weight-semibold text-color-dark">
                      Share:
                      <ul>
                        <li>
                          <a class="item-facebook text-decoration-none text-uppercase"
                             href="#"
                             title="Share on Facebook">Facebook</a>
                        </li>
                        <li>
                          <a class="item-twitter text-decoration-none text-uppercase"
                             href="#"
                             title="Share on Twitter">Twitter</a>
                        </li>
                        <li>
                          <a class="item-google-plus text-decoration-none text-uppercase"
                             href="#"
                             title="Share on Google Plus">Google Plus</a>
                        </li>
                      </ul>
                    </span>
                  </span>
                </article>
              </div>
              <div class="col-md-6 col-sm-10 col-sm-offset-1 col-md-offset-0">
                <article class="thumb-info custom-thumb-info-2 custom-box-shadow-1 appear-animation"
              
                         data-appear-animation="fadeIn"
                         data-appear-animation-delay="0"
                         data-appear-animation-duration="1s">
                  <span class="thumb-info-wrapper">
                    <a href="#">
                      <img src="img/demos/resume/blog/blog-2.jpg"
                           alt
                           class="img-responsive" />
                    </a>
                  </span>
                  <span class="thumb-info-caption">
                    <span class="thumb-info-caption-text">
                      <h4 class="mb-sm">
                        <a href="#"
                           class="text-decoration-none text-color-dark font-weight-semibold">
                          UI, UX Concepts
                        </a>
                      </h4>
                      <p class="custom-text-color-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam
                        tincidunt nulla tortor, a imperdiet enim tristique...</p>
                    </span>
                    <hr class="solid m-none mt-xlg mb-sm">
                    <span class="custom-blog-post-date text-uppercase font-weight-semibold text-color-dark">
                      July 12-2017
                    </span>
                    <span class="custom-blog-post-share text-uppercase font-weight-semibold text-color-dark">
                      Share:
                      <ul>
                        <li>
                          <a class="item-facebook text-decoration-none text-uppercase"
                             href="#"
                             title="Share on Facebook">Facebook</a>
                        </li>
                        <li>
                          <a class="item-twitter text-decoration-none text-uppercase"
                             href="#"
                             title="Share on Twitter">Twitter</a>
                        </li>
                        <li>
                          <a class="item-google-plus text-decoration-none text-uppercase"
                             href="#"
                             title="Share on Google Plus">Google Plus</a>
                        </li>
                      </ul>
                    </span>
                  </span>
                </article>
              </div>
              <div class="col-md-12 col-sm-12 pt-xlg mt-xlg center">
                <a class="btn btn-primary btn-borders text-color-dark custom-btn-style-2 font-weight-bold custom-border-radius-1 text-uppercase">View All</a>
              </div>
            </div>
          </div>
        </section>

        <footer id="footer"
                class="m-none p-none">
          <div class="footer-copyright background-color-light m-none">
            <div class="container">
              <div class="row">
                <div class="col-md-12 m-none">
                  <p class="custom-text-color-2">© Copyright 2017. All Rights Reserved.</p>
                </div>
              </div>
            </div>
          </div>
        </footer>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    data: () => ({
        test: '100%'
    })
}
</script>
<style lang="scss" scoped>
</style>

