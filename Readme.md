## Depliege de apps Spring boot en Heroku

Crear archivo "system.properties" en el proyecto con el contenido:

java.runtime.version=17

1. Crerar cuenta en Heroku.com y Github.com
2. Tener configurado Git en el ordenador
   1. git config --global user.name "Diego Fernandez"
   2. get config --global user.email diegofeva@gmail.com
3. Subir el proyecto a Github desde Intelij IDEA desde la opcion: VCS > share project on github
4. Desde Heroku crear app y elegir metodo Github, buscar el repositorio subido
5. Habilitar deploy automatico y ejecutar deploy