# Base de datos

Coleccion organizadad de datos que pertenecen a un cierto contexto

## Clasificación

De acuerdo a su tasa de cambio de sus datos(cantidad de cambios que hay en un tiempo determinado... por ejemplo 30 cambios al día o 100 mil cambios por hora, o simplemente 0 cambios):
  - estática: solo lectura
  - dinámica: lectura y escritura
 

Digamos que tienes una Base de Datos con la Información de los Terremotos del Siglo XX. Esa BD puede considerarse una Base de Datos estática, porque sus datos no van a cambiar, ya que no habrá nuevos Terremotos en el Siglo XX, cierto? De igual manera, un Libro ya impreso puede considerarse también como una BD estática... sus datos no cambiarán jamás.Por otro lado, una BD de un Sistema de Facturación, está en constante cambio... ingresan nuevas facturas, cambian las cantidades de los productos, etc... es Dinámica por que sus datos cambian con bastante frecuencia.Claro está que hay puntos intermedios... dependiento de la cantidad de tiempo que se quiera considerar para definir la tasa de cambio de los datos. Digamos que por ejemplo una base de datos de Fronteras Geográficas de Paises puede ser considerada "relativamente" Estática (si consideramos que sus datos "casi" no cambian) o puede ser considerada "relativamente" Dinámica si comparamos su estado hace 100 años y su estado Actual. Supongamos que yo te vendo por $1 mensual un Servicio en el cual tu seleccionas un color y yo te doy su representación RGB, CYMK, Pantone, y cualquier otro código numérico que pueda existir para representar un color. Desde TU punto de vista, mi Base de Datos es Estática... ya todos los colores están allí y además es de sólo lectura para ti... Desde MI punto de vista mi Base de Datos puede verse como Dinámica ya que cada vez que alguien se inscribe se generan nuevos datos, mensualmente se genera una facturación, los datos van cambiando (aunque ya todos los colores estén allí)
