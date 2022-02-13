El presente repositorio contiene una serie de notebooks (jupyter notebook) con codigos que permitan aprender y aplicar tanto librerias,
tecnicas, metodos y modelos de Machine Learning.

**Importante**: Los códigos realizados tienen como base consulta a la documentación de la libreria, incluyendo su uso y ejemplos, así como
algún libro, foro o blog vinculado. 

Principales fuentes consultadas o de material extraido como imagenes u otra forma:
  1) Aurélien Géron (O'Reilly) : Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow
  2) Andreas C. Müller and Sarah Guido (O'Reilly): Introduction to Machine Learning with Python A Guide for Data Scientists
  3) tensorflow.org
  4) scikit-learn.org
  5) tslearn.readthedocs
  6) otras librerias/repositorios/blogs/foros vinculados

**Nota**: En algunos casos puede que se deba modificar el código debido a cambios en la libreria en versiones nuevas, generandose alguna incompatibilidad
que genere algún error en caso de ejecutarse.

**Cuidado**: Casos observados de potencial error en versiones nuevas de librerias
1) El retorno de alguna funcion de scikit no devuelve formato numpy sino dataframe o viceversa generando inconsistencia al colocarse X[indice] (numpy) vs X.iloc[indice] (pandas) 
