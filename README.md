# Laboratorio Web

Front-end coursework from the Web ITAM Laboratory at Instituto Tecnológico Autónomo de México. The exercises cover HTML, CSS layout, JavaScript, and HTTP requests.

## Explore the projects

| Project | What it demonstrates |
| --- | --- |
| [Watch-It](Portafolio_P%C3%A1ginas_Web/WATCH-IT/html%27s/1-mainPage.html) | A watch-store prototype with product pages and a simulated checkout. |
| [HTML exercises](Ejercicios_Video_HTML/) | Basic HTML structure and a sample blog. |
| [CSS exercises](Ejercicios_Video_CSS/) | Styling practice with sample pages and a clock exercise. |
| [Box model](Ejercicios_Box_Model/) | Exercises for spacing, borders, and layout. |
| [Flexbox challenge](Reto_FlexBox_Random/id.html) | A layout exercise with a JavaScript component. |
| [Pyramid challenge](Reto_Pir%C3%A1mide/retoPiramide.html) | A pyramid-themed front-end layout exercise. |
| [JavaScript exercises](Ejercicios_JavaScript/) | Small examples of browser-side scripting and layout. |
| [AJAX](AJAX/ajaxcrash/) and [Requests](Requests/pruebaRequest.html) | Examples of loading local JSON, calling public APIs, and making requests to PHP endpoints. |

## Run locally

Use a browser and Python 3. From the repository root, start a local server:

~~~sh
python -m http.server 8000 --bind 127.0.0.1
~~~

Open [localhost:8000](http://localhost:8000) and select an exercise. You can also open standalone HTML pages directly, but use the server for exercises that request local JSON.

Some request exercises depend on the GitHub API or a historical Firebase endpoint. The PHP examples require a PHP server and their original endpoints. Python’s static server does not execute PHP.

[MIT license](LICENSE)
