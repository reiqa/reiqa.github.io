<!DOCTYPE html>
<html><head>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
	<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
	<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
    <link rel="stylesheet" type="text/css" href="css/style.css">
    
	<title>
		Iqa
	</title>
</head>
<body style="height: 100%; overflow-x: hidden;" data-aos-easing="ease-in-out-back" data-aos-duration="2500" data-aos-delay="0">
	<div class="bg" style="background-image: linear-gradient(-60deg, rgb(196, 255, 253) 50%, rgb(255, 255, 255) 50%);"></div>
	<div class="bg bg2" style="background-image: linear-gradient(-60deg, rgb(196, 255, 253) 50%, rgb(255, 255, 255) 50%);"></div>
	<div class="bg bg3" style="background-image: linear-gradient(-60deg, rgb(196, 255, 253) 50%, rgb(255, 255, 255) 50%);"></div>
	<main class="">
		<section>
			<div class="container-fluid m-0 p-0 center">
				<div class="row h-100 w-100 m-0 p-0">
					<div class="col-sm-2 p-0 m-0">
					</div>
					<div class="col-sm-8 main-text">
                        <div style="color: rgb(0, 0, 0); font-weight: 600;" class="tanggalan text-center p-0 m-0 warna"><span id="tanggal"></span> <span id="tanggal2"></span> <span id="tanggal3"></span></div>
                        <div id="MyClockDisplay" class="clock text-center p-0 m-0 warna" onload="showTime()" style="color: rgb(0, 0, 0);"></div>
						<div class="text-center p-0 m-0 warna" style="color: rgb(0, 0, 0);">
							<h1><span onclick="bahasa()" id="first"></span> <span id="timeOf" onclick="bahasa()"></span>,
							 <span class="txt-rotate" data-period="5000" data-rotate="[ &quot;Iqa&quot;,&quot;Sayangku&quot;, &quot;My Baby&quot;, &quot;Sweetie&quot;]"><span class="wrap" style="border-right: 0.08em solid rgb(255, 255, 255);"></span></span>
							</h1>
						</div>
						<div class="container-fluid p-0 m-0">
							<div class="row text-center">
								<div class="col-sm-1"></div>
								<div class="col-sm-10">
									<form class="text-center" action="https://www.google.com/search?q=">
										<div class="searchbox">
											<input type="search" id="box" name="q" class="search" placeholder="Search..." style="border: 0.1em solid rgb(0, 0, 0); color: rgb(0, 0, 0);">
										</div>
									</form>
								</div>
								<div class="col-sm-1"></div>
							</div>
						</div>
						<div class="container">
							<div class="text-center row" style="padding-top: 15px;">
								<div class="p-0 m-0 col-sm-1 col-md-5"></div>
								<div class="col-sm-5 col-md-1 p-0 m-0" id="kanan" style="padding-right: 15px !important; border-right: 0.05em solid rgb(0, 0, 0);">
									<div id="colpick1" class="float-right" style="background-color: rgb(255, 255, 255); border: 1px solid rgb(0, 0, 0);">
									  <input type="color" id="Primary" class="float-right" value="#0099ff" onchange="changeCol(this.value,0)">
									</div>
								</div>
								<div class="col-sm-5 col-md-1 p-0 m-0" id="kiri" style="padding-left: 15px !important; border-left: 0.05em solid rgb(0, 0, 0);">
									<div id="colpick2" class="float-left" style="background-color: rgb(196, 255, 253); border: 1px solid rgb(0, 0, 0);">
										<input type="color" id="Secondary" class="float-left" value="#000000" onchange="changeCol(this.value,1)">
									</div>
								</div>
								<div class="p-0 m-0 col-sm-1 col-md-5"></div>
			    			</div>
						
			    			<div class="text-center row">
			    				<div class="p-0 m-0 col-sm-1 col-md-2"></div>
                                <div class="p-0 m-0 col-sm-1 col-md-8" id="birthday"><a href="#" onclick="AlertIt()" id="startBucin">HAPPY BIRTHDAY</a></div>
			    				<div class="p-0 m-0 col-sm-1 col-md-2"></div>
                            </div>
			    			<div class="text-center row">
			    				<div class="p-0 m-0 col-sm-1 col-md-2"></div>
			    				<div class="p-0 m-0 col-sm-1 col-md-8"><a href="#header" id="bucin1">>>Click Here<<</a></div>
			    				<div class="p-0 m-0 col-sm-1 col-md-2"></div>
			    			</div>

			    		</div>
					</div>
					<div class="col-sm-2 p-0 m-0"></div>
				</div>
			</div>
		</section>
		
		<section>
			<div class="container-fluid m-0 h-100" style="padding-left: 3rem; padding-right: 3rem;">
				<div class="item">
				    <div class="polaroid"><img src="img/Image1.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
				<div class="item">
				    <div class="polaroid"><img src="img/Image2.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
				<div class="item">
				    <div class="polaroid"><img src="img/Image3.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
				<div class="item">
				    <div class="polaroid"><img src="img/Image4.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
			</div>
		</section>
		<section>
			<div class="container-fluid m-0 h-100" style="padding-left: 3rem; padding-right: 3rem; padding-bottom: 3rem;">
				<div class="item">
				    <div class="polaroid"><img src="img/Image5.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
				<div class="item">
				    <div class="polaroid"><img src="img/Image6.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
				<div class="item">
				    <div class="polaroid"><img src="img/Image7.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
				<div class="item">
				    <div class="polaroid"><img src="img/Image8.jpeg">
				    	<div class="caption">-</div>
				    </div>
				</div>
			</div>
		</section>
		<section id="part1" style="height: 100%!important;background-color: rgba(254,199,254,0.3);overflow-x:hidden;">
			<div class="row">
				<div class="container-fluid row p-0 m-0 text-center">
					<div class="container-fluid row" id="header">
						<div class="container text-center p-5 mb-5 even" style="background-color: rgba(255, 255, 255, 0.733); border-radius: 0px 0px 20px 20px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">Happy Birthday Babyyy <i class="fas fa-heart" style="color: rgb(184, 32, 37);"></i></h1>
						</div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-right">
						<div class="container text-center p-5 mb-5 mt-5 odd col-sm-9" style="background-color: rgba(196, 255, 253, 0.733); border-radius: 0px 20px 20px 0px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">I Want To Let You Know</h1>
						</div>
						<div class="col-sm-3"></div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-left">
						<div class="col-sm-3"></div>
						<div class="col-sm-9 container text-center p-5 mb-5 mt-5 even" style="background-color: rgba(255, 255, 255, 0.733); border-radius: 20px 0px 0px 20px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">Things That Makes You Special</h1>
						</div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-right">
						<div class="container text-center p-5 mb-5 mt-5 odd col-sm-9" style="background-color: rgba(196, 255, 253, 0.733); border-radius: 0px 20px 20px 0px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">Self-Less</h1>
						</div>
						<div class="col-sm-3"></div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-left">
						<div class="col-sm-3"></div>
						<div class="col-sm-9 container text-center p-5 mb-5 mt-5 even" style="background-color: rgba(255, 255, 255, 0.733); border-radius: 20px 0px 0px 20px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">Humble</h1>
						</div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-right">
						<div class="container text-center p-5 mb-5 mt-5 odd col-sm-9" style="background-color: rgba(196, 255, 253, 0.733); border-radius: 0px 20px 20px 0px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">Good At Writing</h1>
						</div>
						<div class="col-sm-3"></div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-left">
						<div class="col-sm-3"></div>
						<div class="col-sm-9 container text-center p-5 mb-5 mt-5 even" style="background-color: rgba(255, 255, 255, 0.733); border-radius: 20px 0px 0px 20px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">A Good Reader</h1>
						</div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-right">
						<div class="container text-center p-5 mb-5 mt-5 odd col-sm-9" style="background-color: rgba(196, 255, 253, 0.733); border-radius: 0px 20px 20px 0px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">Good At Explaining Things</h1>
						</div>
						<div class="col-sm-3"></div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-left">
						<div class="col-sm-3"></div>
						<div class="col-sm-9 container text-center p-5 mb-5 mt-5 even" style="background-color: rgba(255, 255, 255, 0.733); border-radius: 20px 0px 0px 20px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">You Are Such A Beauty</h1>
						</div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-right">
						<div class="container text-center p-5 mb-5 mt-5 odd col-sm-9" style="background-color: rgba(196, 255, 253, 0.733); border-radius: 0px 20px 20px 0px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">But The Most Important Things Is..</h1>
						</div>
						<div class="col-sm-3"></div>
					</div>
					<div class="container-fluid p-0 m-0 row aos-init aos-animate" data-aos="fade-left">
						<div class="col-sm-3"></div>
						<div class="col-sm-9 container text-center p-5 mb-5 mt-5 even" style="background-color: rgba(255, 255, 255, 0.733); border-radius: 20px 0px 0px 20px;">
							<h1 class="teksnya" style="color: rgb(0, 0, 0);">You Accept Me As I Am</h1>
						</div>
					</div>
				</div>
				<div class="container-fluid row p-0 m-0 text-center">
					<div class="col-sm-1"></div>
					<div class="col-sm-10 container text-center p-5 mb-5 mt-5 odd" style="background-color: rgba(196, 255, 253, 0.733); border-radius: 20px;">
						<h1 class="teksnya" style="color: rgb(0, 0, 0);">Beside That, There Is More Other Reason Why I Love You <i class="fas fa-heart" style="color: rgb(184, 32, 37);"></i></h1>
					</div>
					<div class="col-sm-1"></div>
				</div>
			</div>
		</section>
		
		
	</main>
	<div id="splash"></div>
	<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
	<script>
	  AOS.init({
	  	duration:2500,
	  	easing: 'ease-in-out-back'});
	</script>

<script type="text/javascript">
	$(document).ready( function() {
	    $("#box").on("focus", function( e ) {
	        $('#b1').show();
	    });
	});
	var TxtRotate = function(el, toRotate, period) {
	  this.toRotate = toRotate;
	  this.el = el;
	  this.loopNum = 0;
	  this.period = parseInt(period, 10) || 2000;
	  this.txt = '';
	  this.tick();
	  this.isDeleting = false;
	};

	TxtRotate.prototype.tick = function() {
	  var i = this.loopNum % this.toRotate.length;
	  var fullTxt = this.toRotate[i];

	  if (this.isDeleting) {
	    this.txt = fullTxt.substring(0, this.txt.length - 1);
	  } else {
	    this.txt = fullTxt.substring(0, this.txt.length + 1);
	  }

	  this.el.innerHTML = '<span class="wrap">'+this.txt+'</span>';

	  var that = this;
	  var delta = 300 - Math.random() * 100;

	  if (this.isDeleting) { delta /= 2; }

	  if (!this.isDeleting && this.txt === fullTxt) {
	    delta = this.period;
	    this.isDeleting = true;
	  } else if (this.isDeleting && this.txt === '') {
	    this.isDeleting = false;
	    this.loopNum++;
	    delta = 500;
	  }

	  setTimeout(function() {
	    that.tick();
	  }, delta);
	};

	window.onload = function() {
	  var css = document.createElement("style");
	  css.type = "text/css";
	  css.innerHTML = ".txt-rotate > .wrap { border-right: 0.08em solid rgba(255,255,255,1) }";
	  document.body.appendChild(css);
	  var elements = document.getElementsByClassName('txt-rotate');
	  for (var i=0; i<elements.length; i++) {
	    var toRotate = elements[i].getAttribute('data-rotate');
	    var period = elements[i].getAttribute('data-period');
	    if (toRotate) {
	      new TxtRotate(elements[i], JSON.parse(toRotate), period);
	    }
	  }
	};
	function blink(){
	  var elements = document.getElementsByClassName('wrap');
	  for (var i=0; i<elements.length; i++){
	  	elements[i].style.borderRight = "0.08em solid rgba(255,255,255,1)";
	  }
	  if (TxtRotate.isDeleting){
	  	setTimeout(blink,700);
	  }else{
	  	setTimeout(unblink, 700);
	  }
	}
	function unblink(){
	  var elements = document.getElementsByClassName('wrap');
	  for (var i=0; i<elements.length; i++){
	  	elements[i].style.borderRight = "0.08em solid rgba(255,255,255,0)";
	  }
	  setTimeout(blink, 700);
	}
	blink();
</script>
<script type="text/javascript">
	var check = 0;
	var first = ["Good"]
	var kataPagi = ["Morning"];
	var kataSiang = ["Afternoon"];
	var kataSore = ["Evening"]
	var kataMalam = ["Night"]
	//Indo, Inggris, Chinese(Simplified), Korean, French, Japanese, Spanish
	function getRandomInt(max){
		return Math.floor(Math.random()*Math.floor(max));
	}
	var langu = getRandomInt(first.length);

	function fade(element) {
    	var op = 1;  // initial opacity
    	var timer = setInterval(function () {
        	if (op <= 0.1){
            	clearInterval(timer);
            	element.style.display = 'none';
        	}
        	element.style.opacity = op;
        	element.style.filter = 'alpha(opacity=' + op * 100 + ")";
        	op -= op * 0.1;
    	}, 50);
	}

	function unfade(element) {
	    var op = 0.1;  // initial opacity
	    element.style.display = 'block';
	    var timer = setInterval(function () {
	        if (op >= 1){
	            clearInterval(timer);
	        }
	        element.style.opacity = op;
	        element.style.filter = 'alpha(opacity=' + op * 100 + ")";
	        op += op * 0.1;
	    }, 60);
	}

	function bahasa(){
		langu++;
		if (langu>(first.length)-1){
			langu = 0;
		}
		var date = new Date();
		var h = date.getHours();
		if(h>0 && h<11){//Morning
	    	var second = kataPagi;
	    	document.getElementById("first").innerText = first[langu];
	    	document.getElementById("timeOf").innerText = second[langu];
	    }else if(h>10 && h<16){//Afternoon
	    	var second = kataSiang;
	    	document.getElementById("first").innerText = first[langu];
	    	document.getElementById("timeOf").innerText = second[langu];
	    }else if(h>15 && h<19){//Evening
	    	var second = kataSore;
	    	document.getElementById("first").innerText = first[langu];
	    	document.getElementById("timeOf").innerText = second[langu];
	    }else{//Night
	    	var second = kataMalam;
	    	document.getElementById("first").innerText = first[langu];
	    	document.getElementById("timeOf").innerText = second[langu];
	    }
	}

	function showTime(){
        var date = new Date();
        tanggalan = date.getDate();
        var months = ["January","February","March","April","May","June","July","August","September","October","November","December"];
        tanggalan2 = months[date.getMonth()];
        tanggalan3 = date.getFullYear()
	    var h = date.getHours(); // 0 - 23
	    var m = date.getMinutes(); // 0 - 59
	    var s = date.getSeconds(); // 0 - 59
	    var oneDay = 24 * 60 * 60 * 1000; // hours*minutes*seconds*milliseconds
		var firstDate = new Date(2021, 0, 26);
        document.getElementById("tanggal").innerText = tanggalan;
        document.getElementById("tanggal2").innerText = tanggalan2;
        document.getElementById("tanggal3").innerText = tanggalan3;
        var days = (Math.abs(firstDate - date) / oneDay);
        if (days >= 0.5 && days < 1){
            document.getElementById("birthday").style.display = "block";
        }else{
            document.getElementById("birthday").style.display = "none";
        }
		var hari = days;
	    h = (h < 10) ? "0" + h : h;
	    m = (m < 10) ? "0" + m : m;
	    document.getElementById("days").innerText = hari;
	    var time = h + ":" + m;
	    document.getElementById("MyClockDisplay").innerText = time;
	    document.getElementById("MyClockDisplay").textContent = time;
	    if(h>0 && h<11){
	    	var second = kataPagi;
	    	document.getElementById("timeOf").innerText = second[langu];
	    }else if(h>10 && h<16){
	    	var second = kataSiang;
	    	document.getElementById("timeOf").innerText = second[langu];
	    }else if(h>15 && h<19){
	    	var second = kataSore;
	    	document.getElementById("timeOf").innerText = second[langu];
	    }else{
	    	var second = kataMalam;
	    	document.getElementById("timeOf").innerText = second[langu];
	    }

	    //Hourly and first time check
	    var warna = document.getElementsByClassName("warna");
	    var primary = "#000000";
	    var secondary = "#0000ff";
	    var warnanya = "red";
	    if(m == 59 && s == 58){
	    	var splash = document.getElementById("splash");
	    	unfade(splash);
	    	splash.style.display = 'block';
	    }
	    if(s == 0 && m == 0){
	    	var splash = document.getElementById("splash");
	    	fade(splash);
	    	setTimeout(function(){
	    		splash.style.display = 'none';
	    	},1000);
	    	if(h>5 && h<11){
			    primary = "#ffffff";
	    		secondary = "#fee1aa";
	    		warnanya = "#000000";
	    	}else if(h>10 && h<16){
	    		primary = "#ffffff";
	    		secondary = "#c4fffd";
	    		warnanya = "#000000";
	    	}else if(h>15 && h<19){
	    		primary = "#fee39e";
	    		secondary = "#feffac";
	    		warnanya = "#000000";
	    	}else{
	    		primary = "#959595";
	    		secondary = "#000000";
	    		warnanya = "#ffffff";
	    	}
	    	var teksnya = document.getElementsByClassName("teksnya");
	    	for(i = 0; i < teksnya.length; i++){
		    	teksnya[i].style.color = warnanya;
		    }
	    	var even = document.getElementsByClassName("even");
		    for(i = 0; i < even.length; i++){
		    	even[i].style.backgroundColor = primary+"bb";
		    }
		    var odd = document.getElementsByClassName("odd");
		    for(i = 0; i < odd.length; i++){
		    	odd[i].style.backgroundColor = secondary+"bb";
		    }
	    	var cols = document.getElementsByClassName("bg");
	    	document.getElementById("Secondary").value = secondary;
	    	document.getElementById("Primary").value = primary;
		    for(i = 0; i < cols.length; i++){
		    	cols[i].style.backgroundImage = "linear-gradient(-60deg,"+secondary+" 50%, "+primary+" 50%)";
		    }
			for(i = 0; i < warna.length; i++){
			    warna[i].style.color = warnanya;
			}
			var cols = document.getElementsByClassName("bg");
		    for(i = 0; i < cols.length; i++){
		    	cols[i].style.backgroundImage = "linear-gradient(-60deg,"+secondary+" 50%, "+primary+" 50%)";
		    }
			for(i = 0; i < warna.length; i++){
			    warna[i].style.color = warnanya;
			}
			var searchCol = document.getElementsByClassName("search");
			for(i = 0; i < searchCol.length; i++){
		    	searchCol[i].style.border = "0.1em solid "+warnanya;
		    	searchCol[i].style.color = warnanya;
		    }
		    document.getElementById("kanan").style.borderRight = "0.05em solid "+warnanya;
		    document.getElementById("kiri").style.borderLeft = "0.05em solid "+warnanya;
			document.getElementById("colpick1").style.backgroundColor = primary;
			document.getElementById("colpick1").style.border = "1px solid "+warnanya;
			document.getElementById("colpick2").style.backgroundColor = secondary;
			document.getElementById("colpick2").style.border = "1px solid "+warnanya;
	    }else if(check === 0){
	    	if(h>5 && h<11){
			    primary = "#ffffff";
	    		secondary = "#fee1aa";
	    		warnanya = "#000000";
	    	}else if(h>10 && h<16){
	    		primary = "#ffffff";
	    		secondary = "#c4fffd";
	    		warnanya = "#000000";
	    	}else if(h>15 && h<19){
	    		primary = "#fee39e";
	    		secondary = "#feffac";
	    		warnanya = "#000000";
	    	}else{
	    		primary = "#959595";
	    		secondary = "#000000";
	    		warnanya = "#ffffff";
	    	}
	    	var teksnya = document.getElementsByClassName("teksnya");
	    	for(i = 0; i < teksnya.length; i++){
		    	teksnya[i].style.color = warnanya;
		    }
	    	var even = document.getElementsByClassName("even");
		    for(i = 0; i < even.length; i++){
		    	even[i].style.backgroundColor = primary+"bb";
		    }
		    var odd = document.getElementsByClassName("odd");
		    for(i = 0; i < odd.length; i++){
		    	odd[i].style.backgroundColor = secondary+"bb";
		    }
	    	var cols = document.getElementsByClassName("bg");
	    	document.getElementById("Secondary").value = secondary;
	    	document.getElementById("Primary").value = primary;
		    for(i = 0; i < cols.length; i++){
		    	cols[i].style.backgroundImage = "linear-gradient(-60deg,"+secondary+" 50%, "+primary+" 50%)";
		    }
			for(i = 0; i < warna.length; i++){
			    warna[i].style.color = warnanya;
			}
			var searchCol = document.getElementsByClassName("search");
			for(i = 0; i < searchCol.length; i++){
		    	searchCol[i].style.border = "0.1em solid "+warnanya;
		    	searchCol[i].style.color = warnanya;
		    }
		    document.getElementById("kanan").style.borderRight = "0.05em solid "+warnanya;
		    document.getElementById("kiri").style.borderLeft = "0.05em solid "+warnanya;
			document.getElementById("colpick1").style.backgroundColor = primary;
			document.getElementById("colpick1").style.border = "1px solid "+warnanya;
			document.getElementById("colpick2").style.backgroundColor = secondary;
			document.getElementById("colpick2").style.border = "1px solid "+warnanya;
	    }
	    check = 1;
	    
	    setTimeout(showTime, 1000);
	    
	}


	function AlertIt() {
		alert('Happy Birthday Baby <3');
		alert("I'm the luckiest person in the whole world because you become mine");
		alert("I love you, and I'm glad that you know it");
        alert("I wish you always be healthy,");
        alert("You can overcome all your problem")
        alert("and I will always be here for you <3")
        alert("I wish all the best for you Baby")
        alert("Thanks for everything <3");
		document.getElementById("part1").style.display = "block";
		document.getElementById("startBucin").style.display = "none";
		document.getElementById("bucin1").style.display = "block";
		console.log("If you see this, I love you nyam :)");
	}

	function changeCol(col,stat){
		if(stat==0){
			var primary = col;
			var secondary = document.getElementById("Secondary").value;
		}else
		{
			var primary = document.getElementById("Primary").value;
	    	var secondary = col;
		}
		document.getElementById("colpick1").style.backgroundColor = primary;
		document.getElementById("colpick2").style.backgroundColor = secondary;
	    var even = document.getElementsByClassName("even");
		for(i = 0; i < even.length; i++){
		   	even[i].style.backgroundColor = primary+"bb";
		}
		var odd = document.getElementsByClassName("odd");
		for(i = 0; i < odd.length; i++){
		    odd[i].style.backgroundColor = secondary+"bb";
		}
	    var cols = document.getElementsByClassName("bg");
	    for(i = 0; i < cols.length; i++){
	    	cols[i].style.backgroundImage = "linear-gradient(-60deg,"+secondary+" 50%, "+primary+" 50%)";
	    }
	}
	bahasa();
	showTime();
</script>

<style type="text/css">.txt-rotate > .wrap { border-right: 0.08em solid rgba(255,255,255,1) }</style></body></html>