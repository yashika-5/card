<!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<style type="text/css">

@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');
#team {
    background: #eee !important;
}

.btn-primary:hover,
.btn-primary:focus {
    background-color: #108d6f;
    border-color: #108d6f;
    box-shadow: none;
    outline: none;
}

.btn-primary {
    color: #fff;
    background-color: #007b5e;
    border-color: #007b5e;
}

section {
    padding: 60px 0;
}

section .section-title {
    text-align: center;
    color: #007b5e;
    margin-bottom: 50px;
    text-transform: uppercase;
}

#team .card {
    border: none;
    background: #ffffff;
}

.image-flip:hover .backside,
.image-flip.hover .backside {
    -webkit-transform: rotateY(0deg);
    -moz-transform: rotateY(0deg);
    -o-transform: rotateY(0deg);
    -ms-transform: rotateY(0deg);
    transform: rotateY(0deg);
    border-radius: .25rem;
}

.image-flip:hover .frontside,
.image-flip.hover .frontside {
    -webkit-transform: rotateY(180deg);
    -moz-transform: rotateY(180deg);
    -o-transform: rotateY(180deg);
    transform: rotateY(180deg);
}

.mainflip {
    -webkit-transition: 1s;
    -webkit-transform-style: preserve-3d;
    -ms-transition: 1s;
    -moz-transition: 1s;
    -moz-transform: perspective(1000px);
    -moz-transform-style: preserve-3d;
    -ms-transform-style: preserve-3d;
    transition: 1s;
    transform-style: preserve-3d;
    position: relative;

}

.frontside {
    position: relative;
    -webkit-transform: rotateY(0deg);
    -ms-transform: rotateY(0deg);
    z-index: 2;
    margin-bottom: 30px;
    background-color: purple;
}

.backside {
    position: absolute;
    top: 0;
    left: 0;
    background: purple;
    -webkit-transform: rotateY(-180deg);
    -moz-transform: rotateY(-180deg);
    -o-transform: rotateY(-180deg);
    -ms-transform: rotateY(-180deg);
    transform: rotateY(-180deg);
    -webkit-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
    -moz-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
    box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
}

.frontside,
.backside {
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    -ms-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-transition: 1s;
    -webkit-transform-style: preserve-3d;
    -moz-transition: 1s;
    -moz-transform-style: preserve-3d;
    -o-transition: 1s;
    -o-transform-style: preserve-3d;
    -ms-transition: 1s;
    -ms-transform-style: preserve-3d;
    transition: 1s;
    transform-style: preserve-3d;
}

.frontside .card,
.backside .card {
    min-height: 312px;
}

.backside .card a {
    font-size: 18px;
    color: black !important;
}

.frontside .card .card-title,
.backside .card .card-title {
    color: #007b5e !important;
}

.frontside .card .card-body img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
}
@media only screen and (max-width: 320px){
    .card-body img{
        width: 80%;
    }
    .card-title{
        visibility: hidden;
    }
    .card-text{
        visibility: hidden;
    }
}
@media only screen and (max-width: 320px){
    .backside{

    }
}

    

</style>


<body>
<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<!------ Include the above in your HEAD tag ---------->

<!-- Team -->
<section id="team" class="pb-5">
    <div class="container">
        <h5 class="section-title h1">OUR TEAM</h5>
        <div class="row">
            <!-- Team member -->
            <div class="col-xs-2 col-sm-6 col-md-4">
                <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
                    <div class="mainflip">
                        <div class="frontside" style="background-color: ">
                            <div class="card" style="background-color: gray;width: 100%">
                                <div class="card-body text-center">
                                    <p><img class=" col-xs-2 col-sm-6 col-md-4" src="pic1.jpg" alt="card image"></p>
                                    <h4 class="card-title" style="color: black;">Yashika Gupta</h4>
                                    <p class="card-text">This is basic card with image on top, title, description and button.</p>
                                    <a href="#" class="btn btn-primary btn-sm"><i class="fa fa-plus"></i></a>
                                </div>
                            </div>
                        </div>
                        <div class="backside" style="width: 100%;">
                            <div class="card" style="width: 100%; background-color: gray">
                                <div class="card-body text-center mt-4" style="color: white">
                                   <div style="color: black"><b>Yashika Gupta</b></div>
                                  <div class="p1" style="margin-left: 47%;color: black"><b>Skills</b><br></div>
                                  <div class="p4" style="margin-left:43%;">   HTML,CSS,JS,Jquery,SQL</div>
                                  <br>
                                 <div class="p2" style="margin-left: 44%;color: black;"><b>Currently Studying</b><br></div>
                                 <div class="p5" style="margin-left: 44%;">Core Java & Python</div>
                                 <br>

                                 <div class="p3" style="margin-left: 45%; color: black;"><b>Experience</b></div>
                                 <div class="p6" style="margin-left: 34%;">There was a good experience with Oraganisation Student Development(OSD).</div>
                                 <br><br>
                                   <div class="p7" style="color: black; margin-left: 40%">
                                           <a href="https://www.facebook.com/profile.php?id=100012481271492"><i class="fa fa-facebook" style="font-size: 30px; margin-top: 70px;margin-right: 35px;margin-left: 35px;"></i></a>
    
    </a>
    <a href="https://www.linkedin.com/in/yashika05/"><i class="fa fa-linkedin" style="font-size: 30px; margin-top: 70px;margin-right: 35px;"></i></a>
        
    </a>
    <a href="https://twitter.com/y20747250"><i class="fa fa-twitter" style="font-size: 30px; margin-top: 70px;margin-right: 35px;"></i></a>
    
    </a>
    <a href="https://plus.google.com/people"><i class="fa fa-google" style="font-size: 30px; margin-top: 70px;margin-right: 35px;"></i></a>
        
    </a>
                                            
                                </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- ./Team member -->
            
        </div>
    </div>
</section>
<!-- Team -->
</body>
</html>
