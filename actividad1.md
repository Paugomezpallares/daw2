## Sistemas de control de versiones. Git
### Paso 1:
-   Primero de todo, vamos a crear una carpeta con nombre ejercicio.
-   Entramos dentro con la orden cd ejercicio/
-   Inicializamos el repositorio en Git, git init.
-   Con git status veremos en la rama que estamos y si hay algún commit.
 ![foto](https://github.com/Paugomezpallares/daw2/blob/master/1.png)

### Paso 2:
- Vamos a crear un script para que el usuario introduzca números.
- Con nano script.sh entramos al script y hacemos las preguntas al usuario.
- Con el comando -> ./script.sh ejecutamos el script y le hará las preguntas al usuario.
- Ejecutamos el comando -> git commit -am "primer commit" para guardar los cambios.
![foto](https://github.com/Paugomezpallares/daw2/blob/master/buena.png)
![foto](https://github.com/Paugomezpallares/daw2/blob/master/3.png)
![foto](https://github.com/Paugomezpallares/daw2/blob/master/6.png)
  
  ### Paso 3:
  - Creamos una rama con nombre rama1 para guardar el script modificado -> git checkout -b rama1.
  - Como nos han pedido que modifiquemos el script, entramos en el -> nano script.sh
  - Modificamos el script para que pida un número más.
  - Lo ejecutamos -> ./script.sh
  - Guardamos los cambios con -> git commit -am "suma de 3 números"
  - Regresamos a la rama master con -> git checkout master.
  - Ejecutamos el script -> ./script.sh en la rama master para comprobar que sigue como la primera vez(la suma de dos números).
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/5.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/4.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/7.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/8.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/19.png)
  
  ### Paso 4:
  - Creamos una nueva rama -> git checkout -b rama2.
  - Modificamos el script -> nano script.sh.
  - Guardamos el script con -> git commit -am "mensaje previo"
  - Regresamos a la rama master -> git checkout master
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/11.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/10.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/8.png)
  ### Paso 5:
  - Integramos la rama2 en master, con -> git merge rama2
  - Eliminamos la rama2, con ->git branch -d rama2
  - Integramos la rama1 en master, con git merge rama1.
  - Eliminamos la rama1, con ->git branch -d rama1.
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/13.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/14.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/15.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/16.png)
  
  ### Paso 6: 
  - Instalamos meld -> sudo apt install meld
  - Git mergetool -> No hay conflictos.
  - Mostramos el git log.
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/17.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/18.png)
  ![foto](https://github.com/Paugomezpallares/daw2/blob/master/20.png)
