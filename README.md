# BRL-CAD
The about page for BRL-CAD for the google code-in, and getting familiar with GitHub
//import html & css stuff


</style>
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>BRL-CAD: About</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
    <style>
  /**Basic Styling**/
*{
    margin:0px;
    padding: 0px;
    list-style: none;
}
h2 {
  color: #d0245e;
}

.words {
  margin: 10px;
  padding: 10px;
}
body{
    color: #2c3e50;
    font-family: Segoe UI, Open Sans, Roboto, sans-serif, Arial;
    font-size: 20px;
    font-weight: normal;
}
a{
    text-decoration: none;
    color: #2c3e50;
}
a:hover{
    color:#d0245e;
    transition: ease-in .2s color;
    -webkit-transition: ease-in .2s color;
    -moz-transition: ease-in .2s color;
    -o-transition: ease-in .2s color;
    -ms-transition: ease-in .2s color;
}
/**Text Selection**/
 ::selection {
    background-color: #f1f1f1;
    color: #000;
 }
::-moz-selection {
   background-color: #352e7e;
   color: #fff;
}
::-o-selection {
   background-color: #352e7e;
   color: #fff;
}
::-ms-selection {
   background-color: #352e7e;
   color: #fff;
}
::-webkit-selection {
   background-color: #352e7e;
   color: #fff;
}
/**Scroll Bar**/
::-webkit-scrollbar {
    width: 10px;
}
::-webkit-scrollbar-track {
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3); 
}
::-webkit-scrollbar-thumb {
    background: #a1a1a1; 
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.5); 
}
::-webkit-scrollbar-thumb:window-inactive {
	background: #a1a1a1; 
}
/**Navbar**/
.header{
    height: 50pt;
    background: #fff;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    text-transform: uppercase;
    background: #000; 
}
.header table{
    border-spacing: 0px 0px;
    font-size: 24px;
    margin: 0px auto;
    
}
.logo{
    width: 80%;
    height:auto;
    margin-top: -8px;
    padding-top: 0px;
    border-radius: 50%;
    background: #000;
    z-index: 2;
}
.logomenu{
    text-align: center;
    width: 14%; /* 100 / 7 = 14 */
    /*background: #000;
/*    cursor: pointer;*/
}

.menutable{
    width: 100%;
}
.menu{
    text-align: center;
    width: 14%; /* 100 / 7 = 14 */
/*    cursor: pointer;*/
    
}
td.menu{
    
   text-align: center;
    width: 14%; /* 100 / 7 = 14 */
    padding-top: 2%;
    padding-bottom: 380px;
}

a.menu{
    color: #d0245e;
    width: 10%;
}

.menu:hover{
    color: #fff;
}


/**First**/
/**.about{
    left: 64px;
    padding: 25px;
    font-size: 23px;
    background: #2d2d2d;
    text-align: center;
    height: 300px;
}**/
#tessellactation{
    position: absolute;
    top: 50pt;
    left: 0px;
    width: 100%;
    height: 350px;
}
.main-h1{
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    font-size: 100px;
    color: #2d2d2d;  /* #2c3e50; */
    margin-top: 20px;
}
.brl{
    position: relative;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    font-size: 100px;
    color: white; /*d91a5d; */
    margin-top: 20px;

   text-shadow: 0px 0px 4px #282828,
    -1px -1px 0 #282828,
    1px -1px 0 #282828,
    -1px 1px 0 #282828,
    1px 1px 0 #282828;
}
.dash{
    position: relative;
    top: -8px;
    left: -5px;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    font-size: 100px;
    color: #888;
    margin-top: 20px;

   text-shadow: 0px 0px 4px #111,
    -1px -1px 0 #111,
    1px -1px 0 #111,
    -1px 1px 0 #111,
    1px 1px 0 #111;
}
.cad{
    position: relative;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    font-size: 100px;
    color: #fff;
    margin-top: 20px;

   text-shadow: 0px 0px 4px #111,
    -1px -1px 0 #111,
    1px -1px 0 #111,
    -1px 1px 0 #111,
    1px 1px 0 #111;
}
.byline{
    position: relative;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    font-size: 32px;
    color: #fff;
    top: -16px;

   text-shadow: 0px 0px 8px #111,
    -1px -1px 0 #111,
    1px -1px 0 #111,
    -1px 1px 0 #111,
    1px 1px 0 #111;
}
.pad{
    padding-top: 20px;
    height: 180px;
    width: 180px;
    color:#999;       
    transition: padding 0.2s linear; /* vendorless fallback */
    -o-transition: color 0.5s linear; /* opera */
    -ms-transition: color 0.5s linear; /* IE 10 */
    -moz-transition: color 0.5s linear; /* Firefox */
    -webkit-transition: padding 0.2s linear; /*safari and chrome */
}
.pad:hover{
    padding-top: 10px;
}
.main-intro{
    font-family: Segoe UI, Open Sans, Arial, sans-serif;
    font-size: 30px;
}
.wrapper-color {
  background: #000; 
  background-image: url('https://brlcad.org/img/Archer_logo.png'); 
  /*background-image: url('https://brlcad.org/gallery/_data/i/galleries/renderings/Hubble-cu_e520x360.jpg'); */
  background-repeat: no-repeat;
  background-size: 100% 100%;
  height: 300px;
  
}
.wrapper-main{
    width: 20%;
    margin: 0px auto;
    padding-top: 40px;
    padding-bottom: 15px;
    /*background: #000; */
    
}
.icon-table{
    width: 90%;
    margin: 10px auto;
    margin-top: 40px;
    border-spacing: 10px 0px;
}
.intro1{
    text-align: center;
    vertical-align: top;
    width: 33%;
}
.intro2{
    text-align: center;
    vertical-align: top;
    width: 33%;
}
.intro3{
    text-align: center;
    vertical-align: top;
    width: 33%;
}
.intro-topic{
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    font-size: 32px;
    font-weight: lighter;
}
.intro-main{
    font-weight: lighter;
    margin: 5px;
}
.what-r{
    margin: 10px auto;
    margin-top: 380px;
    background: #000;
/*     background: #f64747; */
    color: #fff;
    padding: 40px 90px 40px 90px;
    text-align: center;
    font-size: 24px;
}
.what-p{
    font-weight: lighter;
    margin: 15px;
}
.articles{
    text-align: center;
    padding: 70px 50px 70px 70px;
}
.article-table{
    border-spacing: 20px 20px;
    margin: 10px auto;
}
.article-table img{
    height: 250px;
    width: 250px;
    cursor: pointer;
    border-radius: 250px;
    -webkit-border-radius: 250px;
    -moz-border-radius: 250px;
    -o-border-radius: 250px;
    -ms-border-radius: 250px;
}
.why-us{
    background: url("img/intro-background.gif");
    padding: 60px;
}
.double{
    columns: 2;
    -webkit-columns: 2;
    -moz-columns: 2;
    -o-columns: 2;
    -ms-columns: 2;
}
/**Last**/
.last{
    padding: 20px 120px 80px 120px;
    background: #fff;
    text-align: center;
}
.whole-con{
    width: 100%;
    margin: 10px auto;
    margin-top: 20px;
    border-spacing: 10px 10px;
}
.con1{
    vertical-align: top;
    width: 50%;
}
.con2{
    vertical-align: top;
    width: 50%;
}
.message{
    width: 90%;
    outline-color: #d0245e;
/*    outline-color: #f64747;*/
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -o-border-radius: 5px;
    padding: 20px;
    font-family: Open Sans, Arial, sans-serif;
    font-size: 22px;
    max-width: 90%;
    min-width: 90%;
    height: 100px;
    resize: none;
    height: 180px;
    border: none;
    border: 1px solid #999;
}
.inputs{
    border: 1px solid #999;
    width: 100%;
    outline-color: #d0245e;
/*    outline-color: #f64747; */
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -o-border-radius: 5px;
    padding: 20px;
    font-family: Open Sans, Arial, sans-serif;
    font-size: 22px;
    max-width: 90%;
    min-width: 90%;
    margin: 0px 0px 10px 0px;
}
.submits{
    border: 2px solid #d0245e;
/*#f64747; */
    width: 100%;
    background: #d0245e;
/*    background: #f64747; */
    color: #fff;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    outline-color: #d0245e;
/*    outline-color: #f64747; */
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -o-border-radius: 5px;
    padding: 15px;
    font-size: 22px;
    width: 93%;
    margin: 10px auto;
    margin-top: 0px;
}
.submits:hover{
    background: #fff;
    color: #d0245e;
/*    color: #f64747; */
    transition: ease-in-out .3s background;
    -webkit-transition: ease-in-out .3s background;
    -moz-transition: ease-in-out .3s background;
    -o-transition: ease-in-out .3s background;
    -ms-transition: ease-in-out .3s background;
}
.social{
    width: auto;
    background: #d0245e;
    color: #fff;
    text-align: center;
    padding: 10px;
}
.links{
    margin-top: 30px;
}
.links li{
    display: inline;
    margin: 10px;
}
.links li img{
    height: 50px;
    width: auto;
}
.footer{
    background: #3a3a3a;
    color: #fff;
    padding: 70px 200px 70px 200px;
    text-align: center;
}
/**Other**/
.nots-opts1{
    border: 2px solid #d0245e;
/*#f64747; */
    background: #d0245e;
/*    background: #f64747; */
    color: #fff;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    outline-color: #d0245e;
/*    outline-color: #f64747; */
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -o-border-radius: 5px;
    padding: 5px;
    font-size: 14px;
    margin: 0px 0px 20px 0px;
    cursor: pointer;
}
.nots-opts1:hover{
    background: #fff;
    color: #d0245e;
/*    color: #f64747; */
    transition: ease-in-out .3s background;
    -webkit-transition: ease-in-out .3s background;
    -moz-transition: ease-in-out .3s background;
    -o-transition: ease-in-out .3s background;
    -ms-transition: ease-in-out .3s background;
}
.nots-opts2{
    border: 2px solid #d0245e;
/* #f64747; */
    background: #f64747;
    color: #fff;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    outline-color: #d0245e;
/*    outline-color: #f64747; */
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -o-border-radius: 5px;
    padding: 5px;
    font-size: 14px;
    margin: 0px 0px 20px 0px;
    cursor: pointer;
}
.nots-opts2:hover{
    background: #fff;
    color: #d0245e;
/*    color: #f64747; */
    transition: ease-in-out .3s background;
    -webkit-transition: ease-in-out .3s background;
    -moz-transition: ease-in-out .3s background;
    -o-transition: ease-in-out .3s background;
    -ms-transition: ease-in-out .3s background;
}
.nots-opts3{
    border: 2px solid #d0245e;
/*#f64747;*/
    background: #d0245e;
/*    background: #f64747; */
    color: #fff;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    outline-color: #d0245e;
/*    outline-color: #f64747; */
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -o-border-radius: 5px;
    padding: 5px;
    font-size: 14px;
    margin: 0px 0px 20px 0px;
    cursor: pointer;
}
.nots-opts3:hover{
    background: #fff;
    color: #d0245e;
/*    color: #f64747; */
    transition: ease-in-out .3s background;
    -webkit-transition: ease-in-out .3s background;
    -moz-transition: ease-in-out .3s background;
    -o-transition: ease-in-out .3s background;
    -ms-transition: ease-in-out .3s background;
}
.nots-opts4{
    border: 2px solid #d0245e;
/* #f64747; */
    background: #d0245e;
/*    background: #f64747; */
    color: #fff;
    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
    outline-color: #d0245e;
/*    outline-color: #f64747; */
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -o-border-radius: 5px;
    padding: 5px;
    font-size: 14px;
    margin: 0px 0px 20px 0px;
    cursor: pointer;
}
.nots-opts4:hover{
    background: #fff;
    color: #d0245e;
/*    color: #f64747; */
    transition: ease-in-out .3s background;
    -webkit-transition: ease-in-out .3s background;
    -moz-transition: ease-in-out .3s background;
    -o-transition: ease-in-out .3s background;
    -ms-transition: ease-in-out .3s background;
}
            #dialogoverflow{
                display: none;
                position: fixed;
                top: 0;
                right: 0;
                width: 100%;
                z-index: 10;
                background: url("img/bg.png");
            }
            #dialogbox{
                opacity:1;
                display: none;
                position: fixed;
                background: #fff;
                color: #444;
                border: 1px solid #1a1a1a;
                box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -webkit-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -moz-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -o-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                border-radius: 3px;
                -webkit-border-radius: 3px;
                -moz-border-radius: 3px;
                -o-border-radius: 3px;
                -ms-border-radius: 3px;
                width: 750px;
                z-index: 10;
            }
            #dialogbox > div > #dialogboxhead{
                text-align: center;
                font-weight: normal;
                font-size: 25px;
                font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                padding: 10px;
                margin-bottom: 0px;
                border-bottom: 1px solid #666;
            }
            #dialogbox > div > #dialogboxbody{
                font-weight: normal;
                padding: 10px;
                margin: 0px 0px 0px 0px;
                padding: 20px 20px 20px 20px;
                font-size: 90%;
                height: 300px;
                overflow-y: scroll;
            }
            #dialogbox > div > #dialogboxfoot{
                padding: 10px;
                font-size: 90%;
                border-top: 1px solid #666;
            }
            #dialogoverflow2{
                display: none;
                position: fixed;
                top: 0;
                right: 0;
                width: 100%;
                z-index: 10;
                background: url("img/bg.png");
            }
            #dialogbox2{
                opacity:1;
                display: none;
                position: fixed;
                background: #fff;
                color: #444;
                border: 1px solid #1a1a1a;
                box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -webkit-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -moz-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -o-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                border-radius: 3px;
                -webkit-border-radius: 3px;
                -moz-border-radius: 3px;
                -o-border-radius: 3px;
                -ms-border-radius: 3px;
                width: 750px;
                z-index: 10;
            }
            #dialogbox2 > div > #dialogboxhead2{
                text-align: center;
                font-weight: normal;
                font-size: 25px;
                font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                padding: 10px;
                margin-bottom: 0px;
                border-bottom: 1px solid #666;
            }
            #dialogbox2 > div > #dialogboxbody2{
                font-weight: normal;
                padding: 10px;
                margin: 0px 0px 0px 0px;
                padding: 20px 20px 20px 20px;
                font-size: 90%;
                height: 300px;
                overflow-y: scroll;
            }
            #dialogbox2 > div > #dialogboxfoot2{
                padding: 10px;
                font-size: 90%;
                border-top: 1px solid #666;
            }
            #dialogoverflow3{
                display: none;
                position: fixed;
                top: 0;
                right: 0;
                width: 100%;
                z-index: 10;
                background: url("img/bg.png");
            }
            #dialogbox3{ 
                opacity:1;
                display: none;
                position: fixed;
                background: #fff;
                color: #444;
                border: 1px solid #1a1a1a;
                box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -webkit-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -moz-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -o-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                border-radius: 3px;
                -webkit-border-radius: 3px;
                -moz-border-radius: 3px;
                -o-border-radius: 3px;
                -ms-border-radius: 3px;
                width: 750px;
                z-index: 10;
            }
            #dialogbox3 > div > #dialogboxhead3{
                text-align: center;
                font-weight: normal;
                font-size: 25px;
                font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                padding: 10px;
                margin-bottom: 0px;
                border-bottom: 1px solid #666;
            }
            #dialogbox3 > div > #dialogboxbody3{
                font-weight: normal;
                padding: 10px;
                margin: 0px 0px 0px 0px;
                padding: 20px 20px 20px 20px;
                font-size: 90%;
                height: 300px;
                overflow-y: scroll;
            }
            #dialogbox3 > div > #dialogboxfoot3{
                padding: 10px;
                font-size: 90%;
                border-top: 1px solid #666;
            }
            #dialogoverflow4{
                display: none;
                position: fixed;
                top: 0;
                right: 0;
                width: 100%;
                z-index: 10;
                background: url("img/bg.png");
            }
            #dialogbox4{ 
                opacity:1;
                display: none;
                position: fixed;
                background: #fff;
                color: #444;
                border: 1px solid #1a1a1a;
                box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -webkit-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -moz-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -o-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                border-radius: 3px;
                -webkit-border-radius: 3px;
                -moz-border-radius: 3px;
                -o-border-radius: 3px;
                -ms-border-radius: 3px;
                width: 750px;
                z-index: 10;
            }
            #dialogbox4 > div > #dialogboxhead4{
                text-align: center;
                font-weight: normal;
                font-size: 25px;
                font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                padding: 10px;
                margin-bottom: 0px;
                border-bottom: 1px solid #666;
            }
            #dialogbox4 > div > #dialogboxbody4{
                font-weight: normal;
                padding: 10px;
                margin: 0px 0px 0px 0px;
                padding: 20px 20px 20px 20px;
                font-size: 90%;
                height: 300px;
                overflow-y: scroll;
            }
            #dialogbox4 > div > #dialogboxfoot4{
                padding: 10px;
                font-size: 90%;
                border-top: 1px solid #666;
            }
            #dialogoverflow5{
                display: none;
                position: fixed;
                top: 0;
                right: 0;
                width: 100%;
                z-index: 10;
                background: url("img/bg.png");
            }
            #dialogbox5{
                opacity:1;
                display: none;
                position: fixed;
                background: #fff;
                color: #444;
                border: 1px solid #1a1a1a;
                box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -webkit-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -moz-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                -o-box-shadow: rgba(0, 0, 0, .8) 0px 0px 20px 0px;
                border-radius: 3px;
                -webkit-border-radius: 3px;
                -moz-border-radius: 3px;
                -o-border-radius: 3px;
                -ms-border-radius: 3px;
                width: 550px;
                z-index: 10;
            }
            #dialogbox5 > div > #dialogboxhead5{
                text-align: center;
                font-weight: normal;
                font-size: 25px;
                font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                padding: 10px;
                margin-bottom: 0px;
                border-bottom: 1px solid #666;
            }
            #dialogbox5 > div > #dialogboxbody5{
                font-weight: normal;
                padding: 10px;
                margin: 0px 0px 0px 0px;
                padding: 20px 20px 20px 20px;
                font-size: 90%;
                height: 150px;
                overflow-y: scroll;
            }
            #dialogbox5 > div > #dialogboxfoot5{
                padding: 10px;
                font-size: 90%;
                border-top: 1px solid #666;
            }
           @media screen and (max-width: 700px) and (min-width: 100px){
                body{
                    font-size: 18px;
                }
                .header{
                    display: none;
                }
                .about{
                    padding: 10px;
                    background: #2d2d2d;
/*                    background: url("img/intro-background.gif"); */
                    text-align: center;
                    height: 200px;
                }
                .tessellactation-container{
                    display: none;
                }
                .main-h1{
                    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                    font-size: 40px;
                    color: #2c3e50;
                    margin-top: 20px;
                }
                .brl{
                    position: relative;
                    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                    font-size: 40px;
                    color: #d0245e;
                    margin-top: 20px;
                }
                .dash{
                    position: relative;
                    top: -8px;
                    left: -5px;
                    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                    font-size: 40px;
                    color: #888;
                    margin-top: 20px;
                }
                .cad{
                    position: relative;
                    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                    font-size: 40px;
                    color: #fff;
                    margin-top: 20px;
                }
                .byline{
                    position: relative;
                    font-family: Intro, Segoe UI, Open Sans, Arial, sans-serif;
                    font-size: 12px;
                    color: #fff;
                    top: -6px;
                }
                .main-intro{
                    font-size: 17px;
                }
                .pad{
                    width: 100px;
                    height: 100px;
                    margin-top: 0px;
                }
                .intro-topic{
                    font-size: 17px;
                }
                .intro-main{
                    font-size: 70%;
                }
                .who-r{
                    margin-top: 450px;
                    font-size: 16px;
                    padding: 20px 20px 20px 20px;
                }
                .articles{
                    display: none;
                }
                .why-us{
                    padding: 10px 10px 10px 10px;
                }
                .last{
                    display: none;
                }
                .links li img{
                    width: 30px;
                    height: auto;
                }
                .footer{
                    padding: 20px 20px 20px 20px;
                }
            }
            </style>
    
    
  </head>  
  <body>
    <div class="header" id="header">
      <table class="menutable">
        <tr>
          <td valign="top" class="menu">
            <div ><a href="https://sourceforge.net/projects/brlcad/files/" class="menu">download</a></div>
          </td>
          <td valign="top" class="menu">
            <div ><a href="https://www.facebook.com/BRL-CAD-387112738872/" class="menu">news</a></div>
          </td>
          <td valign="top" class="menu">
            <div ><a href="https://brlcad.org/" class="menu">home</a></div>
          </td>
          <td valign="top" class="logomenu">
            <a href="https://brlcad.org/">
              <img onclick="menu_home()" src="https://brlcad.org/img/logo_color.png" alt="HOME" class="logo">
            </a>
          </td>
          <td valign="top" class="menu">
            <div ><a href="/wiki/" class="menu">docs</a></div>
          </td>
          <td valign="top" class="menu">
            <div onclick="menu_support()onclick="menu_docs()""><a href="https://sourceforge.net/projects/brlcad/support" class="menu">support</a></div>
          </td>
          <td valign="top" class="menu">
            <div ><a href="/gallery/" class="menu">gallery</a></div>
            <!-- onclick="menu_gallery()" -->
          </td>
        </tr>
      </table>
    </div>
      <div class="wrapper-color">
        <div class="wrapper-main">
          <h1 class="main-h1"><span class="brl">About</span><span class="dash"></span><span class="cad"></span></h1>
         
          <!-- <h2 class="ossm">Open&nbsp;Source&nbsp;Solid&nbsp;Modeling</h2> -->
         
   </div>
</div>
    
    
        
  <br>
  <div class="words">
    
   <h2>
      About BRL-CAD
    </h2>

  <p>
      BRL-CAD is a cross platform open source solid modeling system that includes interactive geometry editing, high-performance
      ray-tracing for rendering and geometric analysis, a system performance analysis benchmark suite, and geometry libraries 
      for application developers. Everything is distributed in source code and binary form. Although BRL-CAD can be used for 
      a wide range of engineering and graphics applications, its main purpose continues to be the support of ballistic and 
      electromagnetic analyses. BRL-CAD is basically a collection of libraries, tools, and utilities that work together to 
      create, raytrace, and integrate geometry and manipulate files and data. BRL-CAD is a large system with various portions 
      under different license but is predominantly distributed as a collective work under the v2.1 LGPL. Most of our data files 
      and documentation are provided under a modified BSD license or are in the public domain. 
    </p>
      <br>

   <p>
        </p>
      <br>
    <h2>
    What does BRL-CAD stand for?
    </h2>

   <p>
    The BRL in BRL-CAD stands for Ballistic Research Laboratory, which is where the project originates. Though BRL was absorbed
    into the U.S. Army Research Laboratory in 1992, BRL-CAD has retained its original distinctive name and trademark heritage.
    </p>
      <br>
    <h2>
    Our History
    </h2>
    <p>   
     BRL-CAD was created in 1979 when the U.S. Army Ballistic Research Laboratory expressed a need for tools that could assist
      with the computer simulation and engineering analysis of combat vehicle systems and environments. When no CAD package was 
      found to be adequate for this purpose, BRL software developers - led by Mike Muuss - began assembling a suite of utilities capable of interactively displaying, editing, and interrogating geometric models. This suite became known as what you see today - BRL-CAD. Development in BRL-CAD as a package began in 1983, and its first public release was made in 1984. BRL-CAD 
      became an open-source project in December 2004.
      <br>
      The BRL-CAD source code repository is the oldest known public version-controlled codebase in the world still under active 
      developement. It dates back to 1983, resulting in more than 30 years of active development. 
    
   </p>
    </div>
    <br>
    <div class="social">
      <h1 class="main-h1" style="font-size: 35px; color: #fff;">view us on social media!</h1>
      <ul class="links">
        <li><a target="blank" href="https://www.facebook.com/pages/BRL-CAD/387112738872"><img src="https://brlcad.org/img/facebook.png" alt="ICON"></a></li>
        <li><a target="blank" href="https://twitter.com/brl_cad"><img src="https://brlcad.org/img/twitter.png" alt="ICON"></a></li>
        <li><a target="blank" href="https://plus.google.com/s/brl%20-%20cad"><img src="https://brlcad.org/img/google.png" alt="ICON"></a></li>
        <li><a target="blank" href="https://www.linkedin.com/in/brlcad"><img src="https://brlcad.org/img/linkedin.png" alt="ICON"></a></li>
        <li><a target="blank" href="https://www.youtube.com/results?search_query=brl+-+cad"><img src="https://brlcad.org/img/youtube.png" alt="ICON"></a></li>
      </ul>
      <a href="https://bestpractices.coreinfrastructure.org/projects/66"><img src="https://bestpractices.coreinfrastructure.org/projects/66/badge"></a>
    </div>
    <div class="footer">
      <h1 class="main-h1" style="font-size: 25px; color: #fff; margin-top: 0px">BRL-CAD &COPY; 2016</h1>
      <p>All trademarks referenced herein are the properties of their respective owners. This site is not sponsored, endorsed, or run by the U.S. Government.</p>
    </div>
    
  </body>
</html>
