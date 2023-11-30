# SlimFit-Gens: Extremely-low Bandwidth One-on-one Video Calls on Mobile Devices
<html>
    <head>
        <link href="css/bootstrap-4.4.1.css" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet" type="text/css">
        <style>
            element.style {
                color: #8899a5;
                font-size: 12px;
            }
            p {
                margin-top: 0;
                margin-bottom: 1rem;
            }
            .col {
                flex-basis: 0;
                flex-grow: 1;
                max-width: 100%;
            }

            .text-center {
                text-align: center !important;
            }
            *, *::before, *::after {
                box-sizing: border-box;
            }
            @media (min-width: 576px)
                .container, .container-sm {
                    max-width: 540px;
            }
            .container {
                width: 100%;
                padding-right: 15px;
                padding-left: 15px;
                margin-right: auto;
                margin-left: auto;
            }
            div {
                display: block;
            }
            .row {
                display: flex;
                flex-wrap: wrap;
                margin-right: -15px;
                margin-left: -15px;
            }
            .col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12, .col, .col-auto, .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm, .col-sm-auto, .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12, .col-md, .col-md-auto, .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg, .col-lg-auto, .col-xl-1, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl, .col-xl-auto {
                position: relative;
                width: 100%;
                padding-right: 15px;
                padding-left: 15px;
            }
            .img-fluid {
                max-width: 100%;
                height: auto;
            }
            img {
                vertical-align: middle;
                border-style: none;
            }
            img[Attributes Style] {
                width: 45%;
            }
            .embed-responsive {
                position: relative;
                display: block;
                width: 100%;
                padding: 0;
                overflow: hidden;
            }
            @media screen and (max-width: 42em)
                .btn {
                    display: none;
                    width: 100%;
                    padding: 0.75rem;
                    font-size: 0.9rem;
            }
            @media screen and (max-width: 42em)
                .site-footer {
                    display: none;
                    font-size: 0.9rem;
            }
            hr.style11 {
            	height: 6px;
            	background: url(http://ibrahimjabbari.com/images/hr-11.png) repeat-x 0 0;
                border: 0;
            }
             
             
            hr.style12 {
            	height: 6px;
            	background: url(http://ibrahimjabbari.com/images/hr-12.png) repeat-x 0 0;
                border: 0;
            }
             
            hr.style13 {
            	height: 10px;
            	border: 0;
            	box-shadow: 0 10px 10px -10px #8c8b8b inset;
            }
             
             
            hr.style14 { 
              border: 0; 
              height: 1px; 
              background-image: -webkit-linear-gradient(left, #f0f0f0, #8c8b8b, #f0f0f0);
              background-image: -moz-linear-gradient(left, #f0f0f0, #8c8b8b, #f0f0f0);
              background-image: -ms-linear-gradient(left, #f0f0f0, #8c8b8b, #f0f0f0);
              background-image: -o-linear-gradient(left, #f0f0f0, #8c8b8b, #f0f0f0); 
            }
             
             
            hr.style15 {
            	border-top: 4px double #8c8b8b;
            	text-align: center;
            }
            hr.style15:after {
            	content: '\002665';
            	display: inline-block;
            	position: relative;
            	top: -15px;
            	padding: 0 10px;
            	background: #f0f0f0;
            	color: #8c8b8b;
            	font-size: 18px;
            }
            hr.style16 { 
              border-top: 1px dashed #8c8b8b; 
            } 
            hr.style16:after { 
              content: '\002702'; 
              display: inline-block; 
              position: relative; 
              top: -12px; 
              left: 40px; 
              padding: 0 3px; 
              background: #f0f0f0; 
              color: #8c8b8b; 
              font-size: 18px; 
            }
            hr.style17 {
            	border-top: 1px solid #8c8b8b;
            	text-align: center;
            }
            hr.style17:after {
            	content: '§';
            	display: inline-block;
            	position: relative;
            	top: -14px;
            	padding: 0 10px;
            	background: #f0f0f0;
            	color: #8c8b8b;
            	font-size: 18px;
            	-webkit-transform: rotate(60deg);
            	-moz-transform: rotate(60deg);
            	transform: rotate(60deg);
            }
            hr.style18 { 
              height: 30px; 
              border-style: solid; 
              border-color: #8c8b8b; 
              border-width: 1px 0 0 0; 
              border-radius: 20px; 
            } 
            hr.style18:before { 
              display: block; 
              content: ""; 
              height: 30px; 
              margin-top: -31px; 
              border-style: solid; 
              border-color: #8c8b8b; 
              border-width: 0 0 1px 0; 
              border-radius: 20px; 
            }
            body {
                background: #fdfcf9 no-repeat fixed top left;
                font-family:'Open Sans', sans-serif;
              }
            .jumbotron {
              /* padding: 1rem 1rem; */
              margin-bottom: 1rem;
              background-color: #ebf0f1; /*#e9ecef;*/ 
              border-radius: 0.3rem;
            }
            
            @media (min-width: 576px) {
              .jumbotron {
                padding: 4rem 2rem;
              }
            }
            
            .jumbotron-fluid {
              padding-right: 0;
              padding-left: 0;
              border-radius: 0;
            }
        </style>
    </head>

<!-- cover -->
  <section>
    <div class="jumbotron text-center mt-0">
      <div class="container">
        <div class="row">
          <div class="col">
            <h2 style="font-size:30px;">NeuralRecon: Real-Time Coherent 3D Reconstruction from Monocular Video</h2>
            <h4 style="color:#6e6e6e;"> CVPR 2021</h4>
            <h5 style="color:#6e6e6e;"> (Oral Presentation and Best Paper Candidate)</h5>
            <hr>
            <h6> <a href="https://jiamingsun.ml/" target="_blank">Jiaming Sun</a><sup>1,2*</sup>, 
                 <a href="https://ymingxie.github.io/" target="_blank">Yiming Xie</a><sup>1*</sup>, 
                 <!-- <a href="https://ymingxie.github.io/" target="_blank">Yiming Xie</a><sup>1,2*</sup>,  -->
                <a href="https://ootts.github.io/" target="_blank">Linghao Chen</a><sup>1</sup>,
                <a href="http://xzhou.me" target="_blank">Xiaowei Zhou</a><sup>1</sup>,
                <a href="http://www.cad.zju.edu.cn/bao/" target="_blank">Hujun Bao</a><sup>1</sup></h6>
            <p> <sup>1</sup>State Key Lab of CAD & CG, Zhejiang University &nbsp;&nbsp; 
                <sup>2</sup>SenseTime Research
                <br>
                <sup>*</sup> denotes equal contribution
            </p>
            <!-- <p> <a class="btn btn-secondary btn-lg" href="" role="button">Paper</a> 
                <a class="btn btn-secondary btn-lg" href="" role="button">Code</a> 
                <a class="btn btn-secondary btn-lg" href="" role="button">Data</a> </p> -->

            <div class="row justify-content-center">
              <div class="column">
                  <p class="mb-5"><a class="btn btn-large btn-light" href="https://arxiv.org/pdf/2104.00681.pdf" role="button"  target="_blank">
                    <i class="fa fa-file"></i> Paper</a> </p>
              </div>
              <div class="column">
                  <p class="mb-5"><a class="btn btn-large btn-light" id="code_soon" href="https://github.com/zju3dv/NeuralRecon" role="button" 
                    target="_blank" disabled=1>
                <i class="fa fa-github-alt"></i> Code </a> </p>
              </div>
              <div class="column">
                  <p class="mb-5"><a class="btn btn-large btn-light" href="files/NeuralRecon-suppmat.pdf" role="button"  target="_blank">
                    <i class="fa fa-file"></i> Supplementary</a> </p>
              </div>
            </div>
            
          </div>
        </div>
      </div>
    </div>
  </section>
    
    <body>
        <!-- Video Show -->
        <br>
        <section>
            <div class="container">
                <div class="row">
                    <div class="col-12 text-center">
                        <h3>Video Show</h3>
                        <!-- <hr style="margin-top:0px"> -->
                        <hr class="style14">
                        <br>
                    </div>
                </div>
            </div> 
        </section>
        <section>
            <div class="container">
                <div class="row">
                    <div class="col text-center">
                        <!-- <video width="100%" playsinline controls autoplay loop="loop" preload muted> -->
                            <!-- <source src="https://github.com/growthin2023/VIDAR.github.io/releases/download/v0.0/third_view.mp4" type="video/mp4"> -->
                        <!-- </video> -->
                        <!-- <img class="img-fluid" src="https://github.com/anoymousauthor/anoymousauthor.github.io/releases/download/v0.0/video.png" alt="Mobile3DScanner Teaser" width="100%"> -->
                        <img class="img-fluid" src="data/video/video.png" alt="Mobile3DScanner Teaser" width="100%">
                    </div>
                    <hr class="style13">
                </div>
            </div>
        </section>
    
        <br>
        <br>

        <!-- Model Structure -->
        <br>
        <section>
    		<div class="container">
    			<div class="row">
    				<div class="col-12 text-center">
    					<h3>Model Structure</h3>
    					<!-- <hr style="margin-top:0px"> -->
                        <hr class="style14">
    					<br>
    				</div>
    			</div>
    		</div> 
    	</section>
    	<section>
    		<div class="container">
    			<div class="row">
                   <div class="col-12 text-left">
                        <h3>KPD:</h3>
                        <hr class="style10">
                    </div>
    				<div class="col text-center">
    					<img class="img-fluid" src="data/model/KPD.png" alt="KPD Network structure" width="100%">
    				</div>
    			</div>
    
    			<div class="row">
                   <div class="col-12 text-left">
                        <br>
                        <h3>PMG:</h3>
                        <hr class="style10">
                    </div>
    				<div class="col text-center">
    					<img class="img-fluid" src="data/model/PMG.png" alt="PMG Network structure" width="100%">
    				</div>
    			</div>
        
    			<div class="row">
                    <div class="col-12 text-left">
                        <br>
                        <h3>AFG:</h3>
                        <hr class="style10">
                    </div>
    				<div class="col text-center">
    					<img class="img-fluid" src="data/model/AFG.png" alt="AFG Network structure" width="100%">
    				</div>
                    <br>
                    <hr class="style13">
    			</div>
    		</div>
    	</section>
    
        <br>
        <br>

        <!-- Phone Demo -->
        <br>
        <section>
            <div class="container">
                <div class="row">
                    <div class="col-12 text-center">
                        <h3>Phone Demo</h3>
                        <!-- <hr style="margin-top:0px"> -->
                        <hr class="style10">
                        <br>
                    </div>
                </div>
            </div> 
        </section>
        <section>
            <div class="container">
                <div class="row">
                    <div class="col text-center">
                        <video hight="50%" width="20%" playsinline controls autoplay loop="loop" preload muted>
                            <source src="https://github.com/anoymousauthor/anoymousauthor.github.io/releases/download/v0.0/phone.demo.mp4" type="video/mp4">
                        </video>
                    </div>
                    <br>
                    <hr class="style13">
                </div>
            </div>
        </section>
    
        <br>
        <br>
    
    </body>

</html>
