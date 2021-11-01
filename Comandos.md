# Comandos Git
1. git version
- Para poder ver que versión tenemos

2. git config --global user.name "nombre"
- Creación de nombre de usuario

3. git config --global user.email email@dominio.com
- Creación de email para el user

3. git init
- Inicializa el repositorio local

4. git add nombre-de-archivo
- El archivo es seguido y se agrega al staging

5. git commit -m "Mensaje que defina los cambios hechos"
- Se hace el commit para ser añadido al repositorio

6. git status (se le puede añadir -s para ver menos detallado el estado)
- Se hace para ver el estado del proyecto

7. git log (se le puede añadir --oneline para ver menos detallado el estado)
- Se hace para ver los commit del proyecto. Se ve el código, la rama y el commit

8. git checkout código-de-commit
- Se devuelve a un commit sin eliminar los demás commits

9. git show
- Para ver historial del proyecto

10. git reset código-de-commit --hard o --soft
- Se usa para volver a un commit eliminando los que tenga por delante. El soft conserva lo que haya en el staging

11. git brach
- Muestra las ramas

12. git brach nombre-de-rama
- Crea una nueva rama con el nombre especificado

12. git checkout nombre-de-rama
- Se mueve a la rama especificada

13. git merge nombre-de-rama
- Se fusionan la rama master a la rama especificada

14. git remote add nombre-del-remote url
- Se conecta con un repositorio en github

15. git remote -v
- Se ven los repositorios remotos conectados

16. git clone 
- Copia el repositorio remoto a la computadora

17. git push nombre-del-remote nombre-de-la-rama
- Envia el repositorio local al remoto

18. git pull nombre-del-remote nombre-de-la-rama
- Trae los ultimos commit a la computadora