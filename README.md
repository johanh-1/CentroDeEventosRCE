# Centro de Eventos RCE
Herramienta realizada para un centro de eventos que facilita la gestión y asignación de la facturación. El nombre de la empresa, de los expositores y la información de los servicios fueron cambiados para garantizar la privacidad del cliente.

## Contexto
Centro de Eventos RCE es una empresa que organiza eventos culturales propios y también ofrece el alquiler de sus instalaciones para eventos privados. Esta empresa tenía un archivo de Excel en el que ingresaban los servicios prestados a los diferentes expositores que hacían parte de los eventos organizados. Estos servicios estaban divididos en distintas áreas como ***electricidad***, ***Redes***, ***Maquinaria***, ***Mobiliario*** y ***Audiovisuales***, el problema es que mucha gente debía ver este archivo de Excel al mismo tiempo y era muy demorado mirar cuales registros pertenecían a las diferentes áreas, además, se subían servicios nuevos varias veces al día.

## Solución
Con el fin de disminuir el tiempo y los errores asociados a la búsqueda de información en una tabla grande de información (Hoja ***Facturación***) se realizó, con ayuda de ***Power Query*** y ***Power Pivot***, sub tablas para cada una de las áreas deseadas que se alimentaran de la tabla principal y permitieran acceder a la información de una forma más sencilla. Es decir, si un usuario quería acceder a la información sobre los servicios de ***electricidad*** solamente debía ingresar a la hoja ***electricidad***. Por otro lado, si otra persona diferente quería ingresar un nuevo servicio podía simplemente agregarlo en la tabla principal (hoja ***Facturación***) y luego ir a la hoja asociada al nuevo servicio y actualizar la tabla.

A continuación se muestran imágenes de como son las hojas ***facturación*** y ***electricidad*** y un video demostrativo.

### Hoja facturación
![image](https://github.com/johanh-1/CentroDeEventosRCE/assets/136139101/0d977f22-3deb-4423-9e48-d5c050fc132c)

### Hoja electricidad
![image](https://github.com/johanh-1/CentroDeEventosRCE/assets/136139101/e3e8184b-98a8-4466-b8bd-2b4279534956)

### Video 
https://github.com/johanh-1/CentroDeEventosRCE/assets/136139101/66e31e27-5a62-4528-bc63-6ab93139a892
