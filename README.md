1. Cree el repositorio en el github y agregue los archivos README.md y el .gitignore con la interfaz de github
2. 	git clone https://github.com/mike1591991/aspirantes-mir-html-y-css.git
	git push -u origin main
3. mkdir ejercicio1-html-y-css
4. touch index.html
5. <!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Mi Receta</title>
  </head>
  <body>

  </body>
</html>
6. 	git add . 
	git commit -m 'Agrega el esqueleto del segundo ejercicio'
7. <!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Mi Receta</title>
  </head>
  <body>
<h1>Receta: Ensalada</h1>
<img src="salad.png" alt="Ensalada">
<h2>Ingredientes</h2>
<p>Los ingredientes necesarios para prepar la ensalda son los 

siguientes:</p>
<ul>
  <li>Pechuga</li>
  <li>Lechuga</li>
  <li>Tomate</li>
  <li>Cebolla</li>
  <li>Maiz</li>
</ul>
<h2>Preparación</h2>
<span>Se pican todos los ingredientes, se mezclan y listo!</span>
  </body>
</html>
8. 	git add .
	git commit -m 'Agrega el cuerpo HTML del segundo ejercicio'
9. touch estilos.css -> <link rel="stylesheet" href="estilos.css">
10. 	git add .
	git commit -m 'Agrega estilos al segundo ejercicio'
11. 	git checkout main
	git merge develop
12. 	git push
13. 	git branch -D develop
14. 	https://github.com/mike1591991/aspirantes-mir-html-y-css.git
