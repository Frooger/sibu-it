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
