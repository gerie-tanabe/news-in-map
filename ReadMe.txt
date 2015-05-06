Adding to website

1.	Copy Folder to the website folder
2.	Add iframe to the page where you want to call the map
3.	Specify the source html for the iframe which is newsinmap.html


To edit/update

1. Open newsinmap.html
2. Starting line number 12 edit the following varibles.

var center = new OpenLayers.LonLat(124.4811 ,6.9716);		//WGS84 Coordinates of the news
var zoom=16;                                        //specify the zoom level 0-19
var articleURL = "https://ph.news.yahoo.com/";      //URL of the news article
var newsTitle ="SAF 44";	         	//Title of the news article 
var msg ="Click here to view article";	   //Caption for the link	