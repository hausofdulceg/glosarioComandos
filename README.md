## glosarioComandos

#Glosario de comandos en MarkDown

1. **pwd**: muestra la ruta en la que se está trabajando
2. **cd**: siginifica "Change Directory" es para cambiar de directorio
3. **cd ..**: regresar al directorio en donde se trabajaba anteriormente
4. **clear**: limpiar consola
5. **echo**: escribe (imprime en pantalla)
6. **touch**: crear un archivo en blanco
7. **mkdir**: crea un directorio/carpeta
8. **cat**: muestra contenido de un texto
9. **ls -l**: muestra los permisos
10. **mv**: mover un archivo
11. **cat**: muestra el contenido de un archivo
12. **history**: muestra el historial de comandos que has utilizado
13. **nano**: editar un archivo mienstras ves su contenido
14. **git status**: ver status de un main
15. **git diff**: ver cambios en un archivo
16. **git log**: quién editó el archivo en el que estás pocisionado de
17. **git log --oneline**: quién editó el archivo en el que estás pocisionado de forma corta
18. **git add**: como mover un archivo
19. **git commit**: guardar un commit
20. **git config --global user.name**: agregar un usuario
21. **git config --global user.email**: agregar el correo del usuario
22. **git status**: ver el estado de los commits
23. **rm -rf .git**: eliminar un proyecto de git
24. **git checkout "hash"**: ver una version
25. **clone**: agarra el repositorio y clona lo que hay en el
26. **git checkout (código hash)**: para regresar a otro commit
27. **git switch -c (nombre nuevo)**: cambiar el nombre de un commit
28. **git log —oneline —graph —all**: muestra todos los commits del proyecto de forma gráfica
29. **git log —oneline —all**: muestra todos los commits
30. **git log —oneline**: muestra los commits del lugar en donde estás posicionado
31. **git checkout (nombre de rama)**: cambiar de posición
32. **git status -s**: para ver el status de forma corta
33. **git checkout -b rama2**: para crear la rama y saltar a ella


**Código para definir GitBash como terminal default**
{
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 5000,
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "terminal.integrated.env.windows":{
        "CMDER_ROOT":"C:\\Users\\AlumnoFCA\\Desktop\\cmder"
    },


    "terminal.integrated.profiles.windows": {
          "cmder": {
            "path": "C:\\WINDOWS\\System32\\cmd.exe",
            "args": ["/K", "%CMDER_ROOT%\\vendor\\bin\\vscode_init.cmd"]
          }
        },
        "window.zoomLevel": 1,
    
}
