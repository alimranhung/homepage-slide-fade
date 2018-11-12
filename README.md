# Bootstrap-4-slide
##click RAW
``Homepage slide fade for html and css flowing the bellow
``
##HTML
 <section id="showcase" class="bg-dark">
		        <div id="myCarousel" class="carousel carousel-fade" data-ride="carousel" data-interval="50000">
		          <ol class="carousel-indicators">
		            <li data-slide-to="0" data-target="#myCarousel" class="active"></li>
		            <li data-slide-to="1" data-target="#myCarousel"></li>
		            <li data-slide-to="2" data-target="#myCarousel"></li>
		          </ol>
		            <div class="carousel-inner">
		                <div class="carousel-item carousel-bg-1 active">
		                    <div class="container">
		                        <div class="carousel-caption h-100">
		                          <div class="hero-area-table d-table w-100 h-100">
		                            <div class="hero-area-tablcell d-table-cell align-middle">
		                               <h1 class="mb-3">Your Heading.....</h1>
		                                <p>your content.....</p>
		                                <a href="#" class="btn btn-danger py-2 px-3">Learn more</a>
		                          </div>
		                        </div>
		                      </div>
		                    </div>
		                </div>
		                <div class="carousel-item carousel-bg-2">
		                    <div class="container">
		                        <div class="carousel-caption h-100">
		                          <div class="hero-area-table d-table w-100 h-100">
		                            <div class="hero-area-tablcell d-table-cell align-middle">
		                            <h1 class="mb-3">Your Heading.....</h1>
		                                <p>your content.....</p>
		                                <a href="#" class="btn btn-primary py-2 px-3">Learn more</a>
		                          </div>
		                        </div>
		                      </div>
		                    </div>
		                </div>
		                <div class="carousel-item carousel-bg-3">
		                    <div class="container">
		                        <div class="carousel-caption h-100">
		                          <div class="hero-area-table d-table w-100 h-100">
		                            <div class="hero-area-tablcell d-table-cell align-middle">
		                                <h1 class="mb-3">Your Heading.....</h1>
		                                <p>your content.....</p>
		                                <a href="#" class="btn btn-warning py-2 px-3">Learn more</a>
		                          </div>
		                        </div>
		                      </div>
		                    </div>
		                </div>
		            </div>
		            <a href="#myCarousel" class="carousel-control-prev" role="button" data-slide="prev">
		              <span class="fa fa-long-arrow-left" aria-hidden="true"></span>
		            </a>
		            <a href="#myCarousel" class="carousel-control-next" role="button" data-slide="next">
		              <span class="fa fa-long-arrow-right" aria-hidden="true"></span>
		            </a>
		        </div>
		    </section>
        
        
 ``CSS fade for CSS
 ``
 
/*HOMEPAGE CAROUSEL FADE PROPARTY AND CSS START*/
``
#carouselBeadManRedding {
    background-color: #000;
}
.carousel.carousel-fade .carousel-item {
    display: block;
    opacity: 0;
    transition: opacity ease-out 1.7s;
    left: 0;
    top: 0;
    position: absolute;
}
.carousel.carousel-fade .carousel-item.active {
    opacity: 1 !important;
}
.carousel.carousel-fade .carousel-item:first-child {
    top: auto;
    position: relative;
    transition: opacity ease-out 1.7s;
}
.carousel.carousel-fade .carousel-item:second-child {
    top: auto;
    position: relative;
    transition: opacity ease-out 1.7s;
}
.carousel-item .img-fluid {
    margin: 0 auto;
}
.carousel img {
    opacity: 0.5;
    filter: alpha(opacity=50);
}
``
/*HOMEPAGE CAROUSEL FADE PROPARTY AND CSS END*/
        
