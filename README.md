# 1NetzumRepositorio
Primer repositorio creado como prueba de git para el curso de Python de la plataforma Netzum

Modificando el primer repositorio para el curso de Netzum

Otros comandos
1.- git status                      -> me permite ver el estado de sincronización con el repositorio en github
2.- git tag v1.0                    -> se usa generalmente en rama master o main para crer versiones del proyecto


Pasos para actualizar en github mi repositorio
1.- git add .                       -> Se agregan todos los cambios y modificaciones que se hicieron al repositorio en una sola vez
2.- git commit -m 'comentario para identificar ese cambio'
3.- git push origin maim
4.- git pull origin main            -> actualiza todos los cambios del repositorio dremoto al repositorio local


Para cambiarse de ramas
1.- git checkout main                -> salgo de la rama main
2.- git checkout -b nombreRama       -> crea una nueva rama con el nombre que se le  dé y me posiciona en ella.
3.- git add archivoASincronizar.formato    -> agrega para actualizar solo los cambios hechos en el archivo a sicronizar pero en la rama en la que te encuentres
4.- git commit -m "mensaje"
4.- git push origin ramaEnLaQueSeSincronizará  -> sincronizará los cambios en el archivo pero solo para la ramaEnLaQueSeSincronizará