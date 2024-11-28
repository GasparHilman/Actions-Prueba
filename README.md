
# CREAR ACTION
  * Si en la barra de arriba del repositorio no aparece una pestaña que dice Actions, hay que ir a la pestaña Settings/configuración -> Actions, y activar los Actions.
    
    Ya en la parte de Actions tenemos dos opciones, buscar una plantilla o crear uno desde cero. Lo ideal es primero buscar con palabras claves un workflow ya hecho que nos pueda servir y editarlo, y si no hay ninguno crearlo vacío.
  De las dos maneras lo que pasa cuando creamos un action es que se genera un archivo yml en la carpeta .github/workflows. Para configurar el Action hay que ir a esa carpeta y modificar el archivo .yml. 

## Costos
  Github Actions es gratis para repositorios publicos, y para privados hay una determinada cantidad de horas de compilación gratuitos. Con el plan gratuito de Github, se pueden hacer hasta 2000 minutos de compilación por mes. El tiempo de compilación va a depender de varios factores: la cantidad de Jobs, la duración de cada uno, y del sistema operativo en el que corre el Action.
  Github te permite elegir el sistema operativo en el que corre el Action, pero cada uno tiene un multiplicador de tiempo. 
  * Ubuntu tiene multiplicador x1, es decir que un minuto de compilación cuesta un minuto de los 2000 minutos gratuitos
  * Windows tiene multiplicador x2, osea que 1 minuto de compilación restaría 2 minutos de los 2000 gratuitos.
  * Mac tiene multiplicador x10, 1 minuto de compilacion gastaria 10 minutos de los 2000 que nos da github.
