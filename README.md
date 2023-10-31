# Examen-Noviembre-2023
Pablo Jiménez Girardeau     Link: https://github.com/PabloJimenezGirardeau/Examen-Noviembre-2023.git

**1.** Un Pull Request sirve para, tras haber realizado un fork de un repositorio remoto y haber realizado un clone del proyecto para trabajar sobre este como repositorio local, solicitar desde Github al propietario original del repositorio que integre los cambios que hemos realizado nosotros desde este como local al proyecto original. El Pull Request pordrá ser entoces aceptado o rechazado por el propietario.

**2.** Un merge conflict se produce cuando, al fusionar dos ramas mediante un git merge por ejemplo, estas entran en conflicto debido a diversos factores. El que más hemos visto es cuando en un nano hay texto repetido o texto que no debería estar. La solución para resolver el conflicto consistía en abrir de editor de texto de nuevo y editar manualmente el archivo y quitar los fallos de este y el texto que estaba produciendo el conflicto.

**3.** Se puede hacer de dos maneras: o bien fusionar la rama examen_parcial sobre la main, o viceversa. Para fusionar la rama examen_parcial sobre main: primero deberemos cerciorarnos que nos encontramos sobre la rama main, para ellos usaremos el comando *"git checkout main"* , para situarnos en dicha rama. Posteriormente relizaremos el *"git merge examen_parcial"* para integrar la segunda rama en la primera. Otro procedimiento seria el opuesto: integrar la rama main en la rama examen_parcial , para ello haremos el mismo proceso. Nos situamos en examen_parcial con *"git checkout examen_parcial"* e inegramos main mediante *"git merge main"*.

**4.** Realizaría un *"git log --oneline"* para ver la lista de todos los commits y sus id de commits. Una vez conocido el id del commit que se desea editar, se usa un *"git fetch"* que te permitirá editar el commit en cuestión sin afectar al resto.

**5.** Un fork se realiza desde GitHub a un repositorio ajeno o remoto, simplemtente en la pestaña de dicho repositorio encontraremos un botón que dice "Fork". Esto crea una copia independiente del repositorio. Posteriormente podremos clonar dicho repositorio para trabajar sobre el como repositorio local. Generalmente, una vez realizado los cambios, se realiza un Pull Request al propietario original del proyecto (usuario al que le hemos hecho el fork) para integrar en el repositorio original los cambios confirmados en el repositorio local en el que hemos trabajado.

**6.**  a) cd Universidad/UAX/archivo.txt sin embargo, personalmente lo haría paso a paso mediante cd: haría un cd Universidad, cd UAX y finalmente cd archivo.txt. Esto se conoce como ruta absoluta, ya que nos dice la ubicación exacta de un archivo/directorio desdde el repositorio raíz. Al hacer *"pwd"* Git nos responderá : *Pablo_Jiménez_Girardeau/Universidad/UAX/archivo.txt.*
        b) Sabiendo que me encuentro en Universidad, la ruta es más corta, por lo que pasaría a ser la siguiente: cd UAX/archivo.txt. Esta se trata de una ruta relativa ya que , a diferecnia de la absoluta, esta no proporciona la ubicación exacta desde el directorio raíz sino que depende del punto de referencia o en el punto en el que se encuentra el usuario.

**7.** 1- b) git clone    2- a) git branch    3- c) git checkout    4- b) git add     5- b) git commit     6- b) git push   7- c) git pull  
8- d) git merge   9- a) git reset -hard     10- c) git log

**8.** Yo realizaría la integración de ambas ramas por partes, primero Matemáticas y luego Diseño UX. Lo haría mediante un git rebase, ya que a diferencia del git merge, este añade los cambios de manera secuencial y organizada y es más fácil mantener un control sobre lo que se está integrando. Esto permite tambien corregir los posibles conflictos que surjan poco a poco y evitar que estos fuesen más pronunciados, que podría ocurrir si se integra todo de golpe.

**9.** C: Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en la rama principal (master).
