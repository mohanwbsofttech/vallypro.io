---
layout: default
---
<style>
/* carousel */
#quote-carousel {
  padding: 0 10px 30px 10px;
  margin-top: 30px;
  text-align:center;
}
/* indicator position */
#quote-carousel .carousel-indicators {
  right: 50%;
  top: auto;
  bottom: -10px;
  margin-right: -19px;
}
/* indicator color */
#quote-carousel .carousel-indicators li {
  background: #c0c0c0;
}
/* active indicator */
#quote-carousel .carousel-indicators .active {
  background: #333333;
  height:10px;
  width:10px;
  margin-bottom:1px;
}
/* typography */
h1 {
  text-align:center;
  margin-bottom:-20px !important;
}
p {
  font-style:italic;
}
</style>

<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.min.css" type="text/css" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js" type="text/javascript"></script>
<script>
$(document).ready(function() {
  //carousel options
  $('#quote-carousel').carousel({
    pause: true, interval: 10000,
  });
});
</script>

  <section  class="intro">
    <div class="container">
    <div class="intro-content">
      <h2>Your Visions,</h2>
	  <h3>Realized.</h3>
	  <p>Lorem ipsum dolor sit amet, consectetur <br> adipiscing elit.</p>
      <div>
        <a href="contact" class="btn-get-started scrollto">Request a Quote</a>
      </div>
    </div>

    </div>
  </section><section id="about-hide" class="wow slide-testi hide-service hide">
      <div class="container">
        <div class="row service-title show">
		<div class="col-lg-6">
		 <h1 id="back-service" class> Back To Services</h1>
		</div>
		<div class="col-lg-6">
		<h3><img src="img/bath.png"> Bathroom Renovation</h3>
		</div>
		</div>
		<div class="row service-video top">
		<div class="col-lg-6">
		<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/tgbNymZ7vqY" allowfullscreen></iframe>
</div>
		</div>
		<div class="col-lg-6">
		 <h1>Bathroom Renovation</h1>
		 <p>Bathroom renovations can be overly expensive if your project dollars are not spent wisely. Don't take a chance trying to do it yourself.</p>

		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut at ex et ipsum feugiat molestie. Ut porta, est nec mattis commodo, nisi ligula molestie orci, at pretium neque mi in dolor. Suspendisse vehicula aliquam pellentesque. </p>

		<p>Maecenas posuere tempus lectus, non ultricies nisl. </p>
		</div>
		</div>
		<div class="row service-video bottom">
		<div class="col-lg-6">
		 <h1>Bathroom Renovation</h1>
		 <p>Bathroom renovations can be overly expensive if your project dollars are not spent wisely. Don't take a chance trying to do it yourself.</p>

		<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. </li>
		<li>Ut at ex et ipsum feugiat molestie. </li>
		<li>Ut porta, est nec mattis commodo</li>
		<li>Nisi ligula molestie orci, at pretium neque mi in dolor.</li>
		</div>
		<div class="col-lg-6">
		<div class="w3-content w3-display-container">
	  <img class="mySlides" src="img/vid02.jpg" style="width:100%">
	  <img class="mySlides" src="img/vid01.jpg" style="width:100%">
	  <img class="mySlides" src="img/vid02.jpg" style="width:100%">

	  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
	  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
	</div>
		</div>
		</div>
		<div class="col-lg-3 cta-btn-container text-center service">
            <a class="cta-btn align-middle" href="contact">Request a quote</a>
         </div>
	  </div>
	</section>
  <section id="about" class="wow fadeInUp slide-testi">
    <div class="container">
        <div class="row service-title">
          <div class="col-lg-12">
            <h1>OUR SERVICES</h1>
			<h2></h2>
          </div>
		  </div> 
        <div class="row service-text">
          <div class="col-lg-4 one" id="service1">
            <h1><img src="img/services/srv01.png"></h1>
			<h1><img src="img/services/hov01.png" class="img-top1"></h1>
			<h2>Kitchen Remodeling</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula.</p>
          </div>
		  <div class="col-lg-4 two" id="service2">
            <h1><img src="img/services/serv22.png"></h1>
			<h1><img src="img/services/srv02.png" class="img-top2"></h1>
			<h2>Kitchen Remodeling</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula.</p>
          </div>
		  <div class="col-lg-4 three" id="service3">
            <h1><img src="img/services/srv03.png"></h1>
			<h1><img src="img/services/hov03.png" class="img-top3"></h1>
			<h2>Window Installation</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula. </p>
          </div>
        </div>
		<div class="row service-text">
          <div class="col-lg-4 four" id="service4">
            <h1><img src="img/services/srv04.png"></h1>
			<h1><img src="img/services/hov04.png" class="img-top4"></h1>
			<h2>Door Installation</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula.</p>
          </div>
		  <div class="col-lg-4 five" id="service5">
            <h1><img src="img/services/srv05.png"></h1>
			<h1><img src="img/services/hov05.png" class="img-top5"></h1>
			<h2>Roofing</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula.</p>
          </div>
		  <div class="col-lg-4 six" id="service6">
            <h1><img src="img/services/srv06.png"></h1>
			<h1><img src="img/services/hov06.png" class="img-top6"></h1>
			<h2>Sliding</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula. </p>
          </div>
        </div>
		<div class="row service-text">
          <div class="col-lg-4 seven" id="service7">
            <h1><img src="img/services/srv07.png"></h1>
			<h1><img src="img/services/hov07.png" class="img-top7"></h1>
			<h2>Home Additions</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula.</p>
          </div>
		  <div class="col-lg-4 eight" id="service8">
            <h1><img src="img/services/srv08.png"></h1>
			<h1><img src="img/services/hov08.png" class="img-top8"></h1>
			<h2>Restoration Services</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula.</p>
          </div>
		  <div class="col-lg-4 nine" id="service9">
            <h1><img src="img/services/srv09.png"></h1>
			<h1><img src="img/services/hov09.png" class="img-top9"></h1>
			<h2>Custom Home Building</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sed leo tellus. Praesent nec vehicula ligula, non laoreet ligula. </p>
          </div>
		</div>
    </div>
    </section><section id="testimonials" class="wow fadeInUp">
      <div class="container">
        <div class="section-header">
          <h2 class="client-say">What our customer say?</h2>
		   <p><img src="img/star.png"></p>
        </div>
		
		
		<!--- add custom testimonial-->
		<div class="col-md-12">
      <div class="carousel slide" data-ride="carousel" id="quote-carousel">
      
<!-- Bottom Carousel Indicators -->
<ol class="carousel-indicators">
  <li data-target="#quote-carousel" data-slide-to="0" class="active"></li>
  <li data-target="#quote-carousel" data-slide-to="1"></li>
  <li data-target="#quote-carousel" data-slide-to="2"></li>
</ol>
        
<!-- Carousel Slides / Quotes -->
<div class="carousel-inner">

<!-- Quote 1 -->
<div class="item active">
  <div class="row">
    <div class="col-sm-12">
      <p>&ldquo;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sed diam eget risus varius blandit sit amet non magna. Etiam porta sem malesuada magna mollis euismod. Nulla vitae elit libero, a pharetra augue. Donec id elit non mi porta gravida at eget metus.&rdquo;</p>
      <small><strong>Vulputate M., Dolor</strong></small>
    </div>
  </div>
</div>

<!-- Quote 2 -->
<div class="item">
  <div class="row">
    <div class="col-sm-12">
      <p>&ldquo;Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Aenean lacinia bibendum nulla sed consectetur. Nullam id dolor id nibh ultricies vehicula ut id elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum.&rdquo;</p>
      <small><strong>Fringilla A., Vulputate Sit</strong></small>
    </div>
  </div>
</div>

<!-- Quote 3 -->
<div class="item">
  <div class="row">
    <div class="col-sm-12">
      <p>&ldquo;Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Maecenas faucibus mollis interdum. Cras mattis consectetur purus sit amet fermentum.&rdquo;</p>
      <small><strong>Aenean A., Justo Cras</strong></small>
    </div>
  </div>
</div>
  
</div>
        

      </div>                          
    </div>
		<!--- end custom testimonial-->
		
        <!---<div class="owl-carousel testimonials-carousel">

            <div class="testimonial-item">
              <p>
                <img src="img/quote-sign-left.png" class="quote-sign-left" alt="">
                Proin iaculis purus consequat sem cure digni ssim donec porttitora entum suscipit rhoncus. Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam, risus at semper.
                <img src="img/quote-sign-right.png" class="quote-sign-right" alt="">
              </p>
              <img src="img/testimonial-1.jpg" class="testimonial-img" alt="">
              <h3>Saul Goodman</h3>
              <h4>Ceo &amp; Founder</h4>
            </div>
 
            <div class="testimonial-item">
              <p>
                <img src="img/quote-sign-left.png" class="quote-sign-left" alt="">
                Export tempor illum tamen malis malis eram quae irure esse labore quem cillum quid cillum eram malis quorum velit fore eram velit sunt aliqua noster fugiat irure amet legam anim culpa.
                <img src="img/quote-sign-right.png" class="quote-sign-right" alt="">
              </p>
              <img src="img/testimonial-2.jpg" class="testimonial-img" alt="">
              <h3>Sara Wilsson</h3>
              <h4>Designer</h4>
            </div>

            <div class="testimonial-item">
              <p>
                <img src="img/quote-sign-left.png" class="quote-sign-left" alt="">
                Enim nisi quem export duis labore cillum quae magna enim sint quorum nulla quem veniam duis minim tempor labore quem eram duis noster aute amet eram fore quis sint minim.
                <img src="img/quote-sign-right.png" class="quote-sign-right" alt="">
              </p>
              <img src="img/testimonial-3.jpg" class="testimonial-img" alt="">
              <h3>Jena Karlis</h3>
              <h4>Store Owner</h4>
            </div>

            <div class="testimonial-item">
              <p>
                <img src="img/quote-sign-left.png" class="quote-sign-left" alt="">
                Fugiat enim eram quae cillum dolore dolor amet nulla culpa multos export minim fugiat minim velit minim dolor enim duis veniam ipsum anim magna sunt elit fore quem dolore labore illum veniam.
                <img src="img/quote-sign-right.png" class="quote-sign-right" alt="">
              </p>
              <img src="img/testimonial-4.jpg" class="testimonial-img" alt="">
              <h3>Matt Brandon</h3>
              <h4>Freelancer</h4>
            </div>

            <div class="testimonial-item">
              <p>
                <img src="img/quote-sign-left.png" class="quote-sign-left" alt="">
                Quis quorum aliqua sint quem legam fore sunt eram irure aliqua veniam tempor noster veniam enim culpa labore duis sunt culpa nulla illum cillum fugiat legam esse veniam culpa fore nisi cillum quid.
                <img src="img/quote-sign-right.png" class="quote-sign-right" alt="">
              </p>
              <img src="img/testimonial-5.jpg" class="testimonial-img" alt="">
              <h3>John Larson</h3>
              <h4>Entrepreneur</h4>
            </div>

        </div>-->
		
		<div class="col-lg-3 cta-btn-container text-center">
            <a class="cta-btn align-middle" href="contact">Get A Quote</a>
          </div>

      </div>
    </section>
