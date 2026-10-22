**MODELOS DE BASES DE DATOS: MODELO EN RED:**

**1- Introducción:** 

El modelo en red es un tipo de base de datos que organiza la información mediante registros conectados entre sí por enlaces. A diferencia del modelo jerárquico, permite que un registro tenga varios registros relacionados, formando una estructura similar a una red.

**2- Modelo y estructura:**

El modelo en red estructura la información mediante registros y enlaces que dan lugar a relaciones entre los datos. Su estructura tiene forma de red, ya que un mismo registro puede estar conectado con varios registros diferentes.

Los datos se agrupan en registros, que contienen información sobre elementos concretos, como empleado, encargado o directivo. Estos registros se relacionan mediante enlaces que permiten navegar de uno a otro y acceder a la información relacionada.

Una de sus principales ventajas es que permite establecer relaciones de uno a muchos y de muchos a muchos. Por ejemplo, un alumno puede estar matriculado en varias asignaturas y cada asignatura puede tener varios alumnos.

Gracias a esta estructura, el modelo en red permite representar relaciones complejas entre los datos y ofrece mayor flexibilidad que el modelo jerárquico, aunque su gestión puede resultar más complicada.

**3: Ventajas e inconvenientes:** 

Como todo modelo de bases de datos presenta sus virtudes y sus defectos:

\-Ventajas: 

**\-Mayor flexibilidad**: permite establecer relaciones más complejas.

**\-Relaciones múltiples**: un registro puede estar conectado con varios registros, facilitando las relaciones entre muchos usuarios

**\-Acceso rápido a los datos**: los enlaces directos entre registros permiten recuperar información relacionada de forma eficiente.

**\-Mejor representación de la realidad:** permite modelar situaciones complejas, como alumnos matriculados en varias asignaturas.

\-Inconvenientes: 

**Mayor complejidad**: diseñar y mantener la estructura de enlaces requiere  más conocimientos técnicos.

**Dependencia de la estructura**: para acceder a los datos es necesario conocer las rutas y conexiones entre los registros.

**Menor flexibilidad para realizar consultas**: modificar la estructura o realizar consultas nuevas puede resultar complicado.

**Evolución limitada**: posteriormente, el modelo relacional simplificó la organización y consulta de los datos mediante tablas y lenguajes como SQL.

El modelo en red supuso un gran avance durante los años 60-70 ya que fue capaz de dejar atrás algunas limitaciones del modelo jerárquico y permitio representar relaciones más complejas

Un dato importante es que debido a su complejidad se terminó favoreciendo más el uso del modelo relacional.

4: Ejemplos de uso:

 El modelo en red se utilizó principalmente en grandes empresas durante las décadas de 1960, 1970 y 1980, especialmente para gestionar grandes cantidades de información relacionada.

Algunas empresas que usaron este modelo fueron las siguientes:

General Electric (GE): desarrolló el sistema Integrated Data Store (IDS) en los años 60 para gestionar información industrial, como la producción, los pedidos y el inventario. 

Weyerhaeuser: empresa del sector maderero que utilizó el sistema WEYCOS desde 1965 para gestionar pedidos y operaciones comerciales. 

B. F. Goodrich: adaptó el sistema IDS para ordenadores IBM, dando lugar a IDMS, un sistema de bases de datos utilizado posteriormente en grandes organizaciones. 

British Telecom: utilizó bases de datos IDMS en sistemas de atención al cliente y gestión de servicios de telecomunicaciones. 

Actualidad: aunque el modelo relacional es mucho más común, algunos sistemas basados en el modelo en red siguen presentes en aplicaciones empresariales antiguas (sistemas heredados), especialmente en entornos de grandes ordenadores centrales o mainframes.

