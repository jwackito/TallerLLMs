# Taller de LLMs
Repositorio con datasets y ejemplos para el Taller de Large Language Models
- Primera edición - 2024 (Para LIFIA)

## Como usar este repositorio
Hacé un fork a tu github para poder hacer Push Requests de manera cómoda. Además, así es más fácil dejar constancia de la autoría de las contribuciones. Luego, `git clone` a una copia local desde tu repo.
```
git clone git@github.com:<tu_usuario_de_github>/TallerLLMs.git
```
Si queres hacer algún aporte, no dudes en pedirme un Pull Request.

## Necesario durante el taller (Growing...)
Aquí iremos detallando las herramientas necesarias para el taller, en cuanto a software y tools copadas que puedan sernos útiles.

### Conda Environments
Vamos a hacer uso extensivo de conda para no contaminar el Python del sistema con todas las librerías que vamos a instalar. Además, conda nos va a permitir trabajar con versiones específicas de algunas librerías, e incluso versiones de Python específicas.

Mi sugerencia es instalar [Miniconda 3](https://docs.anaconda.com/miniconda/). Hay un [tutorial muy bueno en inglés](https://www.whiteboxml.com/blog/the-definitive-guide-to-python-virtual-environments-with-conda) y [uno mejorable en castellano](https://github.com/jwackito/conda-environments-tutorial/blob/main/Conda%20Environments.md) (se aceptan pull requests) con todo lo que van a necesitar saber sobre instalar, crear y administrar conda virtual envs.

### Jupyter Hub/Lab (opción 1)
[JupyterHub](https://jupyter.org/hub) es una versión multiusuario de los Jupyter Notebooks. Por si no conoces lo Jupyter Notebooks, básicamente es una consola interactiva de Python que funciona desde el navegador. JupyterHub tiene además la posibilidad de correr los notebooks usando diferentes kernels (una instancia de python instalada en un conda env, con una serie de librerías instaladas). Trabaja a nivel de celdas y permite editar y ejecutar secciones pequeñas de código de manera cómoda. El Lab además permite crear proyectos y administrar kernels de manera cómoda.

### Ipython (opción 2)
Una consola de python interactiva con esteroides. La verdad yo lo prefiero a JuptyerHub excepto en muy contados casos. Es super liviana y potente. Viene con magia incluida (%magics). Se puede tunear y escriptear a gusto. Sin duda una de las mejores opciones para correr celdas de python de manera interactiva. Si les digo que hice mi doctorado casi exclusivamente usando esta herramienta no me estaría quedando corto. Sin embargo es una herramienta para la terminal (no tienen entorno gráfico). Si no estás cómodo en la terminal, mejor usar JupyterHub.

### Numpy
Para el primer encuentro (la parte de brigramas) solo hace falta numpy. Es una librería de algebra lineal super potente, que permite operaciones vectorizadas y si uno se da un poco de maña, es posible modelar integramente in LLM usando exclisivamente esta librería. Por comodidad, luego usaremos Torch, pero por ahora, Numpy alcanza. 

---
No olvides darme una estrellita en github si este repo te sirvió!
