---
layout: page
title: Compétitions
permalink: /competitions/
accent_image: /assets/img/homePicture.jpg
---
Vous pouvez trouver sur cette page la listes des courses de la région Auvergne Rhônes-Alpes, départements : Haute-Savoie, Savoie,Ain, avec la liste des coureurs de l'UCT engagés. Vous pouvez également retrouver les résultats des courses sur la page [Résultats](/Resultats/).


# Courses 2023
* This will become a table of contents (this text will be scrapped).
{:toc}
## Catégorie access :
![image](/Calendrier_courses/access.png)

## Contre la montre :
![image](/Calendrier_courses/chrono.png)

## Gentlemen :
![image](/Calendrier_courses/gentlemen.png)

## Grimpée :
![image](/Calendrier_courses/grimpée.png)





## Carte des courses :

<iframe src="/Calendrier_courses/map_courses.html" width="900" height="600"></iframe>

# Courses du mois en cours :
![image](/assets/img/under_construction.jpg)
add a function to change the iframe depending of actual month
<script>
    function changeMap() {
        var monthNames = ["January", "February", "March", "April", "May", "June",
            "July", "August", "September", "October", "November", "December"
        ];

        var d = new Date();
        document.write("The current month is " + monthNames[d.getMonth()]);

        create a new string with the date
        var path = "/Calendrier_courses/map_courses_" + monthNames[d.getMonth()] + ".html";
        <iframe src="'path'" width="900" height="600"></iframe>


        load the iframe using the new path
        document.getElementById("map").src = path;

    }
</script>
<button onclick="changeMap()">Change map</button>

# Mars :
<iframe src="/Calendrier_courses/map_courses_March.html" width="900" height="600"></iframe>

# Avril :
<iframe src="/Calendrier_courses/map_courses_April.html" width="900" height="600"></iframe>

# Mai :
<iframe src="/Calendrier_courses/map_courses_May.html" width="900" height="600"></iframe>

# Juin :
<iframe src="/Calendrier_courses/map_courses_June.html" width="900" height="600"></iframe>

# Juillet :
<iframe src="/Calendrier_courses/map_courses_July.html" width="900" height="600"></iframe>

# Août :
<iframe src="/Calendrier_courses/map_courses_August.html" width="900" height="600"></iframe>

# Septembre :
<iframe src="/Calendrier_courses/map_courses_September.html" width="900" height="600"></iframe>

# Octobre :
<iframe src="/Calendrier_courses/map_courses_October.html" width="900" height="600"></iframe>















