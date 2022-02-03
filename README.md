# Documentación de la Carrera de Diseño gráfico
Este es un repositorio de documentación de la carrera de Diseño Gráfico de la Facultad de Artes de la Universidad de Cuenca. 

El proyecto está construido con la ayuda de [Sphinx](https://www.sphinx-doc.org/en/master/index.html) para producir el sitio web estático y el pdf de la documentación .

El objetivo de este proyecto es presentar la documentación de la facultad de forma ordenada y actualizada. Esta incluye sílabos, contenidos, procesos importantes, formatos, estructura de la malla

## Contribución al proyecto.

Para iniciar la contribución a este proyecto debes considerar que el esquema de desarrollo está estructurado usando los principio de [GitFlow](https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=Gitflow%20es%20un%20modelo%20alternativo,vez%20y%20quien%20lo%20populariz%C3%B3.). 

Haz una bifurcación del repositorio en tu cuenta de github y clona el repositorio en tu ambiente local de desarrollo.

## Instalación:

Sphinx funciona con Python así que se puede trabajar con un Ambiente Virtual (venv). Para crear uno ingresa en la carpeta razíz del repositorio y usa este código:

```
python3 -m venv .venv
```

Esto crea una carpeta `.venv` con el ambiente virtual. Una vez creado el ambiente es necesario activarlo con: 

```
source .venv/bin/activate
```

Sabemos que el ambiente está activado cuando vemos `(.venv)` al inicio de la línea de terminal.

A continuación hay que instalar Sphinx:

```
pip install sphinx   
```

Alternativamente se ha creado un archivo llamado **requirementes.txt** que contienen todas las dependencias que se están usando en el actual ambiente virtual. Para instalarlas solo usa este código:

```
install -r requirements.txt
```

Para volver a generara este archivo, en caso de agregar dependencias al proyecto, se utiliza este código:


```
pip freeze > requirements.txt
```
