@import url('https://fonts.googleapis.com/css2?family=Heebo:wght@300;400;500;600;700;800;900&family=Montserrat:wght@400;500;600;900&family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,900&display=swap');

/*==BASIC-SETUP==*/
body {
  font-family: 'Heebo', sans-serif;
  font-size: 16px;
  font-weight: 400;
  color: #ffffff;
  background: #2C2C2C;
}

a,
a:hover {
  text-decoration: none;
}

ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

h1,
h2,
h3,
h4,
h5,
h6,
p,
label {
  margin-bottom: 0;
}

/* scroll-bar */
.scrolltotop {
  width: 40px;
  height: 40px;
  border-radius: 100px 100px 0 0;
  background: #333333;
  text-align: center;
  padding-top: 8px;
  font-size: 20px;
  color: #ffffff;
  position: fixed;
  right: 8px;
  bottom: 10px;
  display: none;
  transition: 0.2s all ease;
  -webkit-transition: 0.2s all ease;
  -moz-transition: 0.2s all ease;
}

.scrolltotop:hover {
  color: #fff;
  background: rgba(51, 51, 51, 0.7);
}

/*==THIS IS START==*/
.main-header {
    background-color: #ededed;
    padding: 15px;
    /*position: fixed;*/
    z-index: 9999;
    width: 100%;
}

.header-area {
  /*padding: 20px 0px 20px;*/
  position: relative;
  z-index: 999;
  background-image: linear-gradient(to right, white , rgb(255, 255, 255));
}

/* .header-area::before {
  content: '';
  display: block;
  position: absolute;
  width: 100%;
  height: 100%;
  background-image: url('images/hero-bg.png');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  left: 0;
  top: 0;
  z-index: -1;
} */

.icon_ls {
    position: absolute;
    font-size: 15px;
    right: 15px;
    top: 15px;
    border-radius: 100%;
    height: 30px;
    width: 30px;
    text-align: center;
    vertical-align: middle;
    cursor: pointer;
}
.logo img {
  max-width: 170px;
}

.head-main {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #ededed;
}

.nav-area ul {
  display: flex;
  align-items: center;
}

.nav-area ul li {
  padding-left: 37px;
}

.nav-area ul li a {
  font-family: 'Rubik', sans-serif;
  font-size: 16px;
  font-weight: 400;
  color: #000;
  display: inline-block;
  text-transform: capitalize;
  transition: 0.2s;
  position: relative;
}

.nav-area ul li .active-nav {
  color: #045f9b;
}

.nav-area ul li a::after {
  content: '';
  display: block;
  position: absolute;
  width: 0%;
  height: 2px;
  background-color: #045f9b;
  left: 0;
  bottom: -8px;
  transition: 0.2s;
}

.nav-area ul li .active-nav::after {
  content: '';
  display: block;
  position: absolute;
  width: 100%;
  height: 2px;
  background-color: #045f9b;
  left: 0;
  bottom: -8px;
}

.nav-area ul li a:hover {
  color:#045f9b
;
}

.nav-area ul li:last-of-type a:hover {
    opacity: 0.8;
    color: #fff !important;
    background: #045f9b
;
}

.nav-area ul li:last-of-type a:hover::after {
  width: 0;
}

.nav-area ul li a:hover::after {
  width: 100%;
}

.nav-area ul li .download-btn {
    background:  #045f9b;
    border-radius: 50px;
    color:#fff!important;
    padding: 10px 15px;
    width:max-content;
}

.nav-area ul li .download-btn img {
  margin-right: 8px;
}

.menu-bar i {
  font-size: 28px;
  color:#ffff !important
}

.menu-bar {
  cursor: pointer;
  display: none;
}

.close-btn i {
  color: #212529 !important;
  font-size: 20px;
  cursor: pointer;
}

.top-header {
  padding-top: 20px;
}

.top-right {
  text-align: right;
}

.top-right select {
    padding: 2px 12px;
}

.hero-area {
  padding-top: 50px;
}

.hero-right {
    padding-top: 50px;
}


.hero-right h2 {
    font-size: 35px;
    font-weight: 500;
    color: #212529 !important;
    margin: 0;
    line-height: 50px;
    text-transform: capitalize;
}
.hero-right h2 span {
  color: #212529 !important
}


.hero-right p {
    font-size: 18px;
    font-weight: 300;
    color: #212529 !important;
    margin: 5px 0 18px;
    text-align: justify;
    vertical-align: middle;
}

.get-in-touch-area {
  display: flex;
  align-items: center;
}

.get-in-btn a {
  font-size: 24px;
  font-weight: 500;
  padding: 11px 45px;
  background:#045f9b;
  width:max-content;
;
  color: #fff !important;
  display: inline-block;
  text-transform: capitalize;
  transition: 0.2s;
}

.get-in-btn a:hover {
  opacity: 0.8;
}

.get-in-right {
  padding-left: 20px;
}

.get-in-right ul {
  display: flex;
  align-items: center;
}

.get-in-right ul li{
  padding-left: 20px;
}

.get-in-right ul li a:hover {
  opacity: 0.8;
}

.exe-cnt {
  background: #045f9b
;
  border-radius: 0px 100px 100px 0;
  max-width: 560px;
  padding: 0px 50px;
  display: flex;
  align-items: center;
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
}

.exe-cnt h2 {
  font-family: 'Montserrat', sans-serif;
  font-size: 96px;
  font-weight: 900;
  color: #ffffff;
  margin: 0 20px
}

.exe-cnt h3 {
  font-family: 'Rubik', sans-serif;
  font-size: 21px;
  font-weight: 500;
  color: #ffffff;
  margin: 0;
}

.hero-main {
  position: relative;
}

.hero-main{
  position: relative;
  z-index: 999;
}

.hero-main::before {
  content: '';
  display: block;
  position: absolute;
  width: 100%;
  height: 100%;
  /*background: linear-gradient(273.46deg, #2C2C2C 18.67%, rgba(217, 217, 217, 0) 95.8%);*/
  left: 0;
  top: 0;
}

/* WHAT I DO START  */

.about p {
    font-size: 18px;
    font-weight: 300;
    color: #212529 !important;
    margin: 5px 0 18px;
    text-align: justify;
}
.about{
  background-image: linear-gradient(to right, white , rgb(255, 255, 255));
  padding: 40px;

}
.what-i-do-area {
  padding: 80px 0 100px;
}

.what-i-do-left h3 {
  font-family: 'Rubik', sans-serif;
  font-size: 40px;
  font-weight: 500;
  color: #045f9b
;
  margin: 0;
}

.what-i-do-left h2 {
  font-size: 58px;
  font-weight: 800;
  color: #FFFFFF;
  margin: 20px 0 0;
}

.what-i-do-right {
  padding-top: 50px;
}

.what-i-do-right p {
  font-size: 24px;
  font-weight: 400;
  color: #FFFFFF;
  text-align: justify;
  margin: 0;
  line-height: 32px;
}

.whatido-main {
  padding-top: 50px;
}

.whatido-main-content {
  background: #fff;
  padding: 0 26px 36px;
  margin-bottom: 0px;
}

.whatido-title h4 {
  font-size: 28px;
  font-weight: 500;
  color: #000 !important;
  margin: 15px 0 15px;
  text-transform: capitalize;
}

.whatido-title p {
  font-size: 20px;
  font-weight: 400;
  color: #000 !important;
  margin: 0 0 20px;
  max-width: 330px;
}

.whatido-title a {
    font-size: 16px;
    font-weight: 700;
    color: #045f9b;
    margin: 0;
    text-transform: capitalize;
    transition: 0.2s;
    cursor: pointer;
}

.whatido-title a img {
  max-width: 15px;
  margin-right: 12px;
}

.whatido-title a:hover {
  opacity: 0.8;
}

.whatido-main-content2 .whatido-title a {
  color:#045f9b;
}

.whatido-main-content3 .whatido-title a {
  color:#045f9b;
}

.whatido-main-content4 .whatido-title a {
  color: #045f9b;
}

.whatido-main-content5 .whatido-title a {
  color:#045f9b;
}

.whatido-main-content6 .whatido-title a {
  color: #045f9b;
}

/* WHO I AM START */

.whoiam-title h3 {
    font-family: 'Rubik', sans-serif;
    font-size: 30px;
    font-weight: 500;
    color: #000!important;
    margin: 0;
}

.whoiam-title p {
    font-size: 18px;
    font-weight: 300;
    color: #000 !important;
    margin: 20px 0;
    text-align: justify;
}

p.clr{
    color:black !important;
   
}
.dec{
    border:2px solid;
    border-radius:20px;
}

.whoiam-title ul {
  display: flex;
  align-items: center;
}

/*.whoiam-title ul li {*/
/*	font-size: 24px;*/
/*	font-weight: 900;*/
/*	color: #fff;*/
/*	margin: 0;*/
/*	padding-right: 25px;*/
/*}*/
.whoiam-title ul li {
    font-size: 18px;
    font-weight: 300;
    color: #000;
    margin: 0;
    padding-right: 25px;
}
.whoiam-title ul li img {
  margin-right: 5px;
}

.personal-info {
  padding: 48px 0 0;
}

.personal-info h2 {
  font-family: 'Rubik', sans-serif;
  font-size: 36px;
  font-weight: 500;
  color: #fff !important;
  margin: 0 0 25px;
  text-transform: uppercase;
}

.name-info {
  display: flex;
  align-items: center;
  padding-bottom: 25px;
}

.name-info p {
	font-size: 28px;
	font-weight: 400;
	color: #fff !important;
	margin: 0;
}

.name-info-left p {
  display: flex;
  align-items: center;
}

.name-info-left p img {
  max-width: 21px;
  margin-right: 20px;
}

.name-info-left {
  width: 30%;
}

.name-info-right {
  width: 70%;
}

.whoiam-btn .download-btn {
  font-weight: 600;
  font-size: 16px;
  font-family: 'Rubik', sans-serif;
  background: #045f9b
;
  border-radius: 50px;
  color: #ffffff;
  padding: 18px 30px;
}

.whoiam-btn .download-btn img {
  margin-right: 8px;
}

.whoiam-btn {
  padding-top: 30px;
}

.client-area {
  padding: 130px 0;
}

.client-title h3 {
  font-family: 'Rubik', sans-serif;
  font-size: 48px;
  font-weight: 800;
  color: #ffff;
  margin: 0;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke-width: 3px;
}

.client-title h4 {
  font-family: 'Rubik', sans-serif;
  font-size: 24px;
  font-weight:500;
  color: #ffffff;
  margin: 0;
}

/* BUSINESS AREA START */

.business-area {
  padding: 0 0 130px;
  background-image: linear-gradient(to right, white , rgb(255, 255, 255));
  padding: 50px;
}

.business-title h3 {
    font-family: 'Rubik', sans-serif;
    font-size: 40px;
    font-weight: 500;
    color: #045f9b
;
    margin: 0;
}

.business-title h2 {
  max-width: 650px;
  font-size: 46px;
  font-weight: 800;
  color: #212529 ;
  margin: 20px 0 30px;
  line-height: 49px;
}

.business-img-area {
  padding: 0 0 25px;
}

.business-content {
  margin-bottom: 30px;
  padding-left: 30px;
}

.business-btn a {
  font-family: 'Rubik', sans-serif;
  font-size: 22px;
  font-weight: 500;
  color: #3172AF;
  display: inline-block;
  padding: 9px 25px;
  background: #212529;
  border-radius: 6px;
  transition: 0.2s;
}

.business-btn a:hover {
  opacity: 0.8;
}

.business-cnt-inner h2 {
  font-family: 'Rubik', sans-serif;
  font-size: 40px;
  font-weight: 600;
  color: #212529;
  max-width: 350px;
  margin: 25px 0;
}

.business-cnt-inner p {
  font-size: 20px;
  font-weight: 400;
  color: #212529;
  max-width: 350px;
}

.business-content2 .business-btn a{
  background:#045f9b
;
  color: #212529;
}

.business-content2 .business-cnt-inner h2 {
  color:#045f9b
;
}
.who-i-am-area about{
    background:#2C2C2C !important;
}

/* PORTFOLIO AREA START  */


.portfolio-title-left h3 {
  font-family: 'Rubik', sans-serif;
  font-size: 40px;
  font-weight: 500;
  color: #3172AF;
  margin: 0 0 25px;
  padding: 40px;
}

.portfolio-title-left h2 {
  font-size: 53px;
  font-weight: 800;
  color: #ffff;
  margin: 0;
  max-width: 600px;
}

.portfolio-title-right {
  padding-top: 80px;
}

.portfolio-title-right p {
  font-size: 25px;
  font-weight: 400;
  color: #ffff;
  margin: 0;
  max-width: 525px;
}

.portfolio-nav {
  padding: 50px 0 20px;
}

.portfolio-nav ul {
  display: flex;
  align-items: center;
  justify-content: center;
}

.portfolio-nav ul li {
  padding-left: 60px;
}

.portfolio-nav ul li a {
  font-family: 'Rubik', sans-serif;
  font-size: 24px;
  font-weight: 600;
  color: #ffff;
  transition: 0.2s;
}

.portfolio-nav ul li a:hover {
  color: #3172AF;
}

.portfolio-nav ul li:first-of-type a {
  color: #3172AF;
}

/* CONTACT-AREA START  */

.contact-area {
    padding: 140px 0;
    background: #fdfbfe;
}

.contact-title h3 {
  font-family: 'Rubik', sans-serif;
  font-size: 40px;
  font-weight: 500;
  color: #045f9b;
  margin: 0;
  text-transform: capitalize;
}

.contact-title h2 {
  max-width: 590px;
  font-size: 53px;
  font-weight: 800;
  color: #000;
  margin: 20px 0;
}

.contact-title p {
  font-size: 25px;
  font-weight: 400;
  color: #000;
  margin: 0 0 35px;
  max-width: 590px;
}

.name-input {
  padding-bottom: 35px;
}

.name-input input,
.name-input textarea
 {
  width: 100%;
  font-size: 25px;
  font-weight: 500;
  color: #212428;
  padding: 25px 33px 15px;
  background: #FFFFFF;
  border-radius: 14px;
  border: 0;
  outline: 0;
}

.name-input input::placeholder,
.name-input textarea::placeholder
 {
  opacity: 1;
}

/*.send-btn a {*/
/*  font-family: 'Rubik', sans-serif;*/
/*  font-size: 32px;*/
/*  font-weight: 500;*/
/*  color: #ffffff;*/
/*  background: #3172AF;*/
/*  border-radius: 300px;*/
/*  padding: 22px 40px;*/
/*  display: inline-block;*/
/*  transition: 0.2s;*/
/*  text-transform: capitalize;*/
/*}*/
.send-btn a {
    font-size: 16px;
    font-weight: 400;
    padding: 10px 20px;
    background: #045f9b;
    color: #fff !important;
    display: inline-block;
    border-radius: 5px;
    text-transform: uppercase;
    cursor: pointer;
    transition: 0.2s;
}

.send-btn a:hover {
  opacity: 0.8;
}

.contact-details h4 {
  font-family: 'Rubik', sans-serif;
  font-size: 36px;
  font-weight: 600;
  color: #ffffff;
  margin: 0;
}

.contact-details p {
  font-family: 'Rubik', sans-serif;
  font-size: 28px;
  font-weight: 400;
  color: #ffffff;
}

.contact-main-content {
  display: flex;
  align-items: flex-start;
  padding-bottom: 25px;
}

.contact-details {
  padding-left: 20px;
}

.contact-right-img img {
  max-width: 80px;
}

.footer-left p {
  font-family: 'Rubik', sans-serif;
  font-size: 24px;
  font-weight: 600;
  color: #fff;
  margin: 0;
  
}

.footer-left p span {
  color:#fff
;
}

.footer-area {
  padding-top: 50px;
  padding-bottom: 70px;
  /*background-image: linear-gradient(to right, white , rgb(255, 255, 255));*/
  background:#2c2c2c;
}

.footer-right ul {
  display: flex;
  align-items: center;
}

.footer-right ul li {
  padding-left: 30px;
}

.footer-right ul li a {
  font-family: 'Rubik', sans-serif;
  font-size: 24px;
  font-weight: 600;
  color: #fff;
;
  transition: 0.2s;
}

.footer-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.footer-right ul li a:hover {
  opacity: 0.8;
}

.offcanvas {
  background-color: #2C2C2C;
  border-right: 2px solid #3C94E7;
}

.offcanvas-body .nav-area {
  display: block;
}

.offcanvas-body .nav-area ul {
  display: block;
}

.offcanvas-body .nav-area ul li {
  padding: 0 0 25px;
}
.header-area section.top-bar {
    background: white;
    /*padding: 10px 0px 0;*/
}

.tabcontent.intro_ls {
    display: none !important;
}


.tabcontent {
    display: none;
    padding: 6px 12px;
    border: none !important;
    border-top: none;
}
.tabcontent {
    display: none;
    padding: 2px !important;
    border: 1px solid #ccc;
    border-top: none;
}

.name-input input, .name-input textarea, .name-select select {
    width: 100%;
    font-size: 18px;
    font-weight: 400;
    color: #757575;
    padding: 15px 20px ;
    background: #FFFFFF;
    border-radius: 14px;
    border: 1px solid #929292;
    outline: 0;
}

.jdropdown-header {
    width: 54% !important;
    appearance: none;
    background-repeat: no-repeat;
    background-position: top 50% right 5px;
    background-image: url("data:image/svg+xml,%0A%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'%3E%3Cpath fill='none' d='M0 0h24v24H0V0z'/%3E%3Cpath d='M7 10l5 5 5-5H7z' fill='gray'/%3E%3C/svg%3E");
    text-overflow: ellipsis;
    cursor: pointer;
    box-sizing: border-box;
    -webkit-appearance: none;
    -moz-appearance: none;
    padding-right: 30px !important;
}

.btn-secondary {
    color: #000 !important;
    background:#fff !important;
}

.dropdown-menu {
    position: absolute !important;
    z-index: 1000;
    left: 5px !important;
    display: none;
     min-width: 0rem !important; 
    padding: -0.5rem 0;
    margin: 0;
    font-size: 1rem;
    color: #212529;
    text-align: left;
    list-style: none;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid rgba(0, 0, 0, 0.15);
    border-radius: 0.25rem;
}

.btn-check:focus + .btn-secondary, .btn-secondary:focus {
    color: #000 !important;
    background-color: #fff !important;
    border-color: #00000 !important;
    box-shadow: none !important;
}
.get-in-btn a {
    font-size: 16px;
    font-weight: 400;
    padding: 10px 20px;
    background: #045f9b;
    color: #fff !important;
    display: inline-block;
    border-radius: 5px;
    text-transform: uppercase;
    cursor: pointer;
    transition: 0.2s;
}

.whatido-img span i {
    font-size: 48px !important;
}
.whatido-img {
    text-align: center;
    padding-top: 25px;
}
.whatido-img span{
    background:#045f9b;
    height:100px;
    width:100px;
    border-radius:100%;
    display:block;
    padding: 25px 20px;
}
/*.whatido-main-content:hover{*/
/*  background:red;*/
/*  transition: 0.3s;*/
/*}*/
section.logo-slider {
    padding: 50px 0px;
    background: #045f9b !important;
}

.banner-text {
    position: absolute;
    top: 16%;
    left: 5%;
    color: #fff !important;
    z-index: 999;
    font-weight: 700;
    font-size: 62px;
    vertical-align: middle !important;
}
img.d-block.w-100 {
    opacity: 0.5;
}
.carousel-item.active {
    display: block;
    background-color: #000000e8 !important;
    background-blend-mode: overlay !important;
     display: table-cell;
}
.carosel-section{
   height:600px;
  padding-top:82px;
   display: block;
  
}

.button-pos {
    position: absolute;
    top: 40%;
    left: 5%;
    color: #fff !important;
    z-index: 999;
    font-weight: 700;
    font-size: 62px;
}


@media only screen and (max-width: 767px) {
  .button-pos {
    position: absolute;
    top: 55%;
    left: 5%;
    color: #fff !important;
    z-index: 999;
    font-weight: 700;
    font-size: 62px;
}
section.main_header_dp {
    background-image: url("images/slider1.webp");
    background-size: cover !important;
    height: 400px !important;
    background-color: #00000069 !important;
    background-blend-mode: darken;
    display: flex;
    align-items: flex-start;
    padding-left: 2rem !important;
    flex-direction: column;
    justify-content: center;
}
.heading_dp {
    color: #fff !important;
    font-weight: 500;
    font-size: 52px !important;
    line-height: 1;
    text-align:justify;
}
.get-in-btn a {
    font-size: 19px;
    padding: 9px 19px;
    margin-bottom: 10px;
}
.falg {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-content: center;
    align-items: center;
    column-gap: 25px;
    padding-left:20px;
}
.box {
    /* border: 1px solid #f2f2f2; */
    /* box-shadow: inset 0px 0px 1px 1px #bababa; */
    /*padding-bottom: 20px !important;*/
}
/*.boxx {*/
/*   padding: 4px !important;*/
/*}*/
.carosel-section {
    height: 245px;
      padding-top:50px !important;
}
.menu-bar i {
    font-size: 28px;
    color: #000 !important;
}
.offcanvas-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: #fff;
    padding: 1rem 1rem;
}
.offcanvas-body {
    flex-grow: 1;
    padding: 1rem 1rem;
    overflow-y: auto;
    background: #fff;
}
.fab {
    width: calc(100% / 2) !important;
    animation: fade-in 0.5s 
          cubic-bezier(0.455, 0.03, 0.515, 0.955) forwards;
}
.banner-text {
    position: absolute;
    top: 25%;
    left: 5%;
    color: #fff !important;
    z-index: 999;
    font-weight: 700;
    font-size: 40px;
}
.about {
    background-image: linear-gradient(to right, white , rgb(255, 255, 255));
    padding: 0px;
}
.hero-right h2 {
    font-size: 34px !important;
    line-height: 51px;
}
.box span{
    display:none;
}
.boxx span{
    display:none;
}
}
.falg {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-content: center;
    align-items: center;
    column-gap: 25px;
}
.box {
    /*border: 1px solid #f2f2f2;*/
    /*box-shadow: inset 0px 0px 1px 1px #bababa;*/
    /*padding: 3px;*/
}
.box img {
    width: 45px;
    height:auto;
}
.boxx {
    /* border: 1px solid #f2f2f2; */
    /*box-shadow: 0px 0px 6px 3px #dcdcdc;*/
    padding: 0px !important;
}
.boxx img{
    width:45px;
    height:auto;
    
}

.submit-buuton {
    font-size: 16px;
    font-weight: 400;
    padding: 10px 20px;
    background: #045f9b;
    color: #fff !important;
    display: inline-block;
    border-radius: 5px;
    text-transform: uppercase;
    cursor: pointer;
    transition: 0.2s;
    border:none !important;
}
span#more_dp {
    display: none;
}
.ecom_dp {
    display: flex;
    flex-direction: row-reverse;
}
section.main_header_dp {
    background-image: url("images/slider1.webp");
    background-size: cover !important;
    height: 600px;
    background-color: #00000069 !important;
    background-blend-mode: darken;
    display: flex;
    align-items: flex-start;
    padding-left: 4rem;
    flex-direction: column;
    justify-content: center;
}
.heading_dp {
    color: #fff !important;
    font-weight: 700;
    font-size: 62px;
}
.button_dp {
    color: #fff !important;
    z-index: 999;
    font-weight: 700;
    font-size: 62px;
}
.sec_one_dp h5, #more_dp h5, #more h5 , #about H5 {
    color: #000;
    font-size: 26px;
}
ul.list_check_dp {
    list-style: none;
    flex-direction: column;
    align-items: flex-start;
}
ul.list_check_dp li {
    font-size: 18px;
    padding-bottom: 16px;
    font-weight: 300;
    color: #212529 !important;
}
ul.list_check_dp li i {
    padding-right: 6px;
}
section.who_am_dp {
    background: #fff0f0;
    padding: 0rem 0px;
}
section.who_am_dp .about {
    background:#fff0f0;
}
img.built_software_dp {
    width: 50px;
    height: 50px;
}
