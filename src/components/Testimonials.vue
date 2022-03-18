<template>
  <section>
<div id='testimonials'>
	<!-- <div class="container" v-if="testimonials.length">
		<div v-for = "testimonial in testimonials" :key="testimonial.id" class="testimonials">	
			<div class="row">
				<div class="col">
					<h2>Testimonials</h2>
					<div id="myCarousel" class="carousel slide" data-ride="carousel"> -->
						<!-- Carousel indicators -->
						<!-- <ol class="carousel-indicators">
							<li data-target="#myCarousel" data-slide-to="0" class="active"></li>
							<li data-target="#myCarousel" data-slide-to="1"></li>
							<li data-target="#myCarousel" data-slide-to="2"></li>
							<li data-target="#myCarousel" data-slide-to="3"></li>
							<li data-target="#myCarousel" data-slide-to="4"></li>
							<li data-target="#myCarousel" data-slide-to="5"></li>
						</ol>    -->
						<!-- Wrapper for carousel items -->
						<!-- <div class="carousel-inner">
							<div class="carousel-item active"><br>
								<div class="img-box"><img src="{{testimonials.img}}" alt=""></div>
								<p class="testimonial">{{testimonials.details}}</p>
								<p class="overview"><b>{{testimonials.name}}</b>,{{testimonials.position}}</p>
							</div>
						</div> -->
						<!-- Carousel controls -->
						<!-- <a class="carousel-control-prev" href="#myCarousel" data-slide="prev">
							<i class="fa fa-angle-left"></i>
						</a>
						<a class="carousel-control-next" href="#myCarousel" data-slide="next">
							<i class="fa fa-angle-right"></i>
						</a>
					</div>
				</div>
			</div>
		</div>
	</div> -->
</div>	
</section>
</template>

<script>
export default {
	 data() {
    return {
      testimonials: []
    }
  },
  mounted() {
    fetch('https://zharneportfolio.herokuapp.com/testimonials')
      .then(res => res.json())
      .then(data => this.testimonials = data)
      .catch(err => console.log(err.message))
  }
}
</script>

<style scoped>
section{
	height: 100vh;
	margin-top: 50vh;
}
.row{
	margin-left: 100px;
} 
#testimonials{
	width: 80%;
	background-color:  #111;
	margin-left: 250px;
	margin-top: 70vh;
	border-radius:10px ;

} 
.carousel-indicators{
	bottom: 0;
}
.container{
    margin-left: 100px;
	
} 
.container-xl{
    margin-top: 20vh;
	margin-left: 420px;
}
h2 {
	color: #333;
	text-align: center;
	text-transform: uppercase;
	font-family: "Roboto", sans-serif;
	font-weight: bold;
	position: relative;
	margin: 30px 0 60px;
}
h2::after {
	content: "";
	width: 100px;
	position: absolute;
	margin: 0 auto;
	height: 3px;
	background: #8fbc54;
	left: 0;
	right: 0;
	bottom: -10px;
}
.col-center {
	margin: 0 auto;
	float: none !important;
}
.carousel {
	padding: 0 70px;
}
.carousel .carousel-item {
	color: #999;
	font-size: 14px;
	text-align: center;
	overflow: hidden;
	min-height: 290px;
}
.carousel .carousel-item .img-box {
	width: 135px;
	height: 135px;
	margin: 0 auto;
	padding: 5px;
	border: 1px solid #ddd;
	border-radius: 50%;
}
.carousel .img-box img {
	width: 100%;
	height: 100%;
	display: block;
	border-radius: 50%;
}
.carousel .testimonial {
	padding: 30px 0 10px;
}
.carousel .overview {	
	font-style: italic;
}
.carousel .overview b {
	text-transform: uppercase;
	color: #7AA641;
}
.carousel-control-prev, .carousel-control-next {
	width: 40px;
	height: 40px;
	margin-top: -20px;
	top: 50%;
	background: none;
}
.carousel-control-prev i, .carousel-control-next i {
	font-size: 68px;
	line-height: 42px;
	position: absolute;
	display: inline-block;
	color: rgba(0, 0, 0, 0.8);
	text-shadow: 0 3px 3px #e6e6e6, 0 0 0 #000;
}
/* .carousel-indicators {
	bottom: -5px;
} */
.carousel-indicators li, .carousel-indicators li.active {
	width: 12px;
	height: 12px;
	margin: 1px 3px;
	border-radius: 50%;
	border: none;
}
.carousel-indicators li {	
	background: #7AA641;
	border-color: transparent;
	box-shadow: inset 0 2px 1px rgba(0,0,0,0.2);
}
.carousel-indicators li.active {	
	background: #555;		
	box-shadow: inset 0 2px 1px rgba(0,0,0,0.2);
}
</style>