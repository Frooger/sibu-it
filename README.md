# Sibu IT Workshop
Es geht um Skill Share in der Silberburg und IT Nerds.
Wir haben einen Arbeitskreis aufgebaut um diese Skills 
zu teilen um dann Crazy Stuff zu machen.


## Allgemein

### Riseup Pad für Uns
- https://pad.riseup.net/p/sibu-it-keep

### Hilfreiche Links
- https://roadmap.sh/frontend
- https://code.visualstudio.com/


## Erstes Treffen
Wir haben uns HTML,CSS,Javascript angeschaut und wollen es nochmal jeder für sich bis nächstes mal anschauen. Sinan bereitet bis nächstes mal ein Fall Beispiel vor.

```
<html>
<head>
    <style>
    .text-red {
        color: red;
    }

    .text-fett {
        font-weight: 100 !important;
    }

    .bg-purple {
        background-color: purple;
    }

    .card {
        width: 200px;
        height: 200px;
        border: 1px solid black;
        padding-top: 50px;
    }
    </style>
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const btn = document.getElementById('btn');
            btn.addEventListener('click', function () {
                const card = document.getElementById('event-card');
                if(card.classList.contains('bg-purple')) {
                    card.classList.remove('bg-purple')
                } else {
                    card.classList.add('bg-purple');
                }
            })
            
        }, false);
    </script>
</head>

<div id="event-card" class="card">
    <h1 class="text-red text-fett" >Das ist eine Webseite</h1>
</div>

<button id="btn">Klick mich</button>
</html>
```

## Tutorials
### Frontend Tutorials
HTML
https://www.w3schools.com/html/default.asp
CSS
https://www.w3schools.com/css/default.asp
Javascript
https://www.w3schools.com/js/default.asp


### Backend Tutorials

#### Datenbanken

**Relationale Datenbanken**
https://studyflix.de/informatik/relationale-datenbanken-600

**SQL**
https://code.tutsplus.com/articles/sql-for-beginners--net-8200
https://code.tutsplus.com/de/articles/sql-fur-anfanger-teil-2--net-8274
https://code.tutsplus.com/de/articles/sql-for-beginners-part-3-database-relationships--net-8561
