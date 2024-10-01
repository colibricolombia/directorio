# ¿Cómo contribuir?

Para contribuir con este repositorio puede seguir el proceso de **Pull Request**
que se describe a continuación. En caso de no saber manejar la herramienta `git`
pero desea agregar una comunidad en este listado solicite asistencia en el chat
de [Colibri](https://t.me/ColibriColombia).

## Proceso de Pull Request

1. Proceda a crear un fork del repositorio desde la página del repo en
   [Github](https://github.com/colibricolombia/directorio). (botón en la esquina superior derecha)
2. Clone su fork del repositorio en su computadora, dependiendo de su configuración de autenticación deberá usar:
   - Si usa SSH: `git clone git@github.com:(tú usuario)/directorio.git`. O
   - Si usa HTTPS: `git clone https://github.com/(tú usuario)/directorio.git`.
3. Ingrese a su repositorio (`cd directorio`) y proceda a agregar el repositorio original como `upstream` para que pueda actualizar su contenido respecto al original para futuras actualizacione (`git remote add upstream https://github.com/colibricolombia/directorio.git`).
4. Traiga los ultimos cambios del repositorio original a su fork (`git fetch upstream`).
5. Observe su copia local de la rama `master` (`git checkout master`).
6. Una los cambios del repositorio original `upstream/master` a su rama local
   `master` (`git merge upstream/master`).
7. Repita los pasos 4, 5 y 6 para mantener su repositorio actualizado respecto
   al original.
8. Al agregar un nuevo grupo se debe tener en cuenta que todos los campos son requeridos, siguiendo el siguiente formato:
    - Comunidad: Nombre de la comunidad.
    - Link: Enlace al sitio o grupo de su comunidad.
9. Cuando complete sus cambios, subalos a su copia del repositorio (`git push origin master`).
10. Proceda a realizar o crear un `Pull Request` para solicitar agregar sus cambios al repositorio original usando el botón de pull request que aparece en GitHub.

Una guia detalla de todo este proceso la puede encontrar [aquí](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)

## Sobre los derechos de autor

Al contribuir con este repositorio usted está cediendo su trabajo como
[dominio público](https://creativecommons.org/publicdomain/mark/1.0/deed.es).
