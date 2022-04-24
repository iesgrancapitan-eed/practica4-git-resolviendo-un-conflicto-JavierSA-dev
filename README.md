# Tarea 4.11. Practica4. Git. Resolviendo un conflicto


1. Asegúrate de que tienes configurado el editor Visual Studio Code como tu editor de Git. (git config --global core.editor "code --wait")

    ![1](img/1.png)

2. Crea un repositorio local y avanza en la rama "master" añadiendo un fichero "index.html" con la estructura básica html. El body estará vacío

    ![2](img/2.png)
    ![3](img/3.png)
    ![4](img/4.png)


4. Crea y salta a "rama-1". Avanza en un commit con tu nombre de pila en un párrafo dentro del body

    ![5](img/5.png)


5. Vuelve a la rama master

    ![6](img/6.png)
    

6. Crea y salta a "rama-2". Avanza en un commit con tu apellido en un párrafo dentro del body

    ![7](img/7.png)
    ![8](img/8.png)


7. Muestra el estado del repositorio de forma gráfica y resumida

    ![9](img/9.png)

8. Haz un merge a rama-1. Intentas fusionar ambas ramas. Aparecerá un conflicto porque ambos commits trabajan en la misma porción <body></body> de un mismo archivo index.html. Git no será capaz de fusionarlas directamente. 

    ![10](img/10.png)

9.  El editor VS Code reconoce los conflictos de fusión. Las diferencias se resaltan y hay acciones en línea para aceptar los cambios. Deja un único párrafo con tu nombre de pila y apellido.

    ![11](img/11.png)
    Hacemos click en aceptar ambos cambios
    ![12](img/12.png)


10. Una vez que se resuelto el conflicto confirma el archivo en conflicto para que pueda realizar esos cambios

    ![13](img/13.png)

11. Muestra de nuevo el estado del repositorio de forma gráfica y resumida
    
    ![14](img/14.png)

12. Vuelve a la rama master y realiza otro merge. Es una fusión fast-forward. Los dos commits a fusionar tienen relación de ancestro. Entonces el merge no produce un commit nuevo, sencillamente avanza la rama, "avance rápido"

    ![15](img/15.png)

13. Visualiza las ramas que han sido fusionadas con la rama master

    ![16](img/16.png)

14. Elimina las ramas correctamente fusionadas (sin asterisco) para quedarte SOLO con la rama master. 

    ![17](img/17.png)

15. Realiza una copia a este repositorio remoto

    ![18](img/18.png)

16. Recuerda añadir estas instrucciones con los pantallazos en el fichero README.md
17. En GitHub entra en Insights/network y visualiza el gráfico del repositorio con los merge y cinco commits  
