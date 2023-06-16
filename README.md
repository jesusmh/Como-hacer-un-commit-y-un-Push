# Como-hacer-un-commit-y-un-Push

# Pasos para hacer un commit y un push con el cliente GIT
Los pasos son realmente muy simples, primero vamos a chequear el estado de nuestro repositorio (siempre suponiendo que ya lo tenemos clonado en nuestra computadora). Para esto vamos a ejecutar el siguiente comando.

```sh
git status
```
Al ejecutar el comando anterior se van a mostrar los archivos que fueron modificados y los que fueron agregados al índice para luego subir. Además se mostrará los commit realizados y listos para pushear.

En caso de que haya archivos sin agregar al índice hay que ejecutar el siguiente comando.

```sh
git add *
```
Luego hay que generar el commit, para esto vamos a ejecutar el siguiente comando. En este punto es muy importante agregar un comentario bien descriptivo, para que quede en el historial y se utilice cuando sea necesario.

```sh
git commit -m "Un comentario de lo que se hizo"
```

Por último vamos a ejecutar el comando para hacer el push.

```sh
git push origin master
```
Siempre al ejecutar el último comando te va a pedir las credenciales de tu usuario, así que es muy importante saberlas.

Eso es todo lo que hay que hacer para realizar un push con GIT y poder subir todo el código fuente. Ante cualquier inconveniente no duden en dejar un comentario.

Creditos a:
https://unipython.com/como-hacer-un-commit-y-un-push-con-git/
