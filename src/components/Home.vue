<template>
<div id="home">
    <div class="container"><br><br><br><br>
        <div class='img-box'>
            <img src="https://i.postimg.cc/Gp5rLhQK/me-shot-min.jpg" style="border-radius:50%">
        </div><br>
            <h1>ZHARNÉ DESEMBER</h1> 
        <br>
        <div class="button">
             <div class="slide-btn mt-10" data-v-e4caeaf8="">
                <a class="rf-btn" target="_blank" href="https://docs.google.com/document/d/1BNq0GgOnKe2GsPqXlD5l_oy9zYZPytQMoJMmDJ7Hpfc/edit" data-v-e4caeaf8="">Download CV</a>
            </div>
        </div> 
        <div class="socials">
            <ul>
                <li>
                <a href="https://codepen.io/your-work/?search_term=&cursor=ZD0xJm89MCZwPTEmdj01NzcxMjU1MQ==" target="_blank" class="contact-icon">
                <i class="fab fa-codepen" aria-hidden="true"></i></a>
          
                </li>
                <li>
                    <a href="https://github.com/Zharne" target="_blank" class="contact-icon">
             <!-- <i class="fab fa-github" aria-hidden="true"></i></a> -->
            <i class="fab fa-github"></i></a> 
                </li>
                <li>
                    <a href="https://www.linkedin.com/in/zharné-desember-795b8416b" target="_blank"><i class="fab fa-linkedin-in icon"></i></a></li>
                <!-- <li>
                    <a href="#"><i class="fab fa-google-plus-g icon"></i></a></li> -->
            </ul>
        </div>            
    </div>  
</div>      
</template>

<script>


</script>

<style scoped>
.container{
    background-color:  #111;
    height: 100vh;
    margin-left: 250px;
    width: 80%;
    border-radius:10px

} 
h1{
    color:#f00;
    text-shadow: 2px 2px 5px gray;
}
.img-box {
	width: 200px;
	height: 200px;
	margin: 0 auto;
	padding: 5px;
	border: 1px solid #ddd;
	border-radius: 50%;
    
}
.img-box img {
	width: 100%;
	height: 100%;
	display: block;
	border-radius: 50%;
    
}
.button{
    margin-top: 13%;
}
.rf-btn {
    margin-top: 30px;
    display: inline-block;
    padding: 10px 30px;
    height: 50px;
    border-radius: 50px;
    font-size: 16px;
    font-weight: 500;
    text-transform: uppercase;
    transition: .3s ease-in-out;
    color: #fff !important;
    /* background: ; */
    border: 2px solid white;
    box-shadow: 0 5px 20px -5px rgba(0,0,0,.05);
    font-weight: bold;
}

.rf-btn:hover  {
    color: white;
    background: rgba(13, 95, 226, 0.507);
}

ul {
  display: flex;
  position: absolute;
  top: 68%;
  left: 58%;
  transform: translate(-50%, -50%);
}

ul li {
  list-style: none;
}

ul li a {
  width: 70px;
  height: 70px;
  background-color: #fff;
  text-align: center;
  line-height: 80px;
  font-size: 35px;
  margin: 0 10px;
  display: block;
  border-radius: 50%;
  position: relative;
  overflow: hidden;
  border: 3px solid #fff;
  z-index: 1;
}

ul li a .icon {
  position: relative;
  color: #262626;
  transition: .5s;
  z-index: 3;
}

ul li a:hover .icon {
  color: #fff;
  transform: rotateY(360deg);
}

ul li a:before {
  content: "";
  position: absolute;
  top: 100%;
  left: 0;
  width: 100%;
  height: 100%;
  background: #f00;
  transition: .5s;
  z-index: 2;
}

ul li a:hover:before {
  top: 0;
}

ul li:nth-child(1) a:before{
  background: #3b5999;
}

ul li:nth-child(2) a:before{
  background: #55acee;
}

ul li:nth-child(3) a:before {
  background: #0077b5;
}

ul li:nth-child(4) a:before {
  background: #dd4b39;
}

/* Media Queries */
@media screen and (max-width: 800px){
.container{
    margin-left: 220px;
    width: 60%;
}    
ul{
    position: -ms-page;
    top: 73%;
    left: 63%;
}
}
/* 
@keyframes img-box {
  0%,
  49% {
    background: black;
  }
  50%,
  100% {
    background: white;
  }
} */

</style>