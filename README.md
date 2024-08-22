INTEGRANTES
- Samuel Felipe Díaz Mamanche
- Santiago Silva Roa

RESPUESTAS PREGUNTAS: 

1- Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”

El comando Git Add se utiliza para agregar archivos o agregar cambios en el repositorio actual donde se este desempeñando un trabajo.
El comando git commit -m “mensaje” se utiliza para crear un commit que es una captura de los cambios en el repositorio de ese momento. El "-m "mensaje"" permite agregar una descripcion al commit directamente en la linea de comando.

2 - Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo. ¿Que sucedió?

En el momento de actualizer al mismo tiempo, nos genero un conflicto, esto quiere decir que git no sabe que archivo tomar para "hacer push" o para actualizarlo.

3 - ¿Hay una mejor forma de trabajar con git para no tener conflictos?

Existen varias practicas o funciones que ayudan a resolver conflictos en GIT. uno de ellos es usar ramas individuales (cada integrante del trabajo) en vez de trabajar en la rama principal, sirve para aislar los cambios y reducer las posibilidades de conflicto. Tambien, trabajar con pull request (explicion en el proximo punto) es una opcion viable.

4 - ¿Qué es y como funciona el Pull Request?

Un pull request realiza commits pequeños y frecuentes,facilita la revision de los cambios con cometarios o mensajes. Tambien, es facil para resolver un conflicto cuando hay pocos cambios implicados.