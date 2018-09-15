<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<link rel="stylesheet" type="text/css" href="style.css" />
<title>Advance web Development</title>

<script src="https://ajax.aspnetcdn.com/ajax/jQuery/jquery-3.3.1.min.js">
</script>
</head>

<body>

<div id="Ebooks">
<p>Sample Data:</p>

</div>





<div id="container">
		<div id="header">
        	<h1>Advance<span class="off">Web Development</span></h1>
            <h2>by Abayomi Osota</h2>
        </div>   
        
        <div id="menu">
        	<ul>
            	<li class="menuitem"><a href="#">Home</a></li>
                
            </ul>
        </div>
        
        <div id="leftmenu">

        <div id="leftmenu_top"></div>

				<div id="leftmenu_main">    
                
                <h3>Links</h3>
                        
                <ul>
		    <li><a href="http://it4203.azurewebsites.net/">IT 4203 Fall 2017 - Jack G. Zheng</a></li>
                    <li><a href="kennesaw.io/M1.html">Mile Stone 1</a></li>
                    <li><a href="place link here">Mile Stone 2</a></li>
                    <li><a href="place link here">Mile Stone 3</a></li>
                    <li><a href="place link here">Mile Stone 4</a></li>
                 
                </ul>
</div>
                
                
              <div id="leftmenu_bottom"></div>
        </div>
        
        
        
        
		<div id="content">
        
        
        <div id="content_top"></div>
        <div id="content_main">
        	<h2>This site will be used for all Advance Web Developments assignments </h2>
        	<p>&nbsp;</p>
           	<p>&nbsp;</p>
       	  <h3>Intro</h3>
       	  <p> Hello everyone, my name is Abayomi Osota. I am a senior at kennesaw state university. My major is in information systems. I plan to graduate by next year summer. In my free time i either watch tv or hangout with friends.</p>
        	<p>&nbsp;</p>
<h3>Purpose of page</h3>
        	<p> The purpose of this page is to post links to assignments and everything else related to IT 4203</p>
       	  <p>&nbsp;</p>
		  <h3>Course Information</h3>
       	  <p> This course covers advanced topics on web site and application development that include server side and client technologies, web services and APIs. This course has a focus on single-page web applications and web APIs, which has been the latest trends in modern web application development. Building upon your fundamental web site design and client-side development skills, this course enhance your web development skills at the client side, utilizing jQuery, JSON, and AJAX. You will complete at least one major project upon finishing this course. The objectives of this course are the explanation of  modern web application architecture, Demonstratration use of advanced applications of JavaScript and JavaScript libraries, the demonstratration use of HTML 5 features including CCS3 and supporting JavaScript APIs, how to Apply and integrate AJAX techniques to create asynchronous applications, and  the integratration of data and services provided as standard web APIs and data formats.  </p>
        	<p>&nbsp;</p>
        	
<p>&nbsp;</p>
        </div>
        
   </div>
   
   <script>
//fetches information about a specific book
$.ajax({
url: "https://www.googleapis.com/books/v1/volumes/Wfan6L9RGgYC"
}).done(function(data) {
$('#Ebooks').append(JSON.stringify(data))
});


</script>
</body>
</html>
