<template>
  <div id="about-me">
    <div class='container'>
              <h1>ABOUT ME</h1><br><br>
          <div class="row justify-content-evenly">
              <div class="col-sm-6"> 
                <div class='content'>
                   <h3>Hi, I'm Zharné Desember</h3> 
                   <p>I am an adventurous and open-minded person who is willing to learn new things and skills on a daily basis. I am ambitious and have set goals for myself to achieve in my career and for personal growth, which i work hard to achieve.</p>
                </div><br> 
                <div class="personal">
                  <h3>Personal details:</h3>
                  Date of birth: 02/05/1997 <br>
                  Gender: Female <br>
                  Location: Southern Suburbs <br>
                  Cell Phone number: 068 427 0352 <br>
                  Email Address: zharnedesember@gmail.com <br>
                  GitHub: https://github.com/Zharne <br>
                </div>
              </div>
            
                <div class="col-sm-6" style="padding-left:100px">
                  <div class='skills'>
                     <h4>This is my skill level</h4>
                    <small>CSS</small>
                    <div class="progress mb-3" style="height: 15px">
                      <div
                        class="progress-bar bg-primary"
                        role="progressbar"
                        style="width: 70%"
                        aria-valuenow="70"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div>
                    <small>HTML</small>
                    <div class="progress mb-3" style="height: 15px">
                      <div
                        class="progress-bar bg-primary"
                        role="progressbar"
                        style="width: 85%"
                        aria-valuenow="85"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div>
                    <small>JS</small>
                    <div class="progress mb-3" style="height: 15px">
                      <div
                        class="progress-bar bg-primary"
                        role="progressbar"
                        style="width: 65%"
                        aria-valuenow="65"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div> 
                    <small>NODE</small>
                    <div class="progress mb-3" style="height: 15px">
                      <div
                        class="progress-bar bg-primary"
                        role="progressbar"
                        style="width: 70%"
                        aria-valuenow="70"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div>
                    <small>MySQL</small>
                    <div class="progress mb-3" style="height: 15px">
                      <div
                        class="progress-bar bg-primary"
                        role="progressbar"
                        style="width: 70%"
                        aria-valuenow="70"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div>
                    <small>VUE.JS</small>
                    <div class="progress mb-3" style="height: 15px">
                      <div
                        class="progress-bar bg-primary"
                        role="progressbar"
                        style="width: 73%"
                        aria-valuenow="73"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div>
                </div>
                    <div class='resume'>
                        
                    </div> 
                </div>
        </div>
    </div>  
    </div>
</template>

<style>
#about-me{
  background-color: whitesmoke;
  /* padding-bottom: 30px; */
  height: 90vh;
  width: 80%;
  margin-left: 50px;
  margin-top: 50px;
}
.container{
    height: 80vh;
    margin-left: 200px;
    /* padding-bottom:30px ; */
}

/* Progress bar */
.bar{
  box-sizing: border-box;
  display: block;
  line-height: 30px;
  position: static;
  z-index: auto;
}
.background{
    position: relative;
    height: 16px;
    border: 1px solid #7e7e7e;
    padding: 2px;
}
.label{
  font-size: 16px;
  font-weight: 5px;
  display: inline-block;
}
.row{
  display: flex;
}

/* Media Queries */
@media screen and (max-width: 800px){
.row{
  display: initial;
}
.container{
  margin-left: 170px;
}
.personal{
  display: none;
}
}


</style>