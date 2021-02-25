<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en">
<head>
<title>oijee88 - portfolio</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<meta name="description" content="Portfolio website of oijee88, the pixel artist and animator" />
<link rel="stylesheet" type="text/css" href="viva.css" media="screen" />
<link rel="stylesheet" type="text/css" href="jquery-ui-1.7.1.custom.css"  type="text/css" media="screen" />
<link rel="stylesheet" type="text/css" href="jquery.iviewer.css" />
<script type="text/javascript" src="jquery.js" ></script>
<script type="text/javascript" src="jquery.fancybox.pack.js" ></script>
	<script type="text/javascript" src="jquery.sticky.js"></script>
        <script type="text/javascript" src="jquery.mousewheel.min.js"  ></script>
        <script type="text/javascript" src="jquery.iviewer.js" ></script>
        <script type="text/javascript">
            var $ = jQuery;
            $(document).ready(function(){
                  $("#viewer").iviewer(
                       {
                       src: "2.gif", 
                       update_on_resize: false,
                       initCallback: function ()
                       {
                           var object = this;
                           $("#in").click(function(){ object.zoom_by(1);}); 
                           $("#out").click(function(){ object.zoom_by(-1);}); 
                           $("#orig").click(function(){  object.set_zoom(100); }); 
                       },
                       onMouseMove: function(object, coords) { },
                       onStartDrag: function(object, coords) { return false; }, //this image will not be dragged
                       onDrag: function(object, coords) { }
                  });


                  var iviewer = {};
                  $("#viewer2").iviewer(
                  {
                      src: "2.gif",
                      initCallback: function()
                      {
                        iviewer = this;
                      }
                  });
          
                  $("#1").click(function()
                  {
                    iviewer.loadImage("2.gif");
                    return false;
                  });

                  $("#2").click(function()
                  {
                    iviewer.loadImage("2-1.gif");
                    return false;
                  });
          
                  $("#3").click(function()
                  {
                    iviewer.loadImage("2-2.gif");
                    return false;
                  });
                  $("#4").click(function()
                  {
                    iviewer.loadImage("2-3.gif");
                    return false;
                  });
                  $("#5").click(function()
                  {
                    iviewer.loadImage("2-4.gif");
                    return false;
                  });
                  $("#6").click(function()
                  {
                    iviewer.loadImage("2-5.gif");
                    return false;
                  });
                  $("#7").click(function()
                  {
                    iviewer.loadImage("2-6.gif");
                    return false;
                  });
                  $("#8").click(function()
                  {
                    iviewer.loadImage("2-7.gif");
                    return false;
                  });
                  $("#9").click(function()
                  {
                    iviewer.loadImage("2-8.gif");
                    return false;
                  });
                  $("#10").click(function()
                  {
                    iviewer.loadImage("2-9.gif");
                    return false;
                  });

            });
        </script>
		  <style>
		      #header {


      font-size: 20px;
      line-height: 0em;
      font-weight: bold;
      text-align: center;
      padding: 0px;
      width:100%;

    }

   #sidebar {
    margin-top: 0px;
	
    width: 240px; /* ?????? ???? */
    padding: 0px; /* ??????? ?????? ?????? */
    float: left; /* ????????? ?? ??????? ???? */
	      font-size: 0px;
      line-height: 0em;
      font-weight: bold;
      padding: 0px;

   }
   #content {
    margin-left: 243px; /* ?????? ????? */
    padding: 0px; /* ???? ?????? ?????? */
    background: #fff; /* ???? ???? ?????? ??????? */
	

   }
  </style>
    <style type="text/css">
.but1{background:url("b1.png");width: 94px; height: 30px;display: inline-block;}
.but1:hover{background:url("b1.png")0 60px;}
.but1:active{background:url("b1.png")0 30px;}
.but2{background:url("b2.png");width: 94px; height: 30px;display: inline-block;}
.but2:hover{background:url("b2.png")0 60px;}
.but2:active{background:url("b2.png")0 30px;}
</style>

</head>

<body>   
<div style="height:100vh;width:240px;overflow:hidden;" id="sidebar">   <a><div id="header">
	  <a href="https://twitter.com/oijee88" class="but1"></a><a href="mailto:oijee88@aol.com" class="but2"></a>
	  <img src="txti.png"/>
	     </div></a>

<div style="height:100vh;width:253px;overflow-y:scroll;">

<a href="#" id="1"><img src="1.png"/></a>
<a href="#" id="2"><img src="1-1.png"/></a>
<a href="#" id="3"><img src="1-2.png"/></a>
<a href="#" id="4"><img src="1-3.png"/></a>
<a href="#" id="5"><img src="1-4.png"/></a>
<a href="#" id="6"><img src="1-5.png"/></a>
<a href="#" id="7"><img src="1-6.png"/></a>
<a href="#" id="8"><img src="1-7.png"/></a>
<a href="#" id="9"><img src="1-8.png"/></a>
<a href="#" id="10"><img src="1-9.png"/></a>
<img src="txt.png"/>


 </div>
	     </div>
	        <div id="content" class="container" align="center">
            <div id="viewer2" class="viewer" style=></div>
			</div> 
</body>
</html>
