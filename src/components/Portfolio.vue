<template>
<div>
    <div class="body">
        <header id="header" class="header-floating wow bounceInUp" data-plugin-options="{'stickyEnabled': false, 'stickyEnableOnBoxed': false, 'stickyEnableOnMobile': false, 'stickyStartAt': 0, 'stickySetTop': '60px', 'stickyChangeLogo': false}">
            <div class="header-body">
                <div class="header-container container">
                    <div class="header-row">
                        <div class="header-column">
                            <div class="header-row">
                                <div class="header-nav pt-xs">
                                    <button class="btn header-btn-collapse-nav" data-toggle="collapse" data-target=".header-nav-main">
                      <i class="fa fa-bars"></i>
                    </button>
                                    <div class="header-nav-main collapse">
                                        <nav class="wrapper-spy">
                                            <ul class="nav" id="mainNav">
                                                <li>
                                                    <a data-hash href="#about-me" class="text-color-dark background-color-primary">
                              <i class="icon-home icons"></i>
                              <span class="custom-tooltip">About Me</span>
                            </a>
                                                </li>
                                                <li>
                                                    <a data-hash href="#experience" class="text-color-dark background-color-primary">
                              <i class="icon-eye icons"></i>
                              <span class="custom-tooltip">Experience</span>
                            </a>
                                                </li>
                                                <li>
                                                    <a data-hash href="#education" class="text-color-dark background-color-primary">
                              <i class="icon-briefcase icons"></i>
                              <span class="custom-tooltip">Education</span>
                            </a>
                                                </li>
                                                <li>
                                                    <a data-hash href="#skills" class="text-color-dark background-color-primary">
                              <i class="icon-graduation icons"></i>
                              <span class="custom-tooltip">Skills</span>
                            </a>
                                                </li>
                                                <li>
                                                    <a data-hash href="#portfolio" class="text-color-dark background-color-primary">
                              <i class="icon-diamond icons"></i>
                              <span class="custom-tooltip">Portfolio</span>
                            </a>
                                                </li>
                                                <li>
                                                    <a data-hash href="#recommendations" class="text-color-dark background-color-primary">
                              <i class="icon-pencil icons"></i>
                              <span class="custom-tooltip">Recommendations</span>
                            </a>
                                                </li>
                                                <li>
                                                    <a data-hash href="#blog" class="text-color-dark background-color-primary">
                              <i class="icon-bubbles icons"></i>
                              <span class="custom-tooltip">Blog</span>
                            </a>
                                                </li>
                                                <li>
                                                    <a data-hash href="#say-hello" class="text-color-dark background-color-primary">
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
        <div role="main" class="main">

            <section id="about-me" class="section section-no-border section-parallax custom-section-padding-1 custom-position-1 custom-xs-bg-size-cover m-none" data-plugin-parallax data-plugin-options="{'speed': 1.5}" data-image-src="http://www.portotheme.com/wordpress/porto/resume/wp-content/uploads/sites/73/2017/02/contact-bg-1.jpg?id=50">
                <div class="container">
                    <div class="row">
                        <div class="col-md-4 col-sm-4 col-xs-10 col-sm-offset-0 col-xs-offset-1 custom-sm-margin-bottom-1">
                            <img src="https://scontent.fhan5-5.fna.fbcdn.net/v/t1.0-9/18671130_445947035764870_4718051534662975243_n.jpg?_nc_cat=0&oh=c5861d1ed582e07d753f77f0f33291ff&oe=5BE0C2DC" class="img-responsive custom-border custom-image-position-2 custom-box-shadow-4" alt
                            />
                        </div>
                        <div class="col-md-8 col-sm-8 text-left">
                            <h1  class="wow fadeInUp text-color-primary custom-font-size-1">{{ user.userInfor.name }}</h1>
                            <p data-wow-delay="0.2s" class="wow fadeInUp text-color-light font-weight-normal custom-font-size-2 custom-margin-bottom-1">{{ user.userInfor.specialized }}</p>
                            <span data-wow-delay="0.3s" class="wow fadeInUp custom-about-me-infos">
               
                            <span data-wow-delay="0.4s" class="wow fadeInUp custom-text-color-1 text-uppercase mb-md">Information Technology &amp; Services</span>
                            <span data-wow-delay="0.5s" class="wow fadeInUp custom-text-color-1 text-uppercase">
                    <strong class="text-color-light">Previous: </strong>
                   {{ user.userInfor.previous }}
                    <a data-hash
                       href="#experience"
                       class="btn btn-tertiary text-uppercase custom-btn-style-1 text-xs ml-sm">View More</a>
                  </span>
                            <span data-wow-delay="0.6s" class="wow fadeInUp custom-text-color-1 text-uppercase">
                    <strong class="text-color-light">Education: </strong>
                   {{ user.userInfor.education }}
                    <a data-hash
                       href="#education"
                       class="btn btn-tertiary text-uppercase custom-btn-style-1 text-xs ml-sm">View More</a>
                  </span>
                            </span>
                        </div>
                        <div class="col-md-3 hidden-sm hidden-xs">
                            <img src="img/demos/resume/about-me/mouse.png" custom-anim class="img-responsive" alt />
                        </div>
                    </div>
                </div>
                <ul class="social-icons custom-social-icons">
                    <li class="social-icons-facebook">
                        <a href="http://www.facebook.com/" target="_blank" title="Facebook">
                <i class="fa fa-facebook"></i>
              </a>
                    </li>
                    <li class="social-icons-twitter">
                        <a href="http://www.twitter.com/" target="_blank" title="Twitter">
                <i class="fa fa-twitter"></i>
              </a>
                    </li>
                    <li class="social-icons-youtube">
                        <a href="http://www.youtube.com/" target="_blank" title="Youtube">
                <i class="fa fa-youtube"></i>
              </a>
                    </li>
                </ul>
            </section>
            <div class="custom-about-me-links">
                <div class="container">
                    <div class="row">
                        <div class="col-md-3 col-md-offset-4 col-sm-4 center custom-xs-border-bottom p-none">
                            <a data-hash href="#say-hello" class="text-decoration-none">
                  <span class="custom-nav-button text-color-dark">
                    <i class="icon-earphones-alt icons text-color-primary"></i>
                    Contact Information
                  </span>
                </a>
                        </div>
                        <div class="col-md-2 col-sm-4 center custom-xs-border-bottom p-none">
                            <a data-hash href="#say-hello" class="text-decoration-none">
                  <span class="custom-nav-button custom-divisors text-color-dark">
                    <i class="icon-envelope-open icons text-color-primary"></i>
                    Send Message
                  </span>
                </a>
                        </div>
                        <div class="col-md-3 col-sm-4 center p-none">
                            <a href="#skills" class="text-decoration-none">
                  <span class="custom-nav-button text-color-dark">
                    <i class="icon-note icons text-color-primary"></i>
                    Skills and Languages
                  </span>
                </a>
                        </div>
                    </div>
                </div>
            </div>
            <section class="wow fadeInUp section section-no-border background-color-light m-none">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12 text-left ">

                            <div class="custom-box-details background-color-light custom-box-shadow-1 col-md-6 ml-xlg mb-xlg pull-right clearfix">
                                <h4>Personal Details</h4>
                                <div class="col-md-5 col-sm-5 p-none">
                                    <ul class="custom-list-style-1 p-none">
                                        <li>
                                            <span class="text-color-dark">Birthday:</span>
                                            <span class="custom-text-color-2">{{ user.userInfor.birthday }}</span>
                                        </li>
                                        <li>
                                            <span class="text-color-dark">Marital:</span>
                                            <span class="custom-text-color-2">{{ user.userInfor.marital }}</span>
                                        </li>
                                        <li>
                                            <span class="text-color-dark">Nationality:</span>
                                            <span class="custom-text-color-2">{{ user.userInfor.nationality }}</span>
                                        </li>
                                    </ul>
                                </div>
                                <div class="col-md-7 col-sm-7 p-none">
                                    <ul class="custom-list-style-1 p-none">
                                        <li>
                                            <span class="exception-width text-color-dark">Skype:</span>
                                            <span class="custom-text-color-2">
                          <a class="custom-text-color-2"
                             href="skype:yourskype?chat">{{ user.userInfor.skype ? user.userInfor.skype : 'Updating...' }}</a>
                        </span>
                                        </li>
                                        <li>
                                            <span class="exception-width text-color-dark">PHONE:</span>
                                            <span class="custom-text-color-2">
                          <a class="custom-text-color-2"
                             href="tel:123456789">{{ user.userInfor.phone }}</a>
                        </span>
                                        </li>
                                        <li>
                                            <span class="text-color-dark exception-width">EMAIL:</span>
                                            <span class="custom-text-color-2">
                          <a class="custom-text-color-2"
                             href="mailto:info@domain.com">{{ user.userInfor.email }}</a>
                        </span>
                                        </li>
                                    </ul>
                                </div>
                            </div>

                            <h2 class="text-color-quaternary font-weight-extra-bold text-uppercase">About Me</h2>

                            <p class="custom-text-color-2"> {{user.userInfor.aboutMe}}
                            </p>

                            <div style="display: none" id="aboutMeMore">
                               <p v-for="item in user.userInfor.aboutMeMore" :key="user.userInfor.aboutMeMore.indexOf(item)">
                                   {{item.content}}
                               </p>
                            </div>

                            <a v-on:click="showMore()" id="aboutMeMoreBtn" class="btn btn-tertiary text-uppercase custom-btn-style-1 text-xs">View More</a>

                        </div>
                    </div>
                </div>
            </section>
            <section id="experience" class="section section-secondary section-no-border m-none">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12 col-sm-12 text-left">
                            <h2 class="text-color-quaternary text-uppercase font-weight-extra-bold">Experience</h2>
                            <section class="timeline custom-timeline" id="timeline">
                                <div class="timeline-body">
                                    <article v-for="item in user.experiences"  :key="user.experiences.indexOf(item)" class="wow fadeInRight timeline-box right custom-box-shadow-2">
                                        <div style="height: 212.4px!important;" class="experience-info col-md-3 col-sm-5 match-height background-color-primary">
                                            <span class="from text-color-dark text-uppercase">From
                          <span class="font-weight-semibold">{{ item.from }}</span>
                                            </span>
                                            <span class="to text-color-dark text-uppercase">
                          To
                          <span class="font-weight-semibold">{{ item.to }}</span>
                                            </span>
                                            <p class="text-color-dark"></p>
                                            <span class="company text-color-dark font-weight-semibold">{{ item.company }}
                          <span class="company-location text-color-dark font-weight-normal text-uppercase">{{ item.located }}</span>
                                            </span>
                                        </div>
                                        <div style="height: 212.4px!important;" class="experience-description col-md-9 col-sm-7 match-height background-color-light">
                                            <h4 class="text-color-dark font-weight-semibold">{{ item.job }}</h4>
                                            <p class="custom-text-color-2">{{ item.description }}</p>
                                        </div>
                                    </article>

                                    <div class="timeline-bar" style="top: 115.2px; bottom: 121.2px"></div>
                                </div>
                            </section>
                        </div>
                    </div>
                </div>
            </section>
            <section id="education" class="wow bounceInUp section section-no-border custom-background-color-1 m-none">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12">
                            <h2 class="text-color-quaternary text-uppercase font-weight-extra-bold m-none text-left">Education</h2>
                            <div class="owl-carousel nav-bottom custom-carousel-style-1 custom-item-padding custom-dots-style-1 text-center" data-plugin-options="{'items': 1, 'loop': false, 'dots': true, 'nav': false}">
                                <div v-for="item in user.educations" :key="user.educations.indexOf(item)">
                                    <div class="col-md-12 col-sm-12">
                                        <div class="custom-box-details-2 background-color-light custom-box-shadow-3">
                                            <i class="icon-graduation icons text-color-primary"></i>
                                            <h4 class="font-weight-semibold text-color-dark m-none">{{ item.located }}</h4>
                                            <p class="custom-text-color-2 mb-xs">{{ item.class }}</p>
                                            <strong class="text-color-primary">{{ item.from }}-{{ item.to }}</strong>
                                        </div>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section id="skills" class="wow fadeInUp section section-no-border background-color-light m-none">
                <div class="container">
                    <div class="row custom-sm-flex-order">
                        <div data-wow-delay="0.5s" class="wow bounceInLeft col-md-8 col-sm-6 col-xs-12">
                            <h2 class="text-color-quaternary text-uppercase font-weight-extra-bold text-left" style="margin-bottom: 32px!important">Skills & Language</h2>
                            <div class="progress-bars custom-progress-bars row">
                                <div class="col-md-6 col-xs-12" v-for="item in user.skills" :key="user.skills.indexOf(item)">
                                    <div class="progress-label text-color-dark font-weight-semibold text-uppercase text-sm text-left">
                                        <span>{{ item.name }}</span>
                                    </div>
                                    <div class="progress">
                                        <div class="progress-bar" :data-appear-progress-animation="item.percent"></div>
                                    </div>
                                </div>

                            </div>
                        </div>
                       
                        <div data-wow-delay="0.5s" class="wow bounceInRight col-md-4 col-sm-6 col-xs-12">
                            <div class="custom-box-details background-color-light custom-box-shadow-1 text-left">
                                <h4 class="text-color-dark">Languages</h4>
                                <ul class="custom-list-style-1 p-none">
                                    <li>
                                        <span class="font-weight-semibold custom-max-width-1 text-color-dark"><img src="http://greatbritishmag.co.uk/uploads/old-brit-flag_blog.png"
                             class="flag flag-us mr-xs"
                             alt="English">English:</span>
                                        <span class="custom-text-color-2">Advanced</span>
                                    </li>
                                    <li>
                                        <span class="font-weight-semibold custom-max-width-1 text-color-dark"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT43aoC5Fholgyp-YvAOiQLn47MWAofF-9gxtOYtZuirqP9oAXv"
                             class="flag flag-es mr-xs"
                             alt="Spanish">Vietnamese:</span>
                                        <span class="custom-text-color-2">Advanced</span>
                                    </li>

                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section id="portfolio"  class="wow fadeInUp section section-no-border background-color-secondary m-none">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12">
                            <h2 data-wow-delay="0.5s" class=" wow fadeInUp text-color-quaternary font-weight-extra-bold text-uppercase text-left">Portfolio</h2>
                            <ul data-wow-delay="0.75s" class=" wow fadeInUp nav nav-pills sort-source custom-nav-sort mb-xlg" data-sort-id="portfolio" data-option-key="filter">
                                <li data-option-value="*" class="active">
                                    <a href="#">Show All</a>
                                </li>
                                <li data-option-value=".websites">
                                    <a href="#">Websites</a>
                                </li>
                                <li data-option-value=".HIT-Club">
                                    <a href="#">HIT Club</a>
                                </li>
                                <li data-option-value=".Alibaba">
                                    <a href="#">Alibaba English Club</a>
                                </li>
                            </ul>
                            <div data-wow-delay="1s"  class="row wow fadeInUp">
                                <div class="sort-destination-loader sort-destination-loader-showing">
                                    <ul class="image-gallery sort-destination lightbox" data-sort-id="portfolio" data-plugin-options="{'delegate': 'a.lightbox-portfolio', 'type': 'image', 'gallery': {'enabled': true}}">

                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item HIT-Club">
                                            <div class="image-gallery-item">
                                                <a href="https://scontent.fhan5-2.fna.fbcdn.net/v/t31.0-8/21752819_497601923932714_4394120048675903077_o.jpg?_nc_cat=0&oh=27ecf6988d1d6fe80e80fe83c34029a5&oe=5BA3BD73" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://scontent.fhan5-2.fna.fbcdn.net/v/t31.0-8/21752819_497601923932714_4394120048675903077_o.jpg?_nc_cat=0&oh=27ecf6988d1d6fe80e80fe83c34029a5&oe=5BA3BD73"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                                            </div>
                                        </li>
                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item HIT-Club">
                                            <div class="image-gallery-item">
                                                <a href="https://scontent.fhan5-2.fna.fbcdn.net/v/t1.0-9/13726629_378618865831021_6801776781224046837_n.jpg?_nc_cat=0&oh=331785e5c639821e3583ae494f986596&oe=5BA8631F" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://scontent.fhan5-2.fna.fbcdn.net/v/t1.0-9/13726629_378618865831021_6801776781224046837_n.jpg?_nc_cat=0&oh=331785e5c639821e3583ae494f986596&oe=5BA8631F"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                                            </div>
                                        </li>
                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item HIT-Club">
                                            <div class="image-gallery-item">
                                                <a href="https://scontent.fhan5-2.fna.fbcdn.net/v/t31.0-8/18449342_439612279731679_5722258999240077173_o.jpg?_nc_cat=0&oh=c104d02fcdb546cf187773fea51e35a0&oe=5BAC9D39" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://scontent.fhan5-2.fna.fbcdn.net/v/t31.0-8/18449342_439612279731679_5722258999240077173_o.jpg?_nc_cat=0&oh=c104d02fcdb546cf187773fea51e35a0&oe=5BAC9D39"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                                            </div>
                                        </li>
                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item Alibaba">
                                            <div class="image-gallery-item">
                                                <a href="https://scontent.fhan5-2.fna.fbcdn.net/v/t1.0-9/20770039_485296381829935_8759885494463885055_n.jpg?_nc_cat=0&oh=8cf4584605332b5d9d7dfae7538350ed&oe=5BE2726E" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://scontent.fhan5-2.fna.fbcdn.net/v/t1.0-9/20770039_485296381829935_8759885494463885055_n.jpg?_nc_cat=0&oh=8cf4584605332b5d9d7dfae7538350ed&oe=5BE2726E"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                                            </div>
                                        </li>
                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item Alibaba">
                                            <div class="image-gallery-item">
                                                <a href="https://scontent.fhan5-2.fna.fbcdn.net/v/t31.0-8/20617016_1186284668184537_9004984338108739723_o.jpg?_nc_cat=0&oh=8cbb773cfdb347625542700610798e23&oe=5BE0112F" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://scontent.fhan5-2.fna.fbcdn.net/v/t31.0-8/20617016_1186284668184537_9004984338108739723_o.jpg?_nc_cat=0&oh=8cbb773cfdb347625542700610798e23&oe=5BE0112F"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                                            </div>
                                        </li>
                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                                            <div class="image-gallery-item">
                                                <a href="https://firebasestorage.googleapis.com/v0/b/cv-project-79eac.appspot.com/o/Screenshot-2018-7-4%20Admin.png?alt=media&token=1e01c87c-3c88-4333-9728-e726dd7f1413" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://firebasestorage.googleapis.com/v0/b/cv-project-79eac.appspot.com/o/Screenshot-2018-7-4%20Admin.png?alt=media&token=1e01c87c-3c88-4333-9728-e726dd7f1413"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                                            </div>
                                        </li>
                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                                            <div class="image-gallery-item">
                                                <a href="https://firebasestorage.googleapis.com/v0/b/cv-project-79eac.appspot.com/o/Screenshot-2018-7-4%20Ph%C3%B2ng%20C%E1%BA%A3nh%20s%C3%A1t%20PC%20CC%2013.png?alt=media&token=feaa4cd2-f666-48b4-8d08-8a3872ee982b" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://firebasestorage.googleapis.com/v0/b/cv-project-79eac.appspot.com/o/Screenshot-2018-7-4%20Ph%C3%B2ng%20C%E1%BA%A3nh%20s%C3%A1t%20PC%20CC%2013.png?alt=media&token=feaa4cd2-f666-48b4-8d08-8a3872ee982b"
                                     class="img-responsive"
                                     alt="">
                              </span>
                            </span>
                          </a>
                                            </div>
                                        </li>
                                        <li class="col-md-3 col-sm-6 col-xs-12 isotope-item websites">
                                            <div class="image-gallery-item">
                                                <a href="https://firebasestorage.googleapis.com/v0/b/cv-project-79eac.appspot.com/o/Screenshot-2018-7-4%20%C3%81o%20b%C3%B3ng%20%C4%91%C3%A1%20Admin.png?alt=media&token=d235af9b-1d63-4330-b05f-a562bd3f30c9" class="lightbox-portfolio">
                            <span class="thumb-info custom-thumb-info-1">
                              <span class="thumb-info-wrapper">
                                <span class="thumb-info-plus"></span>
                                <img src="https://firebasestorage.googleapis.com/v0/b/cv-project-79eac.appspot.com/o/Screenshot-2018-7-4%20%C3%81o%20b%C3%B3ng%20%C4%91%C3%A1%20Admin.png?alt=media&token=d235af9b-1d63-4330-b05f-a562bd3f30c9"
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

            <section id="recommendations" class=" wow flipInX section section-no-border background-color-primary m-none">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12 text-left">
                            <h2 class="text-color-quaternary font-weight-extra-bold text-uppercase">Recommendations</h2>
                        </div>
                        <div class="col-md-12 p-none text-left">
                            <div class="owl-carousel custom-dots-style-1 custom-dots-color-1 custom-dots-position-1 mb-none" data-plugin-options="{'items': 1, 'autoHeight': true, 'loop': false, 'nav': false, 'dots': true}">
                                <div v-for="item in user.recommendations" :key="user.recommendations.indexOf(item)">
                                    <div class="col-md-12">
                                        <div class="testimonial custom-testimonial-style-1 testimonial-with-quotes mb-none">
                                            <blockquote class="pb-sm">
                                                <p class="custom-text-color-3">{{ item.message }}</p>
                                            </blockquote>
                                            <div class="testimonial-author pull-left">
                                                <p>
                                                    <strong class="text-uppercase">{{ item.author }}</strong>
                                                    <span class="custom-text-color-3">{{ item.duty }}</span>
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

            <section id="blog" class="wow fadeInUp section section-no-border background-color-light m-none">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12">
                            <h2 class="text-color-quaternary font-weight-extra-bold text-uppercase">My Note</h2>
                        </div>
                        <div v-for="item in user.notes" :key="user.notes.indexOf(item)" class="col-md-6 col-sm-10 col-sm-offset-1 col-md-offset-0 custom-sm-margin-bottom-1">
                            <article class="thumb-info custom-thumb-info-2 custom-box-shadow-1 appear-animation" data-appear-animation="fadeIn" data-appear-animation-delay="0" data-appear-animation-duration="1s">
                                <span class="thumb-info-wrapper">
                    <a :href="item.link">
                      <img style="height: 150px!important" :src="item.img"
                           alt
                           class="img-responsive" />
                    </a>
                  </span>
                                <span class="thumb-info-caption">
                    <span class="thumb-info-caption-text">
                      <h4 class="mb-sm">
                        <a  :href="item.link"
                           class="text-decoration-none text-color-dark font-weight-semibold">
                         {{item.title}}
                        </a>
                      </h4>
                      <p class="custom-text-color-2 text-left">{{ item.content }}</p>
                    </span>
                                <hr class="solid m-none mt-xlg mb-sm">
                                <span class="custom-blog-post-date text-uppercase font-weight-semibold text-color-dark">
                  
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
                            <a href="https://www.facebook.com/ntt.naisha/notes?lst=100010487327391%3A100010487327391%3A1530762652" class="btn btn-primary btn-borders text-color-dark custom-btn-style-2 font-weight-bold custom-border-radius-1 text-uppercase">View All</a>
                        </div>
                    </div>
                </div>
            </section>
            <div id="say-hello" class="container-fluid">
                <div class="row">
                    <div class="col-md-6 p-none">
                        <section class=" wow fadeInLeft section section-no-border match-height background-color-primary m-none">
                            <div class="row m-none">
                                <div class="col-half-section col-half-section-right mr-md">
                                    <h2 class="text-color-quaternary text-uppercase font-weight-extra-bold">Say Hello</h2>
                                    <form id="callSendMessage" class="custom-form-style" action="#" method="POST">
                                        <div class="form-content">
                                            <div class="form-control-custom">
                                                <input type="text" class="form-control" name="callName" placeholder="Your Name *" data-msg-required="This field is required." id="callName" required="" />
                                            </div>
                                            <div class="form-control-custom">
                                                <input type="text" class="form-control" name="callSubject" placeholder="Subject *" data-msg-required="This field is required." id="callSubject" required="" />
                                            </div>
                                            <div class="form-control-custom">
                                                <textarea maxlength="5000" data-msg-required="Please enter your message." rows="10" class="form-control" name="message" placeholder="Message*" id="message" required="" aria-required="true"></textarea>
                                            </div>
                                            <input type="submit" class="btn btn-quaternary text-color-light text-uppercase font-weight-semibold outline-none custom-btn-style-2 custom-border-radius-1" value="Submit" />
                                        </div>
                                    </form>
                                </div>
                            </div>
                        </section>
                    </div>
                    <div class="col-md-6 p-none text-left">
                        <section class=" wow fadeInRight section section-no-border match-height m-none" style=" background: url(http://www.portotheme.com/wordpress/porto/resume/wp-content/uploads/sites/73/2017/02/contact-bg-1.jpg?id=50); background-size: cover; height: 433.6px;">
                            <div class="row m-none">
                                <div class="col-half-section col-half-section-left ml-md">
                                    <a href="mailto:you@domain.com" class="text-decoration-none">
                                        <span class="feature-box custom-feature-box mb-xlg">		<span class="custom-feature-box-icon">		<i class="icon-envelope icons text-color-light"></i>		</span>
                                        <span class="feature-box-info">		<label class="font-weight-semibold text-uppercase custom-text-color-1">Email</label>		<strong class="font-weight-light text-color-light custom-opacity-effect-1">{{ user.userInfor.email }}</strong>		</span>
                                        </span>
                                    </a>
                                    <a href="tel:+1234657890" class="text-decoration-none">
                                        <span class="feature-box custom-feature-box mb-xlg">		<span class="custom-feature-box-icon">		<i class="icon-phone icons text-color-light"></i>		</span>
                                        <span class="feature-box-info">		<label class="font-weight-semibold text-uppercase custom-text-color-1">Phone</label>		<strong class="font-weight-light text-color-light custom-opacity-effect-1">{{ user.userInfor.phone }}</strong>		</span>
                                        </span>
                                    </a>
                                    <a href="skype:yourskype?chat" class="text-decoration-none">
                                        <span class="feature-box custom-feature-box mb-xlg">		<span class="custom-feature-box-icon">		<i class="icon-social-skype icons text-color-light"></i>		</span>
                                        <span class="feature-box-info">		<label class="font-weight-semibold text-uppercase custom-text-color-1">Skype</label>		<strong class="font-weight-light text-color-light custom-opacity-effect-1">{{ user.userInfor.skype ? user.userInfor.skype : 'Updating...'}}</strong>		</span>
                                        </span>
                                    </a>
                                    <span class="feature-box custom-feature-box mb-xlg">		<span class="custom-feature-box-icon">		<i class="icon-share icons text-color-light"></i>		</span>
                                    <a :href="user.userInfor.facebook" class="text-decoration-none">
                                        <span class="feature-box-info">		<label class="font-weight-semibold text-uppercase custom-text-color-1">Follow me</label>		<strong class="font-weight-light text-color-light custom-opacity-effect-1">Facebook</strong>		</span>
                                    </a>
                                    <a href="http://www.twitter.com" class="text-decoration-none">
                                        <span class="feature-box-info custom-both-side-border">		<strong class="font-weight-light text-color-light custom-opacity-effect-1">Twitter</strong>		</span>
                                    </a>
                                    <a href="http://www.linkedin.com" class="text-decoration-none">
                                        <span class="feature-box-info p-none">		<strong class="font-weight-light text-color-light custom-opacity-effect-1">Linkedin</strong>		</span>
                                    </a>
                                    </span>
                                </div>
                            </div>
                        </section>
                    </div>
                </div>
            </div>

            <footer id="footer" class="m-none p-none">
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
import WOW from 'wow.js/dist/wow.js';
new WOW().init();
export default {
  data: () => ({
    user: {
      userInfor: {
        name: 'Nguyen Thanh Trung',
        specialized: 'Web Developer',
        previous: 'Web Developer',
        education: 'Hanoi University of Industry',
        birthday: '09-19-1997',
        marital: 'Single',
        nationality: 'Vietnam',
        skype: '',
        phone: '0984-318-297',
        email: 'nt.naisha.trung@gmail.com',
        aboutMe: 'Hello! My name is Trung. I was born in 1997. Now I am learning at Hanoi University of Industry and having a partime job as a Web developer ',
        aboutMeMore: [
          {
            content:
              'My philosophy: "Life is not trying to find the good things. Life is trying to make to be good first. And after that, everything good will comes and say hello to you".'
          },
          {
            content:
              'I often play Overwatch - one of the famous games in the world. My friends is come from all over the world so I can practice my English skill, and learn their culture.'
          },
          {
            content:
              'In the future: I will save my money for a trip to another country. About 1 or 2 months for travelling and learning the news. After that I will come back my country and start-up. I will not work as a staff forever.'
          }
        ],
        facebook: 'https://www.facebook.com/ntt.naisha?ref=bookmarks'
      },
      experiences: [
        {
          delay: '0.25s',
          from: '2016',
          to: '2017',
          company: 'HIT-Club',
          located: 'Ha Nam',
          job: 'Support C',
          description:
            'This is a big change of my life. I got many helps from HIT Club so that was a chance for me to help another people. I also got many skills from that such as presentation, communication, ...'
        },
        {
          delay: '0.55s',
          from: '2017',
          to: '2017',
          company: '3F Group',
          located: 'Ha Noi',
          job: 'Intership',
          description:
            'That time was not too long. I learned HTML, CSS from 3F. But the most important thing is how to use the time efficiently and work seriously.'
        },
        {
          delay: '0.75s',
          from: '2017',
          to: '2018',
          company: 'AIB Technology Joint Stock Company',
          located: 'Ha Noi',
          job: 'Web Developer',
          description:
            'AIB company is where I learn almost knowledge. For example: Angular 5+, Vue.JS, Laravel, Next.JS, Socket.IO, ... . It is good environment for practice and learn. I have been finished 4 projects here.'
        }
      ],
      educations: [
        {
          located: 'Hanoi University of Industry',
          class: 'Information Technology',
          from: '2016',
          to: '2018'
        },
        {
          located: 'Hai Ba Trung High school ',
          class: '12A3',
          from: '2014',
          to: '2016'
        },
        {
          located: 'Hai Ba Trung Secondary School',
          class: '9A2',
          from: '2007',
          to: '2014'
        }
      ],
      skills: [
        {
          name: 'Next.JS',
          percent: '60%'
        },
        {
          name: 'HTML & CSS',
          percent: '80%'
        },
        {
          name: 'Angular 5+',
          percent: '80%'
        },
        {
          name: 'Vue.js',
          percent: '80%'
        },
        {
          name: 'Laravel',
          percent: '70%'
        },
        {
          name: 'Google search',
          percent: '85%'
        }
      ],
      languages: [
        {
          language: 'English',
          level: 'Communication',
          img: ''
        },
        {
          language: 'Vietnamese',
          level: 'Communication',
          img: ''
        }
      ],
      recommendations: [
        {
          message: 'He is a good man. But his defect is always care about the feeling of the others .',
          author: 'Cuc Nguyen',
          duty: 'Classmate'
        },
        {
          message: 'He is like a diamond. The value is deep inside. Someone has to find and raise his ability if he can not do himself',
          author: 'Le Quang Huy',
          duty: 'Classmate'
        }
      ],
      notes: [
        {
          img: 'https://jquery-plugins.net/image/plugin/airbnb-javascript-style-guide.png',
          title: 'JavaScript Style Guide',
          content: 'A mostly reasonable approach to JavaScript. Code clear and performance [...]',
          link: 'https://github.com/airbnb/javascript'
        },
        {
          img: 'https://raw.githubusercontent.com/alexeymezenin/laravel-best-practices/master/images/logo-english.png',
          title: 'Laravel Style Guide',
          content:
            'It is not a Laravel adaptation of SOLID principles, patterns etc. Here you will find the best practices which are usually ignored in real life Laravel projects. [...]',
          link: 'https://github.com/alexeymezenin/laravel-best-practices'
        }
      ]
    }
  }),
  methods: {
    showMore() {
      document.getElementById('aboutMeMoreBtn').style.display = 'none';
      document.getElementById('aboutMeMore').style.display = 'block';
    }
  }
};
</script>

<style lang="scss" scoped>
</style>
