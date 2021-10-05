
# CC_21_22

Repositorio de la asignatura de Cloud Computing perteneciente al Máster en Ingeniería Informática de la Universidad de Granada.


## MantCAR

### Antecedentes

Gran parte de la población española dispone de un vehiculo a motor en propiedad. Concretamente en el año 2016 había [479 vehiculos por cada 1000 habitantes.](https://www.lavanguardia.com/vida/20160911/41235900406/en-espana-hay-479-automoviles-por-cada-1000-habitantes.html)

Para su correcto funcionamiento los vehiculos necesitan mantenimientos de multitud de piezas
(embrague, correa de distribubución, aceite, filtros...). Si a esto se le suma que los vehiculos sufren averías a lo largo del tiempo, al final se hace dificil llevar un control de todas las reparaciones que se le han realizado.

En la actualidad no existen herramientas específicas que gestionen esta situación. Hace algunos años había un par de aplicaciones móviles que desempeñaban esta tarea, pero desafortunadamente los desarolladores dejaron de darle soporte y quedaron obsoletas.

### Solución y lógica de negocio

Crear un servicio donde el responsable del taller mecánico introduzca las referencias de las piezas, descripcion y precio.

- El cliente obtendrá un informe detallado del trabajo realizado. Además tendrá la posibilidad de realizar búsquedas y tener un registro de las averías y mantenimientos.
- El taller dispondrá de un registro de los trabajos realizados a un determinado vehiculo.

Al disponer de las referencias de las piezas (que son identificadores únicos) y el precio que se ha pagado por ellas, se realizará un analisis de la tendencia del precio de cada repuesto, de la estimación de precio en el futuro y de estadisticas que permitan al distribuidor de repuestos anticiparse. Un ejemplo de esto último es que en verano las averias más comunes son las relacionadas con el sistema de aire acondicionado.

Estos datos son valiosos para los distribuidores de piezas ya que, les permiten ajustar el precio al que venden cada repuesto y anticiparse a temporadas donde ciertas piezas se venden más. 

#### Documentación adicional sobre la configuración de GitHub :octocat:



