# Apuntes_UF2_1

**Pruebas**
+ **Dinámicas:** Requieren la ejecución de la aplicación. Permiten medir el comportamiento de la aplicación desarrollada.
+ **Estáticas:** Se realizan sin ejecutar el código de la aplicación. Se examina el código fuente.

**Estrategias de prueba**
+ **Caja negra:** Se estudia el sistema desde fuera. Son pruebas de funcionalidad.
+ **Caja blanca:** Se examina el código fuente y su ejecución. Son pruebas estructurales.

+ **Estrategias de prueba de caja negra**
    + Se estudia el sistema desde fuera.
    + Se trabaja sobre la interfaz.
    + No se tienen en cuenta los detalles internos de funcionamiento.
    +Se proporcionan entradas y se estudian las salidas.

+ **Obtención de código ejecutable**
    + Se examina el código fuente y su ejecución.
    + Se comprueban los flujos de ejecución dentro de cada unidad (función, clase, módulo, etc.).
    + También pueden comprobarse los flujos entre unidades durante la integración.
    + E incluso entre subsistemas, durante las pruebas de sistema.

**Tipos de pruebas**
+ **Funcionales:** Evaluan el cumplimiento de los requisitos.
+ **No funcionales:** Evaluan aspectos adicionales como rendimiento, seguridad, ...

**Pruebas funcionales**
+ Pruebas unitarias (o de unidad).
+ Pruebas de regresión.
+ Pruebas de integración.
+ Pruebas de humo (smoke test).
+ Pruebas del sistema.
+ Pruebas alfa y beta.
+ Pruebas de aceptación (validación por parte del cliente).

**Pruebas no funcionales**
+ Pruebas de usabilidad.
+ Pruebas de rendimiento.
+ Pruebas de stress.
+ Pruebas de seguridad.
+ Pruebas de compatibilidad.
+ Pruebas de portabilidad.

**Mecanismos de prueba**
+ **Manual:** Mediante pruebas realizadas por personal de la empresa o externo.
+ **Automático:** Mediante software que ejecuta código de forma automatizada y compara los resultados obtenidos y los resultados esperados.

**Soporte del depurador**
+ Puntos de ruptura.
+ Ejecución paso a paso.
+ Análisis de variables.

**Automatización de pruebas** 
+ Frameworks de pruebas (xUnit).
+ Aserciones.

**Frameworks para pruebas**
+ Java: JUnit, TestNG.
+ C++: CppUnit, Google Test.
+ PHP: PHPUnit.
+ Javascript: Mocha.

**TDD (Desarrollo guiado por pruebas de software, o Test-Driven Development)**
+ Escribir las pruebas primero (Test First Development).
+ Refactorización (Refactoring).

**Integración**

**Formas de integración**
+ Integración Big bang.
+ Integración Descendente.
+ Integración Ascendente.
+ Integración Continua (CI).

**Servidores de integración continua**
+ Jenkins.
+ Bamboo.
+ TravisCI.
+ CircleCI.

**Convertura del código**
+ Es una medida que indica el porcentaje de código que ha sido ejecutado durante las pruebas.
+ Es aconsejable que sea lo más cercano a 100%.
+ Si es del 100% entonces se ha ejecutado todo el código fuente durante las pruebas.
+ Si es menor del 100% entonces existe código fuente que no se ha ejecutado durante las pruebas.
+ Es posible realizar la cobertura tanto desde el IDE como desde un servicio web apropiado.

**Calidad**

**Control de calidad**
Para lograr una medición de la calidad de un producto, necesitamos realizar pruebas.
+ **QA:** Es un conjunto de actividades para garantizar la calidad en los procesos mediante los cuales se desarrollan los productos.
+ **QC:*** Es un conjunto de actividades para garantizar la calidad de los productos. Las actividades se centran en identificar defectos en los productos reales producidos.


**Factores de calidad**
+ **Operación del producto**
    + Corrección.
    + Fiabilidad.
    + Eficiencia.
    + Seguridad.
    + Facilidad de uso.
+ **Revisión del producto**
    + Mantenibilidad.
    + Flexibilidad.
    + Facilidad de prueba.
+ **Transición del producto**
    + Portabilidad.
    + Reusabilidad.
    + Interoperatividad.
