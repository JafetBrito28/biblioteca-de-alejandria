https://es.wikipedia.org/wiki/Markdown#:~:text=Markdown%20es%20un%20lenguaje%20de,correo%20electr%C3%B3nico%20usando%20texto%20plano.

Markdown es un lenguaje de marcado ligero creado por jonh Gruber y Aaron Swartz que trata de 
conseguir la maxima legibilidad y facilidad de publicacion tanto en su forma de entrada como 
de salida, inspirandose en muchas convenciones existentes para marcar mensajes de correo electronico
usando texto plano. Se distribuye bajo licencia BSD y se distribuye como plugin (o al menos esta disponible)
en diferentes sistemas de gestion de contenidos(CMS). Markdown convierte el texto marcado en documentos
XHTML utilizando html2text creado por Aaron Swartz. Mardown fue implementado originariamente en
Perl por Gruber, pero desde entonces ha sido traducido a multitud de lenguajes de programacion. 
Incluyendo PHP, Python, Ruby, Java y Common Lisp. 

<!-- HEADINGS -->
# h1
## h2
### h3
#### h4
##### h5
###### h6
<!-- italic -->
this is an *italic* text
<!-- italic -->
this is an **strong** text
<!-- strikethrough -->
esto es un ~~texto~~ tachado

<!-- Ul -->
* apple
    * apple 2
* orange
    * orange 2
* ect 

<!-- OL -->
1. apple
    1.1 apple 2
2. orange.
3. ect

<!-- enlaces -->

[jafetbrito.com](http://www.jafetbrito.com)
<!-- 
[jafetbrito.com](http://www.jafetbrito.com "titulo-arternativo") -->

> this is a quote 

---

___

`console.log("hello world");`

``` javascript
console.log("hello world2"); 

    const mongoose = require('mongoose');

    mongoose.set('useFindAndModify)', false);
    mongoose.connect('mongodb://localhost/node-notes-db', {
        useCreateIndex: true,
        useNewUrlParser: true
        })
        .then(db => console.log('DB is connected'))
        .catch(err => console.error(err));

```

``` ptyhon 
print("hello world)

```


```html
<h1>helloword</h1>

```
|     tabla      |


|     |

<!-- IMG URL -->

![visual studio code logo](https://blog.noblinkyblinky.com/2017/09/25/connecting-visual-studio-code-to-github/vsc-logo/)

<!-- IMG local -->

![VSC](vsc-logo.png "vsc-code-logo ")

<!-- GITHUB MARKDOWN -->

* [x] tarea 1
* [ ] tarea 1
* [x] tarea 1

<!-- mencionar -->

@fatzweb

https://gist.github.com/rxaviers/7360908

:computer:

https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet