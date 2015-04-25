---
title       : Gold Stock Prices Project
subtitle    : Shiny App Presentation
author      : Eduardo Magalhaes Barbosa
job         : Coursera Developing Data Products Projects
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
license     : by-nc-sa
github      :
  user      : EduardoMagalhaes
  repo      : SlidifyPresentation
---

## Gold and Stock Price App

* This Shiny App will estimate the Stock Option price for a given Gold Mining Company.

* There will be two inputs: A date range and a A given Gold Price cost

### How it works?

* The app gathers data from internet sources for historic gold prices and stock closing values;

* For the date range supplyed, it will fitt the Stock prices in function of Gold Prices;

* There will be a chart for the fitting plot;

* Using the given Gold Target Price, the app will use the linear regression and estimate the Stock-Price;

* An Chart with historic Gold and Stock prices are showed for the selected date-range.



---

## Top 3 Historic Gold Stock Prices

Here you can see the Stock Closing Price and Volume for three of top world Gold producers:

<!-- MotionChart generated in R 3.1.2 by googleVis 0.5.8 package -->
<!-- Fri Apr 24 21:10:08 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataMotionChartID22944b7a51f2 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "ABX",
new Date(1986,11,1),
556000,
1.73 
],
[
 "ABX",
new Date(1987,11,1),
577200,
5.5 
],
[
 "ABX",
new Date(1988,11,1),
126000,
4.31 
],
[
 "ABX",
new Date(1989,11,1),
512400,
8 
],
[
 "ABX",
new Date(1992,11,1),
835600,
14.06 
],
[
 "ABX",
new Date(1993,11,1),
1392100,
27.25 
],
[
 "ABX",
new Date(1994,11,1),
970900,
21.12 
],
[
 "ABX",
new Date(1995,11,1),
389700,
26.12 
],
[
 "ABX",
new Date(1997,11,1),
1827400,
16.31 
],
[
 "ABX",
new Date(1998,11,1),
2036400,
19.94 
],
[
 "ABX",
new Date(1999,11,1),
788200,
17.81 
],
[
 "ABX",
new Date(2000,11,1),
2322400,
15.31 
],
[
 "ABX",
new Date(2003,11,1),
3635400,
22.49 
],
[
 "ABX",
new Date(2004,11,1),
3001300,
24.9 
],
[
 "ABX",
new Date(2005,11,1),
4291400,
27.08 
],
[
 "ABX",
new Date(2006,11,1),
3714700,
31.2 
],
[
 "ABX",
new Date(2008,11,1),
13592234,
26.31 
],
[
 "ABX",
new Date(2009,11,1),
24234915,
46.07 
],
[
 "ABX",
new Date(2010,11,1),
7356048,
52.44 
],
[
 "ABX",
new Date(2011,11,1),
5495280,
52.81 
],
[
 "ABX",
new Date(2014,11,1),
29024168,
12.41 
],
[
 "AUY",
new Date(2004,11,1),
614500,
2.96 
],
[
 "AUY",
new Date(2005,11,1),
1286800,
5.11 
],
[
 "AUY",
new Date(2006,11,1),
5884500,
12.85 
],
[
 "AUY",
new Date(2008,11,1),
17672911,
4.87 
],
[
 "AUY",
new Date(2009,11,1),
18158157,
13.86 
],
[
 "AUY",
new Date(2010,11,1),
11225655,
11.93 
],
[
 "AUY",
new Date(2011,11,1),
5117483,
16.81 
],
[
 "AUY",
new Date(2014,11,1),
12331535,
4.06 
],
[
 "KGC",
new Date(1981,11,1),
null,
2.06 
],
[
 "KGC",
new Date(1982,11,1),
null,
3 
],
[
 "KGC",
new Date(1983,11,1),
null,
5.25 
],
[
 "KGC",
new Date(1986,11,1),
null,
6.75 
],
[
 "KGC",
new Date(1987,11,1),
null,
7.12 
],
[
 "KGC",
new Date(1988,11,1),
null,
4.12 
],
[
 "KGC",
new Date(1989,11,1),
null,
8.06 
],
[
 "KGC",
new Date(1992,11,1),
null,
3.56 
],
[
 "KGC",
new Date(1993,11,1),
null,
6.38 
],
[
 "KGC",
new Date(1994,11,1),
null,
13.78 
],
[
 "KGC",
new Date(1995,11,1),
null,
24 
],
[
 "KGC",
new Date(1997,11,1),
null,
8.81 
],
[
 "KGC",
new Date(1998,11,1),
60800,
7.5 
],
[
 "KGC",
new Date(1999,11,1),
48900,
6 
],
[
 "KGC",
new Date(2000,11,1),
17500,
1.88 
],
[
 "KGC",
new Date(2003,11,1),
2818900,
9.22 
],
[
 "KGC",
new Date(2004,11,1),
1280800,
7.83 
],
[
 "KGC",
new Date(2005,11,1),
2002600,
7.8 
],
[
 "KGC",
new Date(2006,11,1),
2750100,
12.41 
],
[
 "KGC",
new Date(2008,11,1),
10282614,
13.61 
],
[
 "KGC",
new Date(2009,11,1),
15723683,
21.1 
],
[
 "KGC",
new Date(2010,11,1),
7179111,
17.81 
],
[
 "KGC",
new Date(2011,11,1),
7255498,
13.97 
],
[
 "KGC",
new Date(2014,11,1),
16474145,
3.04 
] 
];
data.addColumn('string','Quote');
data.addColumn('date','Date');
data.addColumn('number','Volume');
data.addColumn('number','Close');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMotionChartID22944b7a51f2() {
var data = gvisDataMotionChartID22944b7a51f2();
var options = {};
options["width"] =    600;
options["height"] =    400;
options["state"] = "";

    var chart = new google.visualization.MotionChart(
    document.getElementById('MotionChartID22944b7a51f2')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "motionchart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartMotionChartID22944b7a51f2);
})();
function displayChartMotionChartID22944b7a51f2() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartMotionChartID22944b7a51f2"></script>
 
<!-- divChart -->
  
<div id="MotionChartID22944b7a51f2" 
  style="width: 600; height: 400;">
</div>
Try it! Hit Play button above

---

## Gold Fun Facts

* The last Gold closing price was 1185.8 USD/oz on 2015-04-23.
* Compared to other metals, gold is much softer. One can beat 1 gram of gold to a 1 square meter sheet and light would shine through that sheet.
* Very few chemicals can attack gold, so that’s why it keeps it shine even when buried for 1000’s of years.
* A total of eighty-eight thousand tons of gold have been extracted from earth ever since. This means all the gold that has been dug up so far in history would, if melted, make a cube measuring approximately 25x25x25 meters.
* Gold is very rare compared with diamonds.
* Gold is one of the heaviest metals in the world. For example, it is 19,3 times as heavy as water. One cubic meter weights some 19.300 kilogram.

Source http://www.ecrresearch.com/fun-facts-about-gold

---

## Thank You!

You can see the Shiny App here: 

https://eduardomagalhaes.shinyapps.io/GoldStockPrices/

Disclaimer

* I would like to remind you that the data contained in this website is not necessarily real-time nor accurate. All figures (stocks, indexes, futures) and Gold prices are not provided by exchanges but rather by market makers, and so prices may not be accurate and may differ from the actual market price, meaning prices are indicative and not appropriate for trading purposes. Therefore I doesn`t bear any responsibility for any trading losses you might incur as a result of using this data .

