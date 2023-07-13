<template>


    <div class="top-pic">
       
       <div class="col-sm-3">

           <img src="../assets/img/car/showcase1.gif" alt="">

    
       </div>
       <div class="col-sm-3">

           <img src="../assets/img/car/showcase2.gif" alt="">
        
       </div>
       <div class="col-sm-3">
       
           <img src="../assets/img/car/showcase3.gif" alt="">
           
       
       </div>
       <div class="col-sm-3">
         
              <img src="../assets/img/car/showcase4.gif" alt="">
          
           
       </div>
       <div class="col-sm-3">
  
           <img src="../assets/img/car/showcase5.gif" alt="">
        
       </div>
     </div>

     <nav id="navigation" class="navbar navbar-expand-lg">
        <a class="navbar-brand" href="index.html">Gary Tracey</a>
    
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
    
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#about">About <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#skills">Skills</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#stats">Stats</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#portfolio">Portfolio</a>
                </li>
            </ul>
        </div>
    
    </nav>



</template>
<script>
//  import $ from 'jquery';

// var skillsTopOffset = $(".skillSection").offset().top;
//     var statsTopOffset = $(".statsSection").offset().top;
//     var countUpFinished =false;
    export default {
        name: 'LandingPage',
        data() {
            return {
                msg: 'Welcome to my Vue.js App'
            }
    //         $(window).scroll(function(){
    //     console.log(window.pageYOffset);
    //     if(window.pageYOffset >skillsTopOffset - $(window).height() + 200){
    //         $('.chart').easyPieChart({
    //             easing: 'easeInOut',
    //             barColor: '#fff',
    //             trackColor: false,
    //             scaleColor: false,
    //             lineWidth: 4,
    //             size:152,
    //             onStep:function(from, to, percent){
    //                 $(this.el).find('.percent').text(Math.round(percent));
                     
    //             }
        
    //         });
    //     }
    //     if(!countUpFinished && window.pageYOffset >statsTopOffset - $(window).height() + 200){ 
    //         $(".counter").each(function(){
    //             var element = $(this);
    //             var endVal = parseInt(element.text());
    //             element.countup(endVal);
    //         });
    //         countUpFinished = true;

    //     }
    // })
       
        }
    }
</script>
<style>

.top-pic{
    margin: 0;
    padding: 150px;
    background-color: #000000;
    height: 1200px;
    width: 100%;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    overflow: hidden;
}

.top-pic img{
    /* margin: 0;
    padding: 0;
    background-color: #000000; */
    height: 100%;
    width: 500px;
    /* display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden; */
}


/* .slides-navigation {
	z-index: 6;
}
.slides-navigation .prev,
.slides-navigation .next {
width: 47px;
height: 47px;
background-size:cover;
background-repeat: no-repeat;
} */
/* .slides-navigation a.prev{
left: 20px;
background-image: url(../assets/img/icons/prev.png);
}

.slides-navigation a.next{
    right: 20px;
    background-image: url(../assets/img/icons/next.png);
}
.titleMessage{
    position: absolute;
    width: 100%;
    height: 250px;
    top: 50%;
    z-index: 5;
    text-align: center;
    margin-top: -125px;
   
} */
/* .titleMessage .heading p{
    color: #ffffff;
    text-shadow:0px 2px 5px rgba(0,0,0,0.4);
    font-weight: 100;
    letter-spacing: 7px;
    
} */

/* .titleMessage .heading .main{
    font-size: 50px;

}
.titleMessage .heading .sub{
    font-size: 23px;
   
} */

#navigation{
    background-color: #176cb7;
    padding: 20px 10px;
    width: 100%; 
    z-index: 100;
 }

 #navigation li{
    display: inline-block;
    padding: 0px 10px;
 }

 #navigation li a{
    color: #ffffff;
 }

 .navbar-brand,
 .navbar-brand:hover{
    color: #c92323;
    /* font-size: 20px;
    font-weight: 600;
    padding: 0px; */
 }
 .navbar-toggler-icon{
    background: url(../assets/img/icons/navmenu.png) no-repeat center center;
    background-size: 100%;
 }

 .section{      
    padding: 100px 0;
}
.aboutImage{
    max-width: 100%;
}

.skillSection{
    background-color: #2b3238;
    color: #ffffff;
}
.skill{
    text-align: center;
    margin-left: 10px;
}
.chart{
    position: relative;
    width: 152px;
    height: 152px;
    display: inline-block;
    text-align: center;
}
.chart canvas{
    position: absolute;
    top: 0;
    left: 0;
}
.chart .percent{
 
    color: #b21b50;
    line-height: 152px;
    display: inline-block;
    font-size: 35px;
}
.chart .percent:after{
    content: '%';

}

</style>