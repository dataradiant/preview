---
layout: mainpage
title: Company
permalink: /company/
order: 5
---

<div id="about-us">
    <div id="slider">
        <div class="container">
            <div class="row header">
                <div class="col-md-12">
                    <h1>About DataRadiant</h1>
                    <p>
                        You have to roll up your sleeves and be a stonecutter before you can become a sculptor – command of craft always precedes art.
                    </p>
                </div>
            </div>
            <div class="row">
                <div class="col-md-12">
                    <div class="flexslider">
                        <ul class="slides">
                            <li class="" style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 0; display: block; z-index: 1;">
                                <img src="/images/office2.png" alt="office2" draggable="false">
                            </li>
                            <li class="flex-active-slide" style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 1; display: block; z-index: 2;">
                                <img src="/images/office1.png" alt="office1" draggable="false">
                            </li>
                            <li style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 0; display: block; z-index: 1;">
                                <img src="/images/office3.png" alt="office3" draggable="false">
                            </li>
                        </ul>
                    <ol class="flex-control-nav flex-control-paging"><li><a class="">1</a></li><li><a class="flex-active">2</a></li><li><a>3</a></li></ol></div>
                </div>
            </div>
        </div>
    </div>

    <div id="info">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <h2>We care about our work</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <p>
                        Whether you want to fill this paragraph with some text like I'm doing right now, this place is perfect to describe some features or anything you want - React has a complete solution for you.
                    </p>
                    <p>
                        You have complete control over the look &amp; feel of your website, we offer the best quality so you take your site up and running in no time.
                    </p>
                </div>
                <div class="col-md-6">
                    <p>
                        React is a simple, developer-friendly way to get your site. Full of features, cool documentation ease of use, lots of pages. We want to help bringing cool stuff to people so they can get their projects faster.
                    </p>
                    <!--a href="#" class="join-team button button-small">Join our team</a-->
                </div>
            </div>
        </div>
    </div>
</div>

<div id="contact-us">
    <div id="map" style="height:400px;">

        <iframe width="100%" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com.mx/?ie=UTF8&amp;ll=37.7908821,-122.4037407&amp;spn=0.023259,0.038495&amp;t=m&amp;z=15&amp;output=embed"></iframe>

        <div class="marker-wrapper">
            <div class="marker-icon"></div>
            <div class="marker"></div>
        </div>

        <!--div id="directions">
            <p>Get directions to our office</p>
            <form>
                <div class="form-group">
                    <input class="form-control" type="text" placeholder="Write your zip code">
                </div>
                <button type="submit" class="button button-small">
                    <span>Get directions</span>
                </button>
            </form>
        </div-->
    </div>
    <div id="info">
        <div class="container">
            <div class="row">
                <div class="col-md-8 message">
                    <h3>Send us a message</h3>
                    <p>
                        You can contact us with anything related to DataRadiant or Apache Beam. <br> We'll get back to you as soon as possible.
                    </p>
                    <form role="form" id="contact-form" method="post" action="https://formspree.io/info@dataradiant.com">
                        <div class="form-group">
                            <label for="name">Your name</label>
                            <input type="text" name="name" class="form-control" id="name">
                        </div>
                        <div class="form-group">
                            <label for="email">Email address</label>
                            <input type="email" name="email" class="form-control" id="email">
                        </div>
                        <div class="form-group">
                            <label for="phone">Phone</label>
                            <input type="text" name="phone" class="form-control" id="phone">
                        </div>
                        <div class="form-group">
                            <label for="_subject">Inquiry</label>
                            <select name="_subject" class="form-control" id="subject">
                                <option selected="selected">General</option>
                                <option>Service</option>
                                <option>Press</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="message">Your message</label>
                            <textarea name="message" class="form-control" id="message" rows="6"></textarea>
                        </div>
                        <div class="submit">
                            <input type="hidden" name="_next" value="/thanks/" />
                            <input type="text" name="_format" value="plain" style="display:none" />
                            <input type="submit" class="btn btn-primary" value="Email us">
                        </div>
                    </form>
                </div>
                <div class="col-md-4 contact">
                    <div class="email">
                        <h3>General</h3>
                        <p>
                            <a href="mailto:info@dataradiant.com">info@dataradiant.com</a>
                        </p>
                    </div>
                    <div class="press">
                        <h3>Press</h3>
                        <p>
                            <a href="mailto:press@dataradiant.com">press@dataradiant.com</a>
                        </p>
                    </div>
                    <div class="address">
                        <h3>Offices</h3>
                        <address>
                          <strong>San Francisco</strong><br>
                          225 Bush St.<br>
                          CA, 94104<br>
                        </address>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<script type="text/javascript">
        $(function() {
            $('.flexslider').flexslider({
                directionNav: false,
                slideshowSpeed: 4000
            });
            $('[data-toggle="tooltip"]').tooltip();
        });
    </script>
