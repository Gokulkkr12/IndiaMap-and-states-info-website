This project named Mapwebsite includes 34 files along with one you are reading now i.e README.txt
   30 HTML files
   1 CSS file 
   2 IMAGES
   1 TEXT file
  _____________
  34 files

First you need to open the "main.html" since it was the homepage to the website
This website was written fully with html5 and css

Code Explanation:

1)Main.html

<DOCTYPE html>
<head>
<title> Indian states </title>
<meta charset="utf-8">
<link href="https://fonts.googleapis.com/css?family=Ubuntu|Jua|Shadows+Into+Light|Pacifico|Josefin+Sans" rel="stylesheet">

//I imported some of best fonts from googlefonts webpage and its link is placed above

<link rel="stylesheet" href="style.css">

//I used external css file here and its link is defined as above

</head>
<body>

// Body tag contains 3 containers which i used 1)HEADER 2)DIV and 3)FOOTER
//header tag is used to represent the top most container in the webpage
//In head tag I used h1,p,div,marquee and kbd tags to represent the data

<header>
<h1> India Map and states  </img></h1>
<p>Explore India!! <img src="images.jpeg" height="50" width="60"> </p>
<center>
<div class="classic">
<a href="#">Maps</a> | <a href="#">States </a> | <a href="#">links</a>
</div>
</center>
</header>
<br>
<marquee><kbd> click on the STATES to explore!! </kbd></marquee>

//imageThings div is all about image mappings
//I reffered www.image-map.com to get coordinates of the image with pixels
//coords are coordinates attributes
//Here i used shape rectangle so it contains four elements left and right coordinates up and down coordinates, i.e coords = "p,q,r,s"
//I used area tag to mention the particular area in the map with shape rectangle and given its href for link to another page as a target

<div id="imageThingss">
<center>
<img id="Image-Maps-Com-image-maps-2018-07-04-112136" src="indian.png" border="0" width="774" height="766" orgWidth="774" orgHeight="766" usemap="#image-maps-2018-07-04-112136" alt="" />
<map name="image-maps-2018-07-04-112136" id="ImageMapsCom-image-maps-2018-07-04-112136">
<area id="jammu" alt="" title="" href="jammu.html" shape="rect" coords="215,18,302,64" style="outline:none;" target="_self"     />
<area id="himachal" alt="" title="" href="himachal.html" shape="rect" coords="233,81,320,116" style="outline:none;" target="_self"     />
<area id="punjab" alt="" title="" href="punjab.html" shape="rect" coords="175,121,262,148" style="outline:none;" target="_self"     />
<area id="harayana" alt="" title="" href="harayana.html" shape="rect" coords="207,154,294,181" style="outline:none;" target="_self"     />
<area id="uttarakhand" alt="" title="" href="uk.html" shape="rect" coords="288,136,375,163" style="outline:none;" target="_self"     />
<area id="uttarpradesh" alt="" title="" href="up.html" shape="rect" coords="315,238,402,265" style="outline:none;" target="_self"     />
<area id="bihar" alt="" title="" href="bihar.html" shape="rect" coords="439,262,526,289" style="outline:none;" target="_self"     />
<area id="sikkim" alt="" title="" href="sikkim.html" shape="rect" coords="515,186,602,213" style="outline:none;" target="_self"     />
<area id="arunachal" alt="" title="" href="ap1.html" shape="rect" coords="628,163,715,229" style="outline:none;" target="_self"     />
<area id="assam" alt="" title="" href="assam.html" shape="rect" coords="588,238,675,260" style="outline:none;" target="_self"     />
<area id="meghalaya" alt="" title="" href="meghalaya.html" shape="rect" coords="562,267,649,293" style="outline:none;" target="_self"     />
<area id="nagaland" alt="" title="" href="nagaland.html" shape="rect" coords="682,248,737,272" style="outline:none;" target="_self"     />
<area id="manipur" alt="" title="" href="manipuri.html" shape="rect" coords="666,284,721,308" style="outline:none;" target="_self"     />
<area id="mizoram" alt="" title="" href="mizoram.html" shape="rect" coords="643,320,698,344" style="outline:none;" target="_self"     />
<area id="tripura" alt="" title="" href="tripura.html" shape="rect" coords="578,314,633,338" style="outline:none;" target="_self"     />
<area id="Westbengal" alt="" title="" href="wb.html" shape="rect" coords="504,337,559,361" style="outline:none;" target="_self"     />
<area id="jaharkand" alt="" title="" href="jharkand.html" shape="rect" coords="436,317,491,341" style="outline:none;" target="_self"     />
<area id="oddisha" alt="" title="" href="oddisa.html" shape="rect" coords="425,395,488,432" style="outline:none;" target="_self"     />
<area id="chattisgarh" alt="" title="" href="ch.html" shape="rect" coords="357,359,420,396" style="outline:none;" target="_self"     />
<area id="madhya" alt="" title="" href="mp.html" shape="rect" coords="233,332,344,365" style="outline:none;" target="_self"     />
<area id="rajisthan" alt="" title="" href="rajisthan.html" shape="rect" coords="133,228,244,261" style="outline:none;" target="_self"     />
<area id="gujarath" alt="" title="" href="gujarat.html" shape="rect" coords="66,322,177,355" style="outline:none;" target="_self"     />
<area id="mumbai" alt="" title="" href="maharastra.html" shape="rect" coords="161,432,272,465" style="outline:none;" target="_self"     />
<area id="andhra" alt="" title="" href="ap.html" shape="rect" coords="269,493,380,526" style="outline:none;" target="_self"     />
<area id="karnataka" alt="" title="" href="karnataka.html" shape="rect" coords="166,592,277,625" style="outline:none;" target="_self"     />
<area id="goa" alt="" title="" href="goa.html" shape="rect" coords="81,530,192,563" style="outline:none;" target="_self"     />
<area id="TN" alt="" title="" href="tn.html" shape="rect" coords="238,655,349,688" style="outline:none;" target="_self"     />
<area id="kerala" alt="" title="" href="kerala.html" shape="rect" coords="137,683,248,716" style="outline:none;" target="_self"     />
</map>

</center>
</div>
<br>

// footer defines my last container 

<footer>
<p> designed by asmjerTeam </p>
</footer>
</body>
</html>


2)CSS FILE
I used basic css
hover effects are used 

3) All other html files 

same as main.html
but it contains middle container content for state description

profile links:
gitHub:

