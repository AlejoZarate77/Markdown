<!-- HEADINGS -->

# My title
## My title h2
### My title h3
#### My title h4
##### My title h5
###### My title h6


This is an *italic* text <!-- Cursiva --> 

This is an **strong** text
 <!--Negrita-->

This is a ~~crossed~~ out text <!-- Tachada-->

<!-- UL -->
* apple
    * banana
* orange
    * banana
* etc

<!-- Ordenadas -->
1. aplle
    1. apple 2
2. orange
3. etc

<!-- ENLACES -->
[google.com](https://www.google.com.ar/?hl=es)

<!-- CITAS -->
> This is a quote
---
---

<!-- GENERAR CODIGO `(entre medio el codigo)`-->
`console.log('hello world')`

---
<!-- BLOQUE DE CODIGO ```()``` -->
```javascript
let miImage = document.querySelector("img");
miImage.onclick = function () {
  let miSrc = miImage.getAttribute("src");
  if (miSrc === "images/firefox-icon.png") {
    miImage.setAttribute("src", "images/firefox2.png");
  } else {
    miImage.setAttribute("src", "images/firefox-icon.png");
  }
};
```
---
```python
print("Hello World")
```
---
```html
<h1>Hello world</h1>
```

<!-- TABLAS -->

|  banana   | banana    | banana   |
------------------------------------

<!-- GENERAR IMG -->
<!--titulo img-->
![visual studio code logo](descarga.png "vscode logo")

<!-- GITHUB MARKDOWN -->
* [x] Task 1 
* [ ] Task 2 
* [ ] Task 3 
* [x] Task 4 

<!-- MENCIONAR USUARIO -->
@alejito

<!-- EMOJIS GITHUB (buscar internet lista) -->
:woman:

<!-- PARA MAS INFO -->
[GitHub MarkDown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
