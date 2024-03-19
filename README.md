# SlimFit-Gens: Extremely-low Bandwidth One-on-one Portrait Video Calls on Mobile Devices
<html>
    <head>
        <link href="css/bootstrap-4.4.1.css" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet" type="text/css">
                <style>
            element.style {
                color: #8899a5;
                font-size: 12px;
            }
            span {
                font-size: 20px;
                font-weight: bolder;
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

            hr.style1{
                border-top: 1px solid #8c8b8b;
            }
            
            
            hr.style2 {
                border-top: 3px double #8c8b8b;
            }
            
            hr.style3 {
                border-top: 1px dashed #8c8b8b;
            }
            
            hr.style4 {
                border-top: 1px dotted #8c8b8b;
            }
            
            hr.style5 {
                background-color: #fff;
                border-top: 2px dashed #8c8b8b;
            }
            
            
            hr.style6 {
                background-color: #fff;
                border-top: 2px dotted #8c8b8b;
            }
            
            hr.style7 {
                border-top: 1px solid #8c8b8b;
                border-bottom: 1px solid #fff;
            }
            
            
            hr.style8 {
                border-top: 1px solid #8c8b8b;
                border-bottom: 1px solid #fff;
            }
            hr.style8:after {
                content: '';
                display: block;
                margin-top: 2px;
                border-top: 1px solid #8c8b8b;
                border-bottom: 1px solid #fff;
            }
            
            hr.style9 {
                border-top: 1px dashed #8c8b8b;
                border-bottom: 1px dashed #fff;
            }
            
            hr.style10 {
                border-top: 1px dotted #8c8b8b;
                border-bottom: 1px dotted #fff;
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
                background: #ffffff no-repeat fixed top left;
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
            .steps {
                /* --normal-color: #666; */
                /* --normal-color: #6e6e6e; */
                /* --normal-color: #74f1b9; */
                --normal-color: #159957;
                /* --active-color: #06e; */
                /* --active-color: #6e6e6e; */
                /* --active-color: #6c6c91; */
                /* --active-color: #42b983; */
                /* --active-color: #42b983; */
                /* --active-color: #000000; */
                --active-color: #585656;
                display: flex;
                justify-content: space-between;
                padding: 0;
                margin: 0;
                counter-reset: order;
                }
            /* 步骤项 */
            .steps > li {
            flex: auto;
            display: inline-flex;
            align-items: center;
            counter-increment: order;
            color: var(--active-color);
            }
            .steps > li:last-child {flex: none;}
            /* 步骤编号（带圈数字） */
            .steps > li::before {
            content: counter(order);
            flex-shrink: 0;
            width: 1.4em;
            line-height: 1.4em;
            margin-right: .5em;
            text-align: center;
            border-radius: 50%;
            border: 1px solid;
            }
            /* 步骤项引导线 */
            .steps > li:not(:last-child)::after {
            content: '';
            flex: 1;
            margin: 0 1em;
            border-bottom: 1px solid;
            opacity: .6;
            }
            /* 步骤状态 */
            .steps > .active {color: var(--active-color);}
            .steps > .active::before {
            color: #fff;
            background: var(--active-color);
            border-color: var(--active-color);
            }
            .steps > .active::after,
            .steps > .active ~ li {color: var(--normal-color);}
        </style>
    </head>

    <body>
        <!-- Video Show -->
        <br>
        <section>
            <div class="container">
                <div class="row">
                    <div class="col-12 text-center">
                        <h2 style="font-size:30px;"> Qualitative comparisons on the Voxceleb dataset </h2>
                        <hr style="margin-top:0px">
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
                        <!-- <img class="img-fluid" src="data/video/video.png" alt="model performance video" width="80%"> -->
                        <!-- font-weight: bolder; -->
                        <h3 style="font-size:20px; color:black;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Origin&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FOM
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LBVC
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ECFA
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ours
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;H.264@10kbps</h3>
                        <video hight="100%" width="100%" playsinline controls autoplay loop="loop" preload muted>
                            <source src="https://github.com/anoymousauthor/anoymousauthor.github.io/releases/download/v1.0/out1.mp4" type="video/mp4">
                        </video>
                        <video hight="100%" width="100%" playsinline controls autoplay loop="loop" preload muted>
                            <source src="https://github.com/anoymousauthor/anoymousauthor.github.io/releases/download/v1.0/out2.mp4" type="video/mp4">
                        </video>
                        <video hight="100%" width="100%" playsinline controls autoplay loop="loop" preload muted>
                            <source src="https://github.com/anoymousauthor/anoymousauthor.github.io/releases/download/v1.0/out3.mp4" type="video/mp4">
                        </video>
                        <video hight="100%" width="100%" playsinline controls autoplay loop="loop" preload muted>
                            <source src="https://github.com/anoymousauthor/anoymousauthor.github.io/releases/download/v1.0/out4_1.mp4" type="video/mp4">
                        </video>
                    </div>
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
    					<h3 style="font-size:30px;">Model Structure</h3>
    					<hr style="margin-top:0px">
    					<br>
    				</div>
    			</div>
    		</div> 
    	</section>
    	<section>
    		<div class="container">
    			<div class="row">
                   <div class="col-12 text-center">
                        <h3 style="font-size:25px; ">KPD Network Structure:</h3>
                        <ol class="steps" width="50%" style="font-size:20px;">
                            <li class="active">KPD</li>
                            <li>PMG</li>
                            <li>AFG</li>
                        </ol>
                        <br>
                    </div>
    				<div class="col text-center">
    					<img class="img-fluid" src="data/model/KPD.png" alt="KPD Network structure" width="100%">
    				</div>
    			</div>
    
    			<div class="row">
                   <div class="col-12 text-center">
                        <br>
                        <h3 style="font-size:25px; ">PMG Network Structure:</h3>
                        <ol class="steps" width="50%" style="font-size:20px;">
                            <li class="done">KPD</li>
                            <li class="active">PMG</li>
                            <li>AFG</li>
                        </ol>
                        <br>
                    </div>
    				<div class="col text-center">
    					<img class="img-fluid" src="data/model/PMG.png" alt="PMG Network structure" width="100%">
    				</div>
    			</div>
        
    			<div class="row">
                    <div class="col-12 text-center">
                        <br>
                        <h3 style="font-size:25px; ">AFG Network Structure:</h3>
                        <ol class="steps" width="50%" style="font-size:20px;">
                            <li class="done">KPD</li>
                            <li class="done">PMG</li>
                            <li class="active">AFG</li>
                        </ol>
                        <br>
                    </div>
    				<div class="col text-center">
    					<img class="img-fluid" src="data/model/AFG.png" alt="AFG Network structure" width="100%">
    				</div>
                    <br>
                    <hr class="style13">
    			</div>
    		</div>
    	</section>
    
    </body>

</html>
