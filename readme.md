Este proyecto está destinado a cubrir los conocimientos de Java con el framework Spring Cloud Netflix atacando una base de datos no relacional, MongoDB y otras tecnologías.
<a name="indice"></a>
## Indice
---
1. [Descripción del proyecto](#item1)
2. [Paneles](#item2)
3. [Repositórios](#item3)

<a name="item1"></a>
## Descripción
---
Puedes leer la descripción del proyecto 
Un cliente del sector empresarial dispone de una aplicación para gestionar la flota de coches de su empresa. Después de analizar los problemas de rendimiento de la aplicación, han detectado que el diseño les está causando cuellos de botella.

Para ello nos han pedido que realicemos una nueva api REST orientada a microservicios que favorezca el escalado y una posterior migración a los sistemas Cloud.

Después de una serie de reuniones con el cliente y realizado el análisis correspondiente se describe la siguiente situación:
* El cliente dispone de una serie de coches de varios modelos.
* Cada coche se define a través de su matrícula.
* El cliente dispone de varios coches del mismo modelo.
* De cada coche el cliente necesita registrar la siguiente información:
    * Las turbulencias generadas por los siguientes elementos: el morro, ambas alas con sus respectivos motores y la cola del avión.
    * El peso del coche en las siguientes situaciones: lleno de combustible, con pasajeros completo, y el peso máximo reservado a las maletas.
    * La distancia máxima que puede recorrer el coche en franjas de 60 120 180 minutos.
* De cada modelo se necesita registrar:
    * El código del modelo.
    * La descripción del modelo.
    * Los coches asociados al modelo.
* De cada matrícula:
        ◦ El código de la matrícula.
        ◦ La descripción de la matrícula.
        ◦ El coche asociado a la matrícula.
* Un coche se puede vender a otro particular o empresa, pero debe quedar registrado de forma interna ya que el cliente no quiere perder el histórico de los coches que han pasado por su compañía.
* Las operaciones que realiza la aplicación actualmente son:
    * Alta, baja y modificación de aviones y modelos de avión.

A nivel técnico se requiere lo siguiente:
* Los servicios deben ser implementados:
    * En java versión 8.
    * Se debe usar el framework Spring Boot en su versión más actualizada.
    * La marca del gestor de base de datos se debe poder cambiar sin que eso suponga un cambio de código en el proyecto.
    * Para la realización de los test unitarios se utilizarán los framework, Junit, Mockito y AssertJ.
## Paneles:
---
<a name="item2"></a>
- Front-End: https://github.com/JavierLobo/gescoches-fontend/projects/1
- Back-end: https://github.com/JavierLobo/gescoches-backend/projects/1

## Repositórios:
---
<a name="item3"></a>
- https://github.com/JavierLobo/gescoches-fontend
- https://github.com/JavierLobo/gescoches-backend

[Volver Arriba](#indice)