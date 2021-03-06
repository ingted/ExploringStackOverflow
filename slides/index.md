- title : Exploring StackOverflow 
- description : Exploring StackOverflow with F# and R.
- author : Evelina Gabasova
- theme : white
- transition : none

***

- data-background: images/posts-background.png
- class : withbackground

# <div style="color: white" > Exploring StackOverflow </div>
## <div style="color: white" > Evelina Gabasova </div>
## <div style="color: white" > @evelgab </div>

------------------------------------------------------------------------------------------------

<img src="images/so-logo.png" /> 

------------------------------------------------------------------------------------------------

<img src="images/cambridge-logo.jpg" /> 

------------------------------------------------------------------------------------------------

- data-background : images/cambridge2.jpg

------------------------------------------------------------------------------------------------

- data-background : images/cancer-unit.jpg

------------------------------------------------------------------------------------------------

- data-background : images/tcga-dna.jpg

------------------------------------------------------------------------------------------------

- data-background : images/bam2.png

------------------------------------------------------------------------------------------------

- data-background : images/star-wars.png

------------------------------------------------------------------------------------------------
![](images/so-logo.png)

' Why analyze StackOverflow?
' Why not? The data are there
' Can we actually learn something from it?

------------------------------------------------------------------------------------------------

- data-background: #d3d3d3

<img src="images/copypaste.jpg" style="height: 640px" />

------------------------------------------------------------------------------------------------

- data-background: #d3d3d3

![](images/api.png)

------------------------------------------------------------------------------------------------

- data-background: #d3d3d3

![](images/archive.png)

------------------------------------------------------------------------------------------------

- data-background : black

<img src="images/files.png" style="width: 960px" />

' 135 GB approx

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

<h1 style="font-size:400pt; color: white"> ? </h1>

' Questions are important - parallel from genomics

------------------------------------------------------------------------------------------------

- data-background : black

![](images/persian-cat-room-guardian.jpg)

------------------------------------------------------------------------------------------------

- data-background : black

<img src="images/dafuq.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

<h1 style="font-size:110pt; color: white"> Questions </h1>

------------------------------------------------------------------------------------------------

![](images/so-structure-full.png)

------------------------------------------------------------------------------------------------

![](images/so-structure-tags.png)

------------------------------------------------------------------------------------------------

# Tags

<div class="fragment">

- What are the most common tags?

</div>

' how to recognize technologies that people use for hobby projects
' technology: F#, xml parsing
' insights: think about your target demographics
' fun: minecraft, Krzysztof, most corporate technologies

------------------------------------------------------------------------------------------------

- data-background : images/tag-frequency.png

------------------------------------------------------------------------------------------------

# Tags

- What are the most common tags?

<div class="fragment">

- When do people ask questions?

</div>

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Question: When?

' demo
' tags-time-full.csv
' Show csv type provider, don't run it
' Remark on distributed computing!!! Don't do serious data science on a laptop, unless you're using it to connect to a server/cluster

------------------------------------------------------------------------------------------------


<script type="text/javascript" src="https://www.google.com/jsapi"></script>
<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Monday"}, {"v": 1386}]}, {"c" : [{"v": "Tuesday"}, {"v": 1542}]}, {"c" : [{"v": "Wednesday"}, {"v": 1471}]}, {"c" : [{"v": "Thursday"}, {"v": 1502}]}, {"c" : [{"v": "Friday"}, {"v": 1391}]}, {"c" : [{"v": "Saturday"}, {"v": 930}]}, {"c" : [{"v": "Sunday"}, {"v": 969}]}]});
    var options = {"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"title":"Tag: f#","width":1000,"height":600} 
    var chart = new google.visualization.BarChart(document.getElementById('d58646cc-a055-47d1-8d4f-d9a17025c2d1'));
    chart.draw(data, options);
}
</script>
<div id="d58646cc-a055-47d1-8d4f-d9a17025c2d1" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Monday"}, {"v": 147006}]}, {"c" : [{"v": "Tuesday"}, {"v": 162664}]}, {"c" : [{"v": "Wednesday"}, {"v": 166002}]}, {"c" : [{"v": "Thursday"}, {"v": 164108}]}, {"c" : [{"v": "Friday"}, {"v": 144248}]}, {"c" : [{"v": "Saturday"}, {"v": 67336}]}, {"c" : [{"v": "Sunday"}, {"v": 67208}]}]});
    var options = {"colors":["#f68024"],"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"title":"Tag: c#","width":1000,"height":600}  
    var chart = new google.visualization.BarChart(document.getElementById('734e0c3a-02aa-4fdb-b5ef-8d2d1f2da484'));
    chart.draw(data, options);
}
</script>
<div id="734e0c3a-02aa-4fdb-b5ef-8d2d1f2da484" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

- data-background : #f68024 

<img src="images/Krzysztof2.jpg" style="height: 500px; text-align:center" />
<img src="images/Krzysztof-tweet.png" style="height: 100px; text-align:center" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio0.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio1.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio2.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio3.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio4.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio5.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio6.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio7.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Weekend index

------------------------------------------------------------------------------------------------

# Most weekend

1. Minecraft : 1.19

2. LWJGL : 1.12

3. SFML (Simple and Fast Multimedia Library) : 1.06                                                                                                                    
4. D : 1.04                                                                                                                       
5. pygame : 1.03   


------------------------------------------------------------------------------------------------

# Most weekday

1. SQL Server Reporting Services 2008, r2 : 0.11

2. Infragistics : 0.13

3. SQL Server Reporting Services 2008 : 0.13 

4. Axapta : 0.13                                                                                                                 
5. DocusignAPI : 0.14     

' Axapta =  enterprise resource planning solution

------------------------------------------------------------------------------------------------

### Functional languages

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "F#"}, {"v": 0.651055951727921}]}, {"c" : [{"v": "Scala"}, {"v": 0.592436649187611}]}, {"c" : [{"v": "Clojure"}, {"v": 0.750728862973761}]}, {"c" : [{"v": "Haskell"}, {"v": 0.886785260482846}]}, {"c" : [{"v": "Erlang"}, {"v": 0.587825740998608}]}, {"c" : [{"v": "OCaml"}, {"v": 0.778732545649839}]}, {"c" : [{"v": "Elm"}, {"v": 1.0126582278481}]}]});
    var options = {"hAxis":{"title":"Weekend ratio","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"width":1000,"height":600}  
    var chart = new google.visualization.BarChart(document.getElementById('8c94b49e-d814-44db-acbd-8d057057761b'));
    chart.draw(data, options);
}
</script>
<div id="8c94b49e-d814-44db-acbd-8d057057761b" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

### Data science

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Python"}, {"v": 0.606629300657529}]}, {"c" : [{"v": "R"}, {"v": 0.49564316329895}]}, {"c" : [{"v": "Scala"}, {"v": 0.592436649187611}]}, {"c" : [{"v": "Matlab"}, {"v": 0.579115610015983}]}, {"c" : [{"v": "SAS"}, {"v": 0.294543000385654}]}, {"c" : [{"v": "Hadoop"}, {"v": 0.410816667419078}]}, {"c" : [{"v": "F#"}, {"v": 0.651055951727921}]}]});
    var options = {"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"width":1000,"height":600}  
    var chart = new google.visualization.BarChart(document.getElementById('8d5b1ad7-9c7e-47bc-b894-a6e867ad589f'));
    chart.draw(data, options);
}
</script>
<div id="8d5b1ad7-9c7e-47bc-b894-a6e867ad589f" style="width: 800px; height: 600px;"></div>


------------------------------------------------------------------------------------------------

### Continuous integration 

![](images/travis-vs-jenkins.png)

------------------------------------------------------------------------------------------------

### Continuous integration 

<div class="fragment">

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Travis-CI"}, {"v": 0.5944625407}]}, {"c" : [{"v": "Jenkins"}, {"v": 0.2083646193}]}]});
    var options = {"hAxis":{"title":"Weekend ratio","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"width":1000,"height":400}  
    var chart = new google.visualization.BarChart(document.getElementById('8c94b49e-d814-44db-acbd-8d057057761c'));
    chart.draw(data, options);
}
</script>
<div id="8c94b49e-d814-44db-acbd-8d057057761c" style="width: 800px; height: 400px;"></div>

</div>

------------------------------------------------------------------------------------------------

<img src="images/travis-ci.jpg" style="height: 200px"/> 
<img src="images/jenkins.png" style="height: 200px"/>  

<div class="fragment"> 
# Who's your target user? 
</div>

' Do you want people to use your product in their free time?  Make it easy for them
' But targeting enterprise is a valid goal as well

************************************************************************************************

- data-background: images/posts-background.png
- class : withbackground

<h1 style="font-size:200pt"> ? </h1>

------------------------------------------------------------------------------------------------

![](images/profile1.png)

------------------------------------------------------------------------------------------------

![](images/profile2.png)

------------------------------------------------------------------------------------------------

# Question: Where?

' Are there local pockets for some of the languages?
' Where is each technology used?
' technology: type providers for JSON & Bing, HTML & Wikipedia, charting
' insights: technology countries, where are programmers concentrated

------------------------------------------------------------------------------------------------

# Where?

- 5 277 833 users in total

- 769 541 filled in their location

------------------------------------------------------------------------------------------------

- data-background : black

### $HOME

------------------------------------------------------------------------------------------------

- data-background : black

# 83%

------------------------------------------------------------------------------------------------

- data-background : black

### (Unfortunately) Germany

------------------------------------------------------------------------------------------------

- data-background : black

### 7151 Mawson Station, Australian Antarctic Territory, Antarctica

------------------------------------------------------------------------------------------------

- data-background : images/antarctica.jpg

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground 

# Where?

' demo: JSON type provider + Bing map API

------------------------------------------------------------------------------------------------

### Javascript

<script type="text/javascript">
google.load("visualization", "1", {packages:["geochart"]})
google.setOnLoadCallback(drawChart);
function drawChart() {
var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "United States"}, {"v": 49103}]}, {"c" : [{"v": "Canada"}, {"v": 7213}]}, {"c" : [{"v": "United Kingdom"}, {"v": 13960}]}, {"c" : [{"v": "Turkey"}, {"v": 1550}]}, {"c" : [{"v": "Australia"}, {"v": 4874}]}, {"c" : [{"v": "India"}, {"v": 26724}]}, {"c" : [{"v": "Israel"}, {"v": 1481}]}, {"c" : [{"v": "South Africa"}, {"v": 1356}]}, {"c" : [{"v": "Denmark"}, {"v": 1471}]}, {"c" : [{"v": "Georgia"}, {"v": 253}]}, {"c" : [{"v": "Netherlands"}, {"v": 4358}]}, {"c" : [{"v": "Sweden"}, {"v": 2615}]}, {"c" : [{"v": "France"}, {"v": 4910}]}, {"c" : [{"v": "Colombia"}, {"v": 482}]}, {"c" : [{"v": "Belgium"}, {"v": 1807}]}, {"c" : [{"v": "Ireland"}, {"v": 1232}]}, {"c" : [{"v": "New Zealand"}, {"v": 1204}]}, {"c" : [{"v": "Lebanon"}, {"v": 194}]}, {"c" : [{"v": "Hungary"}, {"v": 659}]}, {"c" : [{"v": "Norway"}, {"v": 1154}]}, {"c" : [{"v": "Finland"}, {"v": 775}]}, {"c" : [{"v": "Germany"}, {"v": 7863}]}, {"c" : [{"v": "Mexico"}, {"v": 1100}]}, {"c" : [{"v": "Philippines"}, {"v": 1220}]}, {"c" : [{"v": "Poland"}, {"v": 2486}]}, {"c" : [{"v": "Argentina"}, {"v": 1115}]}, {"c" : [{"v": "Paraguay"}, {"v": 50}]}, {"c" : [{"v": "Spain"}, {"v": 2658}]}, {"c" : [{"v": "Chile"}, {"v": 398}]}, {"c" : [{"v": "Belarus"}, {"v": 555}]}, {"c" : [{"v": "Latvia"}, {"v": 315}]}, {"c" : [{"v": "Thailand"}, {"v": 326}]}, {"c" : [{"v": "Japan"}, {"v": 720}]}, {"c" : [{"v": "Austria"}, {"v": 1022}]}, {"c" : [{"v": "Lithuania"}, {"v": 365}]}, {"c" : [{"v": "Luxembourg"}, {"v": 72}]}, {"c" : [{"v": "Russia"}, {"v": 3218}]}, {"c" : [{"v": "Brazil"}, {"v": 3600}]}, {"c" : [{"v": "Iceland"}, {"v": 118}]}, {"c" : [{"v": "Singapore"}, {"v": 893}]}, {"c" : [{"v": "Oman"}, {"v": 1312}]}, {"c" : [{"v": "Croatia"}, {"v": 401}]}, {"c" : [{"v": "Kenya"}, {"v": 224}]}, {"c" : [{"v": "Switzerland"}, {"v": 1561}]}, {"c" : [{"v": "Honduras"}, {"v": 36}]}, {"c" : [{"v": "Uruguay"}, {"v": 212}]}, {"c" : [{"v": "Bolivia"}, {"v": 62}]}, {"c" : [{"v": "Bangladesh"}, {"v": 1002}]}, {"c" : [{"v": "Pakistan"}, {"v": 2056}]}, {"c" : [{"v": "Puerto Rico"}, {"v": 67}]}, {"c" : [{"v": "Italy"}, {"v": 2707}]}, {"c" : [{"v": "Estonia"}, {"v": 268}]}, {"c" : [{"v": "Greece"}, {"v": 742}]}, {"c" : [{"v": "Myanmar"}, {"v": 107}]}, {"c" : [{"v": "Slovakia"}, {"v": 363}]}, {"c" : [{"v": "Portugal"}, {"v": 1107}]}, {"c" : [{"v": "Czech Republic"}, {"v": 1069}]}, {"c" : [{"v": "Malaysia"}, {"v": 539}]}, {"c" : [{"v": "Bulgaria"}, {"v": 702}]}, {"c" : [{"v": "Gabon"}, {"v": 6}]}, {"c" : [{"v": "China"}, {"v": 2578}]}, {"c" : [{"v": "Serbia"}, {"v": 487}]}, {"c" : [{"v": "Trinidad and Tobago"}, {"v": 25}]}, {"c" : [{"v": "Slovenia"}, {"v": 292}]}, {"c" : [{"v": "Taiwan"}, {"v": 340}]}, {"c" : [{"v": "Ukraine"}, {"v": 2630}]}, {"c" : [{"v": "El Salvador"}, {"v": 75}]}, {"c" : [{"v": "Jordan"}, {"v": 240}]}, {"c" : [{"v": "Guatemala"}, {"v": 81}]}, {"c" : [{"v": "Central African Republic"}, {"v": 10}]}, {"c" : [{"v": "Armenia"}, {"v": 155}]}, {"c" : [{"v": "Dominica"}, {"v": 128}]}, {"c" : [{"v": "United Arab Emirates"}, {"v": 365}]}, {"c" : [{"v": "Peru"}, {"v": 208}]}, {"c" : [{"v": "Moldova"}, {"v": 109}]}, {"c" : [{"v": "Botswana"}, {"v": 15}]}, {"c" : [{"v": "Venezuela"}, {"v": 247}]}, {"c" : [{"v": "Egypt"}, {"v": 661}]}, {"c" : [{"v": "Cambodia"}, {"v": 115}]}, {"c" : [{"v": "Costa Rica"}, {"v": 168}]}, {"c" : [{"v": "Samoa"}, {"v": 2}]}, {"c" : [{"v": "Ecuador"}, {"v": 85}]}, {"c" : [{"v": "Macedonia"}, {"v": 123}]}, {"c" : [{"v": "Saint Lucia"}, {"v": 2}]}, {"c" : [{"v": "Iran"}, {"v": 1246}]}, {"c" : [{"v": "Indonesia"}, {"v": 963}]}, {"c" : [{"v": "Greenland"}, {"v": 4}]}, {"c" : [{"v": "Madagascar"}, {"v": 22}]}, {"c" : [{"v": "Palestine"}, {"v": 51}]}, {"c" : [{"v": "Kyrgyzstan"}, {"v": 44}]}, {"c" : [{"v": "Antigua and Barbuda"}, {"v": 11}]}, {"c" : [{"v": "Albania"}, {"v": 66}]}, {"c" : [{"v": "Qatar"}, {"v": 38}]}, {"c" : [{"v": "Malta"}, {"v": 121}]}, {"c" : [{"v": "San Marino"}, {"v": 2}]}, {"c" : [{"v": "Afghanistan"}, {"v": 62}]}, {"c" : [{"v": "Saudi Arabia"}, {"v": 137}]}, {"c" : [{"v": "Vietnam"}, {"v": 691}]}, {"c" : [{"v": "Bosnia and Herzegovina"}, {"v": 150}]}, {"c" : [{"v": "Panama"}, {"v": 48}]}, {"c" : [{"v": "Tunisia"}, {"v": 218}]}, {"c" : [{"v": "Heard Island and McDonald Islands"}, {"v": 1}]}, {"c" : [{"v": "Niger"}, {"v": 285}]}, {"c" : [{"v": "Syria"}, {"v": 64}]}, {"c" : [{"v": "Nepal"}, {"v": 487}]}, {"c" : [{"v": "Uzbekistan"}, {"v": 64}]}, {"c" : [{"v": "South Korea"}, {"v": 349}]}, {"c" : [{"v": "Solomon Islands"}, {"v": 6}]}, {"c" : [{"v": "Abkhazia"}, {"v": 7}]}, {"c" : [{"v": "Cyprus"}, {"v": 80}]}, {"c" : [{"v": "Micronesia"}, {"v": 4}]}, {"c" : [{"v": "Macao SAR"}, {"v": 6}]}, {"c" : [{"v": "Jamaica"}, {"v": 38}]}, {"c" : [{"v": "Kazakhstan"}, {"v": 100}]}, {"c" : [{"v": "Azerbaijan"}, {"v": 77}]}, {"c" : [{"v": "Uganda"}, {"v": 53}]}, {"c" : [{"v": "Bahrain"}, {"v": 34}]}, {"c" : [{"v": "Sri Lanka"}, {"v": 867}]}, {"c" : [{"v": "Bermuda"}, {"v": 6}]}, {"c" : [{"v": "Mali"}, {"v": 12}]}, {"c" : [{"v": "Guinea"}, {"v": 6}]}, {"c" : [{"v": "Nicaragua"}, {"v": 38}]}, {"c" : [{"v": "Antarctica"}, {"v": 8}]}, {"c" : [{"v": "Isle of Man"}, {"v": 12}]}, {"c" : [{"v": "Algeria"}, {"v": 127}]}, {"c" : [{"v": "Aruba"}, {"v": 5}]}, {"c" : [{"v": "Fiji"}, {"v": 10}]}, {"c" : [{"v": "Montenegro"}, {"v": 14}]}, {"c" : [{"v": "Rwanda"}, {"v": 6}]}, {"c" : [{"v": "Kuwait"}, {"v": 42}]}, {"c" : [{"v": "Morocco"}, {"v": 228}]}, {"c" : [{"v": "North Korea"}, {"v": 25}]}, {"c" : [{"v": "Mozambique"}, {"v": 12}]}, {"c" : [{"v": "Bahamas, The"}, {"v": 12}]}, {"c" : [{"v": "Romania"}, {"v": 116}]}, {"c" : [{"v": "Maldives"}, {"v": 22}]}, {"c" : [{"v": "Zimbabwe"}, {"v": 19}]}, {"c" : [{"v": "Yemen"}, {"v": 12}]}, {"c" : [{"v": "Seychelles"}, {"v": 2}]}, {"c" : [{"v": "Curacao"}, {"v": 12}]}, {"c" : [{"v": "Liberia"}, {"v": 1}]}, {"c" : [{"v": "Kosovo"}, {"v": 42}]}, {"c" : [{"v": "Andorra"}, {"v": 53}]}, {"c" : [{"v": "Belize"}, {"v": 6}]}, {"c" : [{"v": "Ghana"}, {"v": 60}]}, {"c" : [{"v": "Mauritius"}, {"v": 46}]}, {"c" : [{"v": "Reunion"}, {"v": 6}]}, {"c" : [{"v": "Brunei"}, {"v": 8}]}, {"c" : [{"v": "South Sudan"}, {"v": 3}]}, {"c" : [{"v": "Ethiopia"}, {"v": 53}]}, {"c" : [{"v": "Libya"}, {"v": 15}]}, {"c" : [{"v": "Senegal"}, {"v": 5}]}, {"c" : [{"v": "Cayman Islands"}, {"v": 11}]}, {"c" : [{"v": "Namibia"}, {"v": 11}]}, {"c" : [{"v": "Mongolia"}, {"v": 37}]}, {"c" : [{"v": "Marshall Islands"}, {"v": 19}]}, {"c" : [{"v": "Cuba"}, {"v": 66}]}, {"c" : [{"v": "Benin"}, {"v": 7}]}, {"c" : [{"v": "Chad"}, {"v": 8}]}, {"c" : [{"v": "Guyana"}, {"v": 5}]}, {"c" : [{"v": "Saba"}, {"v": 1}]}, {"c" : [{"v": "Angola"}, {"v": 8}]}, {"c" : [{"v": "Sudan"}, {"v": 6}]}, {"c" : [{"v": "Tanzania"}, {"v": 46}]}, {"c" : [{"v": "Cameroon"}, {"v": 37}]}, {"c" : [{"v": "Barbados"}, {"v": 11}]}, {"c" : [{"v": "Turks and Caicos Islands"}, {"v": 1}]}, {"c" : [{"v": "Jersey"}, {"v": 8}]}, {"c" : [{"v": "Mauritania"}, {"v": 4}]}, {"c" : [{"v": "Faroe Islands"}, {"v": 6}]}, {"c" : [{"v": "Guam"}, {"v": 2}]}, {"c" : [{"v": "Tajikistan"}, {"v": 6}]}, {"c" : [{"v": "Tuvalu"}, {"v": 1}]}, {"c" : [{"v": "French Polynesia"}, {"v": 3}]}, {"c" : [{"v": "Liechtenstein"}, {"v": 7}]}, {"c" : [{"v": "Gibraltar"}, {"v": 7}]}, {"c" : [{"v": "FYRO Macedonia"}, {"v": 8}]}, {"c" : [{"v": "Norfolk Island"}, {"v": 1}]}, {"c" : [{"v": "Vanuatu"}, {"v": 3}]}, {"c" : [{"v": "Bhutan"}, {"v": 10}]}, {"c" : [{"v": "Turkmenistan"}, {"v": 8}]}, {"c" : [{"v": "French-Guadeloupe"}, {"v": 3}]}, {"c" : [{"v": "Jan Mayen"}, {"v": 1}]}, {"c" : [{"v": "ZZZAbkhazia"}, {"v": 3}]}, {"c" : [{"v": "Haiti"}, {"v": 9}]}, {"c" : [{"v": "New Caledonia"}, {"v": 7}]}, {"c" : [{"v": "Zambia"}, {"v": 14}]}, {"c" : [{"v": "Suriname"}, {"v": 1}]}, {"c" : [{"v": "Midway Islands"}, {"v": 13}]}, {"c" : [{"v": "Grenada"}, {"v": 3}]}, {"c" : [{"v": "Malawi"}, {"v": 9}]}, {"c" : [{"v": "Kiribati"}, {"v": 4}]}, {"c" : [{"v": "Lesotho"}, {"v": 2}]}, {"c" : [{"v": "Cape Verde"}, {"v": 3}]}, {"c" : [{"v": "Congo (DRC)"}, {"v": 6}]}, {"c" : [{"v": "Iraq"}, {"v": 31}]}, {"c" : [{"v": "Laos"}, {"v": 2}]}, {"c" : [{"v": "Ivory Coast"}, {"v": 9}]}, {"c" : [{"v": "French-Martinique"}, {"v": 3}]}, {"c" : [{"v": "Burkina Faso"}, {"v": 5}]}, {"c" : [{"v": "Sierra Leone"}, {"v": 3}]}, {"c" : [{"v": "Dominican Republic"}, {"v": 8}]}, {"c" : [{"v": "Pitcairn Islands"}, {"v": 2}]}, {"c" : [{"v": "Svalbard"}, {"v": 1}]}, {"c" : [{"v": "Swaziland"}, {"v": 1}]}, {"c" : [{"v": "Monaco"}, {"v": 8}]}, {"c" : [{"v": "Northern Mariana Islands"}, {"v": 3}]}, {"c" : [{"v": "Guernsey"}, {"v": 2}]}, {"c" : [{"v": "Nigeria"}, {"v": 12}]}, {"c" : [{"v": "Republic of Korea"}, {"v": 1}]}, {"c" : [{"v": "Equatorial Guinea"}, {"v": 2}]}, {"c" : [{"v": "Timor-Leste"}, {"v": 1}]}, {"c" : [{"v": "Cook Islands"}, {"v": 1}]}, {"c" : [{"v": "Korea, North"}, {"v": 4}]}, {"c" : [{"v": "The Bahamas"}, {"v": 2}]}, {"c" : [{"v": "Pridnestrovie"}, {"v": 5}]}, {"c" : [{"v": "Transnistria"}, {"v": 1}]}, {"c" : [{"v": "Burundi"}, {"v": 1}]}, {"c" : [{"v": "Somalia"}, {"v": 3}]}, {"c" : [{"v": "Bouvet Island"}, {"v": 1}]}, {"c" : [{"v": "Papua New Guinea"}, {"v": 2}]}, {"c" : [{"v": "Gambia"}, {"v": 1}]}, {"c" : [{"v": "Tonga"}, {"v": 1}]}, {"c" : [{"v": "Togo"}, {"v": 2}]}, {"c" : [{"v": "East Timor"}, {"v": 1}]}, {"c" : [{"v": "Saint Barthelemy"}, {"v": 1}]}, {"c" : [{"v": "Christmas Island"}, {"v": 1}]}, {"c" : [{"v": "Saint Pierre and Miquelon"}, {"v": 1}]}, {"c" : [{"v": "Falkland Islands (Islas Malvinas)"}, {"v": 1}]}]});
    var options = {"legend":{"position":"none"},"width":1000,"height":600} ;
    var chart = new google.visualization.GeoChart(document.getElementById('c0946653-59db-4a2b-95e2-a0ffa85d6dfb'));
    chart.draw(data, options);
}
</script>
<div id="c0946653-59db-4a2b-95e2-a0ffa85d6dfb" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

$$$
n \times \frac{1}{\text{population}} \times \frac{\text{registered}}{\text{located}}  \times 1,000,000

<br />
<br />

<div class="fragment"> 
### ppm (Programmers-per-million) 
</div>


------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground 

# Where really?

' we need population
' demo: HTML type provider

------------------------------------------------------------------------------------------------

#### F#

<script type="text/javascript">
    google.load("visualization", "1", {packages:["geochart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "United States"}, {"v": 21.1441649612187}]}, {"c" : [{"v": "Australia"}, {"v": 33.5895256401621}]}, {"c" : [{"v": "Norway"}, {"v": 50.3885226982056}]}, {"c" : [{"v": "United Kingdom"}, {"v": 41.0609702691429}]}, {"c" : [{"v": "Poland"}, {"v": 9.21370207660584}]}, {"c" : [{"v": "New Zealand"}, {"v": 38.2940917317782}]}, {"c" : [{"v": "Netherlands"}, {"v": 27.2895993705161}]}, {"c" : [{"v": "Russia"}, {"v": 3.50390962731898}]}, {"c" : [{"v": "Canada"}, {"v": 21.2922413531757}]}, {"c" : [{"v": "India"}, {"v": 0.313034807609634}]}, {"c" : [{"v": "Brazil"}, {"v": 0.974474222519289}]}, {"c" : [{"v": "Sweden"}, {"v": 53.8960153684717}]}, {"c" : [{"v": "Switzerland"}, {"v": 25.8064642993965}]}, {"c" : [{"v": "Ireland"}, {"v": 36.4866453176332}]}, {"c" : [{"v": "Germany"}, {"v": 11.069909152792}]}, {"c" : [{"v": "Israel"}, {"v": 24.2741968485698}]}, {"c" : [{"v": "Denmark"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Belgium"}, {"v": 10.4248090891128}]}, {"c" : [{"v": "France"}, {"v": 6.34725338483007}]}, {"c" : [{"v": "Spain"}, {"v": 2.8411379457247}]}, {"c" : [{"v": "Turkey"}, {"v": 0.617316339027548}]}, {"c" : [{"v": "Guatemala"}, {"v": 0.429280799661604}]}, {"c" : [{"v": "Austria"}, {"v": 16.6815705617765}]}, {"c" : [{"v": "Italy"}, {"v": 4.92200989513662}]}, {"c" : [{"v": "South Africa"}, {"v": 2.49547075908887}]}, {"c" : [{"v": "Colombia"}, {"v": 0.568768047380725}]}, {"c" : [{"v": "China"}, {"v": 20.7944073955373}]}, {"c" : [{"v": "Japan"}, {"v": 0.710813724612141}]}, {"c" : [{"v": "Czech Republic"}, {"v": 21.7033563800386}]}, {"c" : [{"v": "Finland"}, {"v": 13.8987443946405}]}, {"c" : [{"v": "Saint Lucia"}, {"v": 37.3338887616799}]}, {"c" : [{"v": "South Korea"}, {"v": 0.137189030091987}]}, {"c" : [{"v": "Mexico"}, {"v": 0.323905558943612}]}, {"c" : [{"v": "Macedonia"}, {"v": 3.35256943281996}]}, {"c" : [{"v": "Oman"}, {"v": 18.5309511105928}]}, {"c" : [{"v": "Greece"}, {"v": 5.75583221422658}]}, {"c" : [{"v": "Madagascar"}, {"v": 0.309529774019991}]}, {"c" : [{"v": "Ukraine"}, {"v": 6.18582690419955}]}, {"c" : [{"v": "Malaysia"}, {"v": 0.437327411888557}]}, {"c" : [{"v": "Uruguay"}, {"v": 1.995304698859}]}, {"c" : [{"v": "Georgia"}, {"v": 3.7329874796648}]}, {"c" : [{"v": "Philippines"}, {"v": 0.202233838415483}]}, {"c" : [{"v": "Indonesia"}, {"v": 0.133242702070996}]}, {"c" : [{"v": "Trinidad and Tobago"}, {"v": 5.14504934155792}]}, {"c" : [{"v": "Egypt"}, {"v": 0.227474147792854}]}, {"c" : [{"v": "Portugal"}, {"v": 3.35745175411309}]}, {"c" : [{"v": "Argentina"}, {"v": 1.11512450373723}]}, {"c" : [{"v": "Bulgaria"}, {"v": 5.82413724792847}]}, {"c" : [{"v": "Bosnia and Herzegovina"}, {"v": 1.96652241082105}]}, {"c" : [{"v": "Singapore"}, {"v": 17.564127612541}]}, {"c" : [{"v": "Malta"}, {"v": 16.1737518392535}]}, {"c" : [{"v": "Iran"}, {"v": 0.611166794297645}]}, {"c" : [{"v": "Slovakia"}, {"v": 2.55944740851418}]}, {"c" : [{"v": "Sri Lanka"}, {"v": 0.662415654838544}]}, {"c" : [{"v": "Lithuania"}, {"v": 14.5328093793667}]}, {"c" : [{"v": "Estonia"}, {"v": 42.2151903708514}]}, {"c" : [{"v": "Paraguay"}, {"v": 1.01306686691447}]}, {"c" : [{"v": "Hungary"}, {"v": 5.65538292551966}]}, {"c" : [{"v": "Peru"}, {"v": 1.10263416871329}]}, {"c" : [{"v": "Moldova"}, {"v": 1.95437879870323}]}, {"c" : [{"v": "Botswana"}, {"v": 3.11268445302353}]}, {"c" : [{"v": "Dominica"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Slovenia"}, {"v": 26.9233339410991}]}, {"c" : [{"v": "Pakistan"}, {"v": 0.178740477775467}]}, {"c" : [{"v": "Kazakhstan"}, {"v": 0.391146571303903}]}, {"c" : [{"v": "El Salvador"}, {"v": 3.19480880875329}]}, {"c" : [{"v": "Jamaica"}, {"v": 2.54993610921395}]}, {"c" : [{"v": "Ecuador"}, {"v": 0.417987076041062}]}, {"c" : [{"v": "Belarus"}, {"v": 6.57862418811075}]}, {"c" : [{"v": "Serbia"}, {"v": 3.92523361387584}]}, {"c" : [{"v": "Croatia"}, {"v": 4.97111795969029}]}, {"c" : [{"v": "Uganda"}, {"v": 0.188386188917079}]}, {"c" : [{"v": "Chile"}, {"v": 0.763428043214008}]}, {"c" : [{"v": "Cuba"}, {"v": 2.47143014084609}]}, {"c" : [{"v": "Bhutan"}, {"v": 8.92523849937978}]}, {"c" : [{"v": "Cyprus"}, {"v": 8.198469078716}]}, {"c" : [{"v": "United Arab Emirates"}, {"v": 1.40911187290431}]}, {"c" : [{"v": "Vietnam"}, {"v": 0.224728262448947}]}, {"c" : [{"v": "Mauritius"}, {"v": 5.49862917165655}]}, {"c" : [{"v": "Saudi Arabia"}, {"v": 0.223887784806559}]}, {"c" : [{"v": "Thailand"}, {"v": 0.211294647909894}]}, {"c" : [{"v": "Latvia"}, {"v": 3.54508030920587}]}, {"c" : [{"v": "Bangladesh"}, {"v": 0.0431093878835645}]}, {"c" : [{"v": "Niger"}, {"v": 0.335221014225076}]}, {"c" : [{"v": "San Marino"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Palestine"}, {"v": 1.4417313369622}]}, {"c" : [{"v": "Tunisia"}, {"v": 0.622543866964826}]}, {"c" : [{"v": "Kyrgyzstan"}, {"v": 1.14820319945641}]}, {"c" : [{"v": "Azerbaijan"}, {"v": 0.711814187860433}]}, {"c" : [{"v": "Venezuela"}, {"v": 0.223796140659211}]}, {"c" : [{"v": "South Korea"}, {"v": 0.137189030091987}]}, {"c" : [{"v": "Marshall Islands"}, {"v": 81.9457102597392}]}]});
    var options = {"legend":{"position":"none"},"width":1000,"height":600} 
    var chart = new google.visualization.GeoChart(document.getElementById('2f1227d9-f924-4eed-ad93-6fe640abde4c'));
    chart.draw(data, options);
}
</script>
<div id="2f1227d9-f924-4eed-ad93-6fe640abde4c" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

### R

<script type="text/javascript">
    google.load("visualization", "1", {packages:["geochart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "United States"}, {"v": 86.142972528205}]}, {"c" : [{"v": "France"}, {"v": 34.8578669494766}]}, {"c" : [{"v": "Ireland"}, {"v": 121.135662454542}]}, {"c" : [{"v": "United Kingdom"}, {"v": 94.9201650377589}]}, {"c" : [{"v": "Australia"}, {"v": 99.4389174833419}]}, {"c" : [{"v": "Sweden"}, {"v": 103.592341227712}]}, {"c" : [{"v": "Poland"}, {"v": 23.4859072540933}]}, {"c" : [{"v": "Switzerland"}, {"v": 149.84398625456}]}, {"c" : [{"v": "Netherlands"}, {"v": 104.650393213385}]}, {"c" : [{"v": "Russia"}, {"v": 6.81841873424234}]}, {"c" : [{"v": "Germany"}, {"v": 61.264764395223}]}, {"c" : [{"v": "Brazil"}, {"v": 7.62442357152844}]}, {"c" : [{"v": "Singapore"}, {"v": 94.0935407814696}]}, {"c" : [{"v": "Canada"}, {"v": 84.5053554274897}]}, {"c" : [{"v": "Spain"}, {"v": 26.7665101202485}]}, {"c" : [{"v": "Greece"}, {"v": 30.0582348965166}]}, {"c" : [{"v": "Belgium"}, {"v": 63.1620785987423}]}, {"c" : [{"v": "New Zealand"}, {"v": 108.865264654264}]}, {"c" : [{"v": "Lebanon"}, {"v": 6.95801934836919}]}, {"c" : [{"v": "Norway"}, {"v": 88.8429215994678}]}, {"c" : [{"v": "Oman"}, {"v": 38.6061481470684}]}, {"c" : [{"v": "Denmark"}, {"v": 137.075675661231}]}, {"c" : [{"v": "Portugal"}, {"v": 36.2604789444213}]}, {"c" : [{"v": "Italy"}, {"v": 21.4050197765244}]}, {"c" : [{"v": "Pakistan"}, {"v": 0.714325732386172}]}, {"c" : [{"v": "Saint Lucia"}, {"v": 37.3338887616799}]}, {"c" : [{"v": "Hungary"}, {"v": 14.1384573137992}]}, {"c" : [{"v": "Israel"}, {"v": 59.0071194142223}]}, {"c" : [{"v": "India"}, {"v": 4.34143431194298}]}, {"c" : [{"v": "Austria"}, {"v": 72.2868057676982}]}, {"c" : [{"v": "Slovenia"}, {"v": 63.9429181101104}]}, {"c" : [{"v": "Ukraine"}, {"v": 14.4878577493095}]}, {"c" : [{"v": "Finland"}, {"v": 83.3924663678429}]}, {"c" : [{"v": "Trinidad and Tobago"}, {"v": 5.14504934155792}]}, {"c" : [{"v": "Turkey"}, {"v": 4.76215461535537}]}, {"c" : [{"v": "South Africa"}, {"v": 7.73595935317548}]}, {"c" : [{"v": "Thailand"}, {"v": 1.05647323954947}]}, {"c" : [{"v": "Qatar"}, {"v": 8.67435346340951}]}, {"c" : [{"v": "Czech Republic"}, {"v": 33.5415507691506}]}, {"c" : [{"v": "Bulgaria"}, {"v": 8.73620587189271}]}, {"c" : [{"v": "Costa Rica"}, {"v": 14.1995197298051}]}, {"c" : [{"v": "Venezuela"}, {"v": 2.0141652659329}]}, {"c" : [{"v": "Japan"}, {"v": 3.71810255950966}]}, {"c" : [{"v": "Argentina"}, {"v": 7.16865752402502}]}, {"c" : [{"v": "Sri Lanka"}, {"v": 6.95536437580471}]}, {"c" : [{"v": "Lithuania"}, {"v": 65.3976422071502}]}, {"c" : [{"v": "China"}, {"v": 157.848456138851}]}, {"c" : [{"v": "Colombia"}, {"v": 4.68968598815053}]}, {"c" : [{"v": "Ghana"}, {"v": 0.501919742873497}]}, {"c" : [{"v": "Mexico"}, {"v": 3.56296114837973}]}, {"c" : [{"v": "Estonia"}, {"v": 79.1534819453463}]}, {"c" : [{"v": "Philippines"}, {"v": 1.07759713840026}]}, {"c" : [{"v": "Luxembourg"}, {"v": 60.2577517326662}]}, {"c" : [{"v": "Iran"}, {"v": 2.87952774119407}]}, {"c" : [{"v": "Latvia"}, {"v": 24.8155621644411}]}, {"c" : [{"v": "Malaysia"}, {"v": 4.58851345323173}]}, {"c" : [{"v": "Chile"}, {"v": 13.3599907562451}]}, {"c" : [{"v": "Morocco"}, {"v": 0.610927137612498}]}, {"c" : [{"v": "Slovakia"}, {"v": 15.3566844510851}]}, {"c" : [{"v": "Peru"}, {"v": 3.52842933988254}]}, {"c" : [{"v": "Serbia"}, {"v": 14.7196260520344}]}, {"c" : [{"v": "Tanzania"}, {"v": 0.881311271284692}]}, {"c" : [{"v": "Georgia"}, {"v": 24.2644186178212}]}, {"c" : [{"v": "Croatia"}, {"v": 14.9133538790709}]}, {"c" : [{"v": "Jordan"}, {"v": 3.56710061790081}]}, {"c" : [{"v": "United Arab Emirates"}, {"v": 4.22733561871294}]}, {"c" : [{"v": "Cameroon"}, {"v": 0.305774387199748}]}, {"c" : [{"v": "Kenya"}, {"v": 3.08620282117038}]}, {"c" : [{"v": "Iceland"}, {"v": 185.96955837366}]}, {"c" : [{"v": "Uruguay"}, {"v": 5.98591409657699}]}, {"c" : [{"v": "Egypt"}, {"v": 1.0602574734783}]}, {"c" : [{"v": "Bangladesh"}, {"v": 0.947776961143472}]}, {"c" : [{"v": "Indonesia"}, {"v": 0.453025187041387}]}, {"c" : [{"v": "Armenia"}, {"v": 11.5924398345171}]}, {"c" : [{"v": "Cyprus"}, {"v": 49.190814472296}]}, {"c" : [{"v": "South Korea"}, {"v": 4.52723799303557}]}, {"c" : [{"v": "Senegal"}, {"v": 0.469200639659638}]}, {"c" : [{"v": "Vietnam"}, {"v": 1.19855073306105}]}, {"c" : [{"v": "Kazakhstan"}, {"v": 1.56458628521561}]}, {"c" : [{"v": "Romania"}, {"v": 0.702844464541746}]}, {"c" : [{"v": "Kyrgyzstan"}, {"v": 1.14820319945641}]}, {"c" : [{"v": "Dominica"}, {"v": 194.804631862103}]}, {"c" : [{"v": "Kuwait"}, {"v": 4.97944858997016}]}, {"c" : [{"v": "Fiji"}, {"v": 32.037385511753}]}, {"c" : [{"v": "Mozambique"}, {"v": 0.262798295078753}]}, {"c" : [{"v": "Taiwan"}, {"v": 7.97332692719065}]}, {"c" : [{"v": "Moldova"}, {"v": 9.77189399351616}]}, {"c" : [{"v": "Tunisia"}, {"v": 5.60289480268343}]}, {"c" : [{"v": "Belarus"}, {"v": 5.11670770186391}]}, {"c" : [{"v": "San Marino"}, {"v": 210.395494915087}]}, {"c" : [{"v": "Azerbaijan"}, {"v": 1.42362837572087}]}, {"c" : [{"v": "Iraq"}, {"v": 0.366602633215824}]}, {"c" : [{"v": "Niger"}, {"v": 1.3408840569003}]}, {"c" : [{"v": "Bosnia and Herzegovina"}, {"v": 3.9330448216421}]}, {"c" : [{"v": "Albania"}, {"v": 2.40611252624628}]}, {"c" : [{"v": "Nicaragua"}, {"v": 3.32640872942839}]}, {"c" : [{"v": "Cambodia"}, {"v": 2.66628926312568}]}, {"c" : [{"v": "Nepal"}, {"v": 3.66359670242818}]}, {"c" : [{"v": "Ecuador"}, {"v": 1.25252016505323}]}, {"c" : [{"v": "North Korea"}, {"v": 1.43393157573447}]}, {"c" : [{"v": "Burkina Faso"}, {"v": 0.364818665370511}]}, {"c" : [{"v": "Mauritius"}, {"v": 10.9972583433131}]}, {"c" : [{"v": "Ethiopia"}, {"v": 0.150621498234794}]}, {"c" : [{"v": "Syria"}, {"v": 0.748125760576649}]}, {"c" : [{"v": "The Bahamas"}, {"v": 18.3686998986151}]}, {"c" : [{"v": "Honduras"}, {"v": 1.59249906253389}]}, {"c" : [{"v": "Suriname"}, {"v": 12.8205615368059}]}, {"c" : [{"v": "Micronesia"}, {"v": 67.549643090199}]}, {"c" : [{"v": "South Korea"}, {"v": 0.137189030091987}]}, {"c" : [{"v": "Macedonia"}, {"v": 10.0577082984599}]}, {"c" : [{"v": "Tonga"}, {"v": 67.2539351264136}]}, {"c" : [{"v": "Saudi Arabia"}, {"v": 0.223887784806559}]}, {"c" : [{"v": "Algeria"}, {"v": 0.687534981155688}]}, {"c" : [{"v": "Grenada"}, {"v": 67.204468388747}]}, {"c" : [{"v": "Bolivia"}, {"v": 1.2642814771723}]}, {"c" : [{"v": "Malta"}, {"v": 48.5212555177605}]}, {"c" : [{"v": "Rwanda"}, {"v": 1.20211032827865}]}, {"c" : [{"v": "Nigeria"}, {"v": 0.0371366253966696}]}, {"c" : [{"v": "Cuba"}, {"v": 0.617857535211523}]}, {"c" : [{"v": "South Sudan"}, {"v": 0.572426288819756}]}, {"c" : [{"v": "Guyana"}, {"v": 9.29723297586351}]}, {"c" : [{"v": "Uzbekistan"}, {"v": 0.439844011595928}]}, {"c" : [{"v": "Zambia"}, {"v": 0.435807349010436}]}, {"c" : [{"v": "Mongolia"}, {"v": 2.23415964791675}]}, {"c" : [{"v": "Guatemala"}, {"v": 2.14640399830802}]}, {"c" : [{"v": "The Bahamas"}, {"v": 18.3686998986151}]}, {"c" : [{"v": "Andorra"}, {"v": 89.0109891772304}]}, {"c" : [{"v": "Afghanistan"}, {"v": 0.251078096082313}]}, {"c" : [{"v": "Abkhazia"}, {"v": 28.8490197946551}]}, {"c" : [{"v": "Antigua and Barbuda"}, {"v": 80.4693587076013}]}, {"c" : [{"v": "Palestine"}, {"v": 1.4417313369622}]}, {"c" : [{"v": "Panama"}, {"v": 1.82036707472424}]}, {"c" : [{"v": "Mali"}, {"v": 0.378610943224058}]}, {"c" : [{"v": "Laos"}, {"v": 1.0695741651273}]}]});
    var options = {"legend":{"position":"none"},"width":1000,"height":600} 
    var chart = new google.visualization.GeoChart(document.getElementById('f18c96ce-58b2-4455-b135-76efefd6ac7c'));
    chart.draw(data, options);
}
</script>
<div id="f18c96ce-58b2-4455-b135-76efefd6ac7c" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

- data-background : images/dominican-republic.jpg

------------------------------------------------------------------------------------------------

- data-background : #121412

## (Sampling bias)

<img src="images/skull.jpg" style="width: 200px" />

' only registered users
' only active users
' and out of them, only the ones that gave out their address

************************************************************************************************

# Tags + Users

<div class="fragment">

# = 
# Communities

</div>

' Users ask questions with specific tags & answer questions with specific tags
' No-one knows everything

' how to define relation between tags through posts & users, similar users - similar tags
' memory vs. distributed computing
' t-SNE visualization - how to create a meaningful visualization
' Networks
' technology: RProvider, Fable

------------------------------------------------------------------------------------------------

# Tags 

### define 

# relations



------------------------------------------------------------------------------------------------

|           | F# | C# | JS | R | Cobol |
|-----------|----|----|------------|---|---|
| Evelina   | 1  | 0  | 1          | 1 | 0 |
| Krzysztof | 1  | 1  | 1          | 0 | 0 |

------------------------------------------------------------------------------------------------

### 44 265 tags x  5 277 831 users

------------------------------------------------------------------------------------------------

#### Users with more than 1,000 posts
#### Tags with more than 5,000 posts

<div class="fragment">
## 807 tags, 1633 power users
</div>

------------------------------------------------------------------------------------------------

# t-SNE
## t-distributed Stochastic Neighbourhood embedding

' image
' run t-sne on my desktop at work

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation0.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation1.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation2.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation3.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation4.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation5.png" />

------------------------------------------------------------------------------------------------
# t-SNE in R

    [lang=R]
    library(tsne)

    ts <- tsne(m, perplexity=20)

    plot(ts)

------------------------------------------------------------------------------------------------

# t-SNE in F#

    open RProvider
    open RProvider.tsne

    let ts = R.tsne(namedParams[ "X", box m; "perplexity", box 20])

    R.plot(ts)

------------------------------------------------------------------------------------------------

- data-background : images/rplot.png

------------------------------------------------------------------------------------------------

*The best thing about R is that it was written by statisticians.*
<div class="fragment">
*The worst thing about R is that it was written by statisticians.*
</div>
<br />

Bow Cowgill, 2009

------------------------------------------------------------------------------------------------

![](images/fable.png)

------------------------------------------------------------------------------------------------

- data-background : images/tsne-full.png

------------------------------------------------------------------------------------------------

<img src="images/tsne-example1.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-example2.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-example3.png" style="width: 960px" />

------------------------------------------------------------------------------------------------

<img src="images/hapmap-tsne.png" style="height: 550px" />

Platzer, A. (2013). Visualization of SNPs with t-SNE. PLoS ONE, 8(2), e56883. 

************************************************************************************************

## ✔ Tags 
## ✔ Users
## ✔ Technologies

<br />

<div class="fragment">
# Questions and Answers
</div>

------------------------------------------------------------------------------------------------

# Word2vec

word embeddings

------------------------------------------------------------------------------------------------

# t-SNE
### Point + local neighbourhood
# ⬇
### 2D embedding

------------------------------------------------------------------------------------------------

# Word2vec
### Word + local context
# ⬇
### vector-space embedding

------------------------------------------------------------------------------------------------

# Word2vec

**F#** is a functional language on the **.NET platform**. <br/>
**Scala** is a functional language on the **JVM**.

------------------------------------------------------------------------------------------------

## Scala - JVM + .NET
# =
<div class="fragment"> 
## C#, F# 
</div>

------------------------------------------------------------------------------------------------

## F# - .NET
# =
<div class="fragment"> 
## SML, OCaml, GHCi, Haskell, Idris
</div>

------------------------------------------------------------------------------------------------

![](images/word2vec-paper3.png)

------------------------------------------------------------------------------------------------

![](images/word2vec-paper2.png)

------------------------------------------------------------------------------------------------

![](images/word2vec-paper1.png)

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

<div class="fragment">

## Is
# StackOverflow
## a meritocracy?

</div>

' now a provocative question
' How would we recognize meritocracy? Well, if you come and give a good answer, then you get higher score and reputation for your answer
' So I'll look at how good is author's reputation and other author properties related to the score of the question he answered

------------------------------------------------------------------------------------------------

<img src="images/reputation-score.png" style="width: 960px"/>

------------------------------------------------------------------------------------------------

<img src="images/reputation-score-log.png" style="width: 960px"/>

------------------------------------------------------------------------------------------------

# Regression 

### input data
# ⬇
### score

------------------------------------------------------------------------------------------------

# Input data 

18,100,293 rows

<div style="font-size:20pt" />
"Accepted" 
"Question Score" 
"Number of tags" 
"Answer Count"           
"Comment Count"           
"Question Favourite Count"
"Question View Count"     
"Author Reputation"      
"Author Profile Views"    
"Author Up Votes"        
"Author Down Votes"       
"Gold Badges"            
"Silver Badges"           
"Bronze Badges"          
"Author Number of Tags"   
"Time to Answer"        
</div>

# ⬇ 

"Score"  

<div class="fragment">
linear regression, nonlinear regression, random forests, SVMs, neural networks

------------------------------------------------------------------------------------------------

# Most predictive

<div class="fragment">

- Question favourites

- Question view count

- Accepted

</div>

------------------------------------------------------------------------------------------------

 - data-background : images/chucknorrisapproves.gif

------------------------------------------------------------------------------------------------

![](images/leverage.png)

------------------------------------------------------------------------------------------------

![](images/lever.png)

------------------------------------------------------------------------------------------------

<img src="images/leverage-illustration.png" style="width: 600px" />


' The 'Jon Skeet' effect
' The reputation is not really important, unless you are Jon Skeet

------------------------------------------------------------------------------------------------

![](images/jonskeet.png)

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Quality matters

<div class="fragment">
## ... unless you are Jon Skeet
</div>

************************************************************************************************

- data-background: images/posts-background.png
- class : withbackground

# Technological side of things


' Data science is about a lot of things - from preprocessing the data, through mathematical models, to visualization
' No single tool - but type providers are a great thing that basically make external data sources a part of your IDE

## Tool for the job

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Data science side of things
## Questions

<div class="fragment">
## Move to the Dominican republic?
</div>

' think about your demographics - who are you targetting with your product
' if you're doing .NET - there's a world out there! And if you're doing JavaScript - it's not the only thing in the world!
' help people on StackOverflow - what matters is that answers are helpful, not who they come from (unless...)
' and if you want to do digital nomad thing - you can gather data where you can find likely minded people
' Sampling bias!!!

------------------------------------------------------------------------------------------------

- data-background : images/beach.jpg

<table>
<tr>
  <td class="noborder" style="width:60%;"></td>
   <td class="noborder" style="width:40%;">

<h2> <div style="color: white" > Evelina Gabasova </div> </h2>
<div style="color: white" >
@evelgab <br />
evelinag.com<br />
</div>
<br /><br /><br/><br/><br/><br/>
</td> 
</tr>
</table>

