# daw2

## clase 1

- Crear una cuenta en Github 
- Crear un nuevo repositorio: daw2
- Instalar git
- Si aparece un error "no se pudo bloquear /var/lib/dpkg/lock ... 
  introducir la siguiente instrucción: ```sudo fuser -vki /var/lib/dpkg/lock```
  y volver a instalar git.
```sudo apt install git```

### Instrucciones básicas git

- clonar el repositorio remoto ```git clone url```
- ver estado repositorio local
```git status```
- Hacer un *commit*(compremeter) los cambios al repositorio local
```git commit -am "mensaje"```
- subir (push) los cambios del repositorio local el repositorio remoto:
```git push origin master```
- Actualizar (pull) el repositorio local con los cambios desde el           repositorio remoto ```git push origin master```